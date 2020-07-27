# Backend tela de login, cadastro e recuperar/trocar senha

repositório com codigo criado para a funcionalidade de cadastrar usuarios, realizar login e recuperar a senha do usuario

## Para testa 

rode yarn install para instalar os mudulos,
configure o arquivo ormconfig com seu dados do banco de dados,
configure um valor para ser usando com secret no jwt,
crie uma conta no mailtrap para testa o recebimento de email,
configure a parte do codigo(process.env,MAILTRAP_USER...) onde se envia o email com seu dados do mailtrap

se vc for rodar em desenvolvimento mudar o arquivo ormconfig
  onde tem dist coloque src e acrescente synchronize: true;

## Build

usei o babel para gerar a build de produção,
para gerar o build rode yarn build que sera executado um script do babel presente no arquivo package.json

