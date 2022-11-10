# Projeto conversão de temperatura

### Sobre o projeto
O projeto conversão de temperatura é um projeto desenvolvido em NodeJS. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando NodeJS.

### Observações do projeto
A aplicação é exposta usando a porta 8080

### Observação do build
Ir para a pasta src, e então executar o docker build para geração da imagem, e então alterar na pasta k8s/deployment.yaml

### Observação do inicio do cluster
Executar kubectl apply -f k8s/

# Project temperature converter

### About the project
The project temperature converter is a project developed in NodeJS. The project goal is to be a example to environment creation with containers using NodeJS

### Project observation
The application runs using PORT 80

### Build Observation
Go to src folder, then execute docker build to generate the image, then changes the image name in the file deployment.yaml in k8s folder

### Cluster initialize Observation
Execute kubectl apply -f k8s/