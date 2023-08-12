# Instrução para encontrar um CPF

## Instrução para encontrar um CPF sob o formato 999.999.999-99.

```
cat teste.txt | grep -E '[0-9][0-9][0-9][\.][0-9][0-9][0-9][\.][0-9][0-9][0-9][-][0-9][0-9]'
```
