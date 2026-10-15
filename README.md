# Docker Compose com MongoDB e Express

Docker Componse com as imagens do MongoDB e Express para uso em outras aplicações.

## Sobre o projeto
 - Utiliza o **Docker Compose** para definir e gerenciar o serviço do banco de dados e o Express. 
 - Utiliza o **MongoDB 9.0.4** como banco de dados da aplicação. 
 - A ferramenta **Express 1.0.2** vem configurada no arquivo compose.yml.
 
## Docker
 - Utilizar o terminal do Windows Powershel em modo administrador.

### Para criar os conteiner e os serviços
 - ```docker compose up -d```

### Para verificar o serviço em execução
 - ```docker compose ps```

### Parar o serviço
 - ```docker compose down -v```

### Remover a imagem
 - ```docker compose down --rmi all```

### URL para Clientes MongoDB
 - ```mongodb://root:root@localhost:27017/?authSource=admin```

### Hostname MongoDB
 - mongo

### Usuário MongoDB
 - root/root

## URL o Express Gerenciador do MongoDB:
 - ```http://localhost:8081/```

### Usuário Express
 - admin/admin

## Arquivos
- compose.yml - Arquivo de configuração da composição do Docker.

