## Instruções

### Execute
docker-compose up -d

### Pause o serviço
docker-compose down

### Abra wp-config.php e acescente
define('WP_HOME','http://127.0.0.1');
define('WP_SITEURL','http://127.0.0.1');

### Suba novamente
docker-compose up -d

### Rotas

#### Rota de instalação
http://127.0.0.1/install

#### Rota principal
http://127.0.0.1

#### PHP MyAdmin
http://127.0.0.1:8080
User: root
Pass: password