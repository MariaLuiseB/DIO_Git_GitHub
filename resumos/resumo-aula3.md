# Desfazendo Alterações no repositório local

Exemplo: Digamos que você tenha inicializado uma pasta com o git sem querer.
Solução: 
1º vá a pasta que você quer remover e remova a força todo o repositório git

```
rm -rf .git
```

Exemplo: Digamos que você sem querer tenha apagado uma parte do código e queira **restaurar** ele.
Solução:
```
git restore <nome do arquivo>
```
**ATENÇÃO**: Ele descarta TODAS as últimas alterações.



