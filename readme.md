## exemplo de proxy reverso

<img src="https://webapplicationconsultant.com/wp-content/uploads/reverseproxy.png" alt="proxy_reverso" style="height: 250px; width:500px;"/>
<a href="https://rockcontent.com/br/blog/nginx/" target="_blank"><br>Clique aqui para ver a imagem original </a>

### Usando 
- Docker-compose 
- Nginx
##### Obs: imagens do docker-compose estão publicas no meu dockerhub

## Rodando o ambiente 

##### para iniciar o ambiente
```{bash}
docker-compose up --build
acesse: http://localhost/   #use f5 para alterar entre requisições dos servidores web01, web02, web03
```

##### para finalizar
```{bash}
docker-compose down
```

# 



