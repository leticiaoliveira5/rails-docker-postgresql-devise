# Descrição

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam eu risus varius eros vulputate placerat ac id nisl. Fusce ac ultricies sapien. Nunc auctor, libero eu varius luctus, velit justo sodales turpis, sit amet dictum massa tellus ac justo. Proin consectetur, purus et euismod accumsan, eros velit aliquam arcu, et dapibus neque quam at leo. 

## Principais ferramentas
- Ruby (v3.1.3)
- Rails (v7.0.4)
- Devise (v4.8.1)
- PostgreSQL
- GitHub Actions

## Subir o projeto

Para testar, a melhor opção é usar o Docker. Pra isso, é necessário ter instalado na máquina o docker e docker compose.

Agora execute os comandos no terminal:

```
cd rails-docker-postgresql-devise
```

```
docker-compose build
docker-compose up
```

Abra um outro terminal execute:

```
docker compose exec rake db:setup
```

Acesse a aplicação em http://localhost:3000/

## Login

Para utilizar o app, é preciso fazer login. É possível entrar com o usuário criado no `seed` ou criar um novo clicando em Sign Up.

Usuário padrão:

- E-mail: 
```
admin@app.net
```
- Senha:
```
123456
```
