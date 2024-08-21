# Enviando e Baixando Alterações do Repositório Local para o Repositório Remoto

## Enviando (PUSH) Alterações do Repositório Local

1. Tenha certeza de que todos os commits foram adicionados e commitados.

2. Crie no seu GitHub, um repositório (caso não tenha) 

3. Digite o comando:
``` 
git remote add origin <endereço https do repositório remoto que você quer enviar>
```
4. Depois EMPURRE/ENVIE (PUSH) os commits do seu repositório local para o repositório remoto.
``` 
git push -u origin main
```

## Baixando (PULL) Alterações do Repositório Remoto

1. Vá até o seu repositório local.
2. Baixe (PULL) os commits para a sua máquina dessa forma: 
``` 
git pull
```