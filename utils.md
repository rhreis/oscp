---
description: Comandos para socorrer na hora do sufoco
---

# 🆘 Utils

## Melhor shell interativo com Python

```
python3 -c 'import pty;pty.spawn("/bin/bash")'
```

## Melhorar shell interativo com RLWRAP

```
rlwrap nc -nvlp 4444
```

## Procuar por Diretório com permissão de escrita

```
find / -writable -type d 2>/dev/null
```

## Procurar por arquivos com permissão swing bit ativo SUID

```
find / -perm -u=s -type f 2>/dev/null
```

