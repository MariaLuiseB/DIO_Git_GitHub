# Salvando Alterações no Repositório Local

## Comandos de Visualização para o Git
**Mostre**, por exemplo, a pasta aulas com o gitkeep

``` 
mkdir aulas
touch aulas/.gitkeep
```

**Ignore**, por exemplo, a pasta resumos com o gitignore

```
echo resumos/ > .gitignore -- jogando para dentro
```

Para olhar o status para verificar as alterações do arquivo/pasta basta dar um:
```
git status
```

Para olhar QUEM FEZ as alterações do arquivo/pasta basta dar um:
```
git log
```