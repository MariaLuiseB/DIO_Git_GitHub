# Comando Úteis no Dia a Dia

git fetch
git diff
git clone <url do repositorio> --branch <nome da branch requisitada> --single-branch
git stash e git stash list

# Comandos Úteis no Dia a Dia

## ``git fetch``
O comando `git fetch` baixa commits, arquivos e referências de um repositório remoto para o seu repositório local, mas não faz merge dessas mudanças na sua branch atual.

**Exemplo:**
```sh
git fetch origin
```
Isso baixa todas as mudanças do repositório remoto chamado origin, mas não as aplica na sua branch atual.

## ```git diff```
O comando git diff mostra as diferenças entre commits, branches, arquivos, etc. É útil para ver o que mudou entre duas versões de um arquivo ou entre o estado atual e o último commit.


Exemplo:
```sh
git diff HEAD
```
Isso mostra as mudanças feitas no seu diretório de trabalho que ainda não foram commitadas.

## ```git clone --branch --single-branch```
O comando git clone cria uma cópia de um repositório remoto no seu sistema local. A opção --branch permite clonar uma branch específica, e --single-branch garante que apenas essa branch será clonada.

Exemplo:
```sh
git clone https://github.com/seu-usuario/seu-repositorio.git --branch develop --single-branch
Isso clona apenas a branch develop do repositório remoto.
```

## ```git stash``` e ```git stash list```
O comando git stash salva temporariamente as mudanças não commitadas no seu diretório de trabalho para que você possa trabalhar em outra coisa e depois restaurar essas mudanças. O comando git stash list mostra todas as stashes salvas.

Exemplo:
```
# Salva as mudanças não commitadas
git stash

# Lista todas as stashes salvas
git stash list
```
Isso salva as mudanças não commitadas e depois lista todas as stashes que foram salvas.