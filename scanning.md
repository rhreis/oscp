---
description: Nmap para diversas finalidades
---

# 🔍 Scanning

## Scan básico para identificar máquina ativa.

```
nmap -v HOST-IP
```

## Scan as top 10 portas abertas

```
nmap -v -Pn --open --top-ports 10 HOST-IP
```

## Scan todas as portas abertas

```
nmap -v -Pn --open -p- HOST-IP
```

## Scan lista de portas abertas com as informações da versão dos serviços

```
nmap -v -Pn -sS -sV --open -p22,80 HOST-IP
```

