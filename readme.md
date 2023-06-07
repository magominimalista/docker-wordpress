## Instruções

### Cerifique-se que a porta 3306 está livre
1. Pressione as teclas "Win + R" para abrir a caixa de diálogo "Executar".
2. Digite "services.msc" e pressione "Enter" para abrir o "Console de Serviços".
3. Na janela "Console de Serviços", role para baixo e encontre o serviço chamado "MySQL" ou "MySQL Server".
4. Clique com o botão direito no serviço e selecione "Parar" para interromper temporariamente a execução do serviço.
5. Após parar o serviço, ele não estará mais ouvindo na porta 3306.

### Execute
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