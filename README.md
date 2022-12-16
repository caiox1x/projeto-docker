# Projeto conversão de temperatura by Caio

### Sobre o projeto
O projeto conversão de temperatura é um projeto desenvolvido em NodeJS. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando NodeJS.

### Observações do projeto
A aplicação é exposta usando a porta 8080

### Objetivo do projeto
O projeto tem como objetivo ser a minha aplicação em um container, estou utilizando como base o curso devops pro, e estou no modulo de docker

OBS: o código em JS não é meu

### Como rodar o projeto 
Já tendo instalado o docker na sua máquina, rode o seguinte comando 

docker image build -t conversao-temperatura .

docker container run -d -p 8080:8080 conversao-temperatura

dessa forma na primeira linha será criado uma nova imagem a partir do dockerfile do projeto e na segunda linha será criado um container da aplicação usando como base a imagem que criamos.
