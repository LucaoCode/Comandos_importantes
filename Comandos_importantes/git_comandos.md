# Configurações do git

**-> Configura o github para aparecer o meu nome quando for enviar o codigo**
```shell
git config --global user.name "Lucas"
```
**-> para verificar os repositorios do meu email**
```shell
git config --global user.email "lucas.lima@ucl.br" 
```
-> para verificar os repositorios do meu email


## Comando Git

**-> clona o repositorio na minha maquina**
```shell
git clone (link do repositorio) 
```

**-> Cria e troca para uma nova branch chamada feature/gerenciador-de-tarefas**
```shell
git checkout -b feature/gerenciador-de-tarefas
```
**-> verifica o status do git**
```shell
git status 
```
**-> adiciona o arquivo git ignore e envia uma mensagem para o repositorio**
```shell
git add .gitignore && git commit -m "adiciona arquivo gitignore" 
```
**-> envia para o repositorio feature/gerenciador de tarefas**
```shell
git push origin feature/gerenciador-de-tarefas
```