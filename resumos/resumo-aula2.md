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

Para visualizar o status para verificar SE HÁ ALGUMA alteração a ser COMMITADA DE ALGUM arquivo/pasta basta dar um:
```
git status
```

Para visualizar QUAIS alterações/commit's e QUEM as fez do arquivo/pasta basta dar um:
```
git log
```

Ele retornará O HASH DO COMMIT, AUTHOR, DATA e HORA e COMENTÁRIO DO COMMIT:
```
commit 1ad2029ac1d34950e95621c91c4e999d58df40ff <<<- ESSE É O HASH DO COMMIT
Author: MariaLuiseB <marialuisebritto@gmail.com>
Date:   Tue Aug 20 20:20:28 2024 -0300

    commit inicial
```

Para visualizar um histórico mais detalhado do que foi feito:
``` 
git reflog
```
