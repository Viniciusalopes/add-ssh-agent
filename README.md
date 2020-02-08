# add-ssh-agent:

## O que faz este script?
 
- Verifica se existe o diretório padrão para chaves ssh (/home/user/.ssh);

- Exibe um menu com a lista de chaves disponíveis;

- Inicia o ssh-agent;

- Adiciona a chave ssh selecionada, e solicita a senha.


## O que falta esse script fazer?

Está nos meus planos, verificar qual é o sistema operacional e disponibilizar a adição da chave no ssh-agent para Windows.

## Instruções

Em um emulador de terminal, execute os comandos abaixo:

- Para fazer o download do script

```wget https://raw.githubusercontent.com/Viniciusalopes/add-ssh-agent/master/add-ssh-agent -O /tmp/add-ssh-agent```

- Para fazer o executar o script

```/usr/bin/env bash /tmp/add-ssh-agent```

---
### FONTES
[Ajuda do GitHub](https://help.github.com/pt/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

---

Vovolinux: Sem trauma e sem teoria!
