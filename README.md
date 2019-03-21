# compose-test
Exemplo da documentação do Docker Compose que cria uma aplicação em Flask.  


## Executando a aplicação  

Para executar use o comando:  

```sh
docker-compose up
```  
Ou se quiser mandar os containers para executar em segundo plano:  

```sh
docker-compose up -d
```  

Ou para reconstruir e executar a imagem depois de uma alteração:  

```sh
docker-compose up --build
```  

A aplicação executará em um navegador na url: `http://0.0.0.0:5000/` ou `localhost:5000/`.  

## Finalizando a aplicação  

Para finalizar use `CTRL + C` quando estiver no mesmo terminal ou quando estiver em um segundo terminal use: 

```sh
docker-compose down
```
