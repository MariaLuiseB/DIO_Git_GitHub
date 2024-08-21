# Desfazendo Alterações no Repositório Local

## Apagando um repositório .git
Exemplo: Digamos que você tenha inicializado uma pasta com o git sem querer.
Solução: 
1º vá a pasta que você quer remover e remova a força todo o repositório git

```
rm -rf .git
```
**ATENÇÃO**: Ele descarta TODAS as últimas alterações.


## Restaurando o último commit do repositório local
Exemplo: Digamos que você sem querer tenha apagado uma parte do código e queira **restaurar** ele.
Solução:
```
git restore <nome do arquivo>
```
Ou você pode também estar fazendo: 
```
git restore --staged <nome do arquivo>
```
Para depois poder adicionar com git add . e aí commitar novamente. 

## Corrigindo comentário do commit já realizado
```
git commit --amend -m "frase nova"
```
Caso você queira escrever um comentário maior, basta escrever:
```
git commit --amend
```
E depois dar Enter, ele irá abrir seu editor de texto (se utilizar Vim, você aperta a tecla i e escreve o quanto quiser, ao sair é só digitar Esc:w)


## Desfazer comentário do commit já realizado
Exemplo: Caso você queira desfazer o comentário do commit e voltar para o commit anterior você usará o: 
```
git reset
```

Ele nos dá 3 opções:
1. ``` git reset --soft <hash do commit>```

    Esse aqui apenas remove o último comentário do último commit não apagando ele.

2. ```git reset --mixed <hash do commit>```

    Esse aqui é a mesma coisa que git reset (sem escrever mixed), ele faz com que se perca a referência do commit e deixa ele como **UNTRACKED FILES**

3. ```git reset --hard <hash do commit>```

    Esse aqui apaga a referência, o commit e o comentário, é como se você não tivesse feito NENHUM COMMIT, não sobre nadinha.

