# Wordpress-docker-mysql

Configuração do ambiente
 * Wordpress
 * Mysql
 * PhpMyAdmin

Para iniciar os Containers...

Abra o terminal e navegue até o diretório onde você salvou o arquivo docker-compose.yml. 
Em seguida, execute o seguinte comando para iniciar os containers:

no bash
docker-compose up -d

Isso iniciará os serviços definidos no arquivo docker-compose.yml. 
O WordPress estará disponível em http://localhost:8000, 
e o phpMyAdmin estará disponível em http://localhost:8080.

Configurar o WordPress

* Acesse http://localhost:8000 no seu navegador.
* Siga as instruções para configurar o WordPress, fornecendo as informações necessárias.
* Quando solicitado, insira as informações do banco de dados:
* Nome do banco de dados: wordpress
* Nome do usuário: wordpress
* Usuário e senha do PhpMyAdmin: wordpress
  
Agora você tem um ambiente Docker com WordPress, MySQL e phpMyAdmin configurados! 
Lembre-se de que este é um ambiente de desenvolvimento e não é recomendado para uso em produção. 
Certifique-se de proteger suas senhas adequadamente em um ambiente de produção.

--------------
Caso estiver no Mac, alterar a imagem do mysql no arquivo docker-compose.yml para image: arm64v8/mysql

