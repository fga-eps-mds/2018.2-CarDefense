# Integra -  CarDefense
![CI status](https://img.shields.io/badge/build-passing-brightgreen.svg)
![Django Rest](https://img.shields.io/badge/django--rest--framework-3.7.7-orange.svg)
![Python](https://img.shields.io/badge/python-3.6-ff69b4.svg)
![Docs](https://img.shields.io/badge/docs-Github%20Pages-blue.svg)

* [Documentação do Integra - CarDefense](https://fga-eps-mds.github.io/2018.2-CarDefense/docs/)

* [Documentação do App Integra](https://fga-eps-mds.github.io/2018.2-FGAPP-FrontEnd)


CarDefense é um módulo do aplicativo Integra, onde é feito o monitoramento de carros dentro do ambiente da UnB - Universidade de Brasília.

## Instalação 

### Requisitos 
Para instalação do projeto você deve ter instalado:
* Docker
* Docker Compose

### Como instalar

1 - Clone o repositório

2 - Entre na pasta do projeto

3 - Rode o comando:
```
sudo docker-compose up
```

4 - Acesse localhost:8000


Para acessar o container da aplicação use o seguinte comando:
```
sudo docker exec -it 20182cardefense_web_1 bash
```

Para ver todos os containers rodando na sua máguina use o seguinte comando:

```
sudo docker ps
```

## Nossos microsserviços 
* [CarDefense Profile](https://github.com/CarDefense/CarDefense_Profile)
* [CarDefense Notification](https://github.com/CarDefense/CarDefense_Notification)
* [CarDefense Cars](https://github.com/CarDefense/CarDefense_Cars)
* [CarDefense Gamification](https://github.com/CarDefense/CarDefense_Gamification)
