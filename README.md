# site-web
site web desenvolvido com Laravel 5 um blog de nóticias .(teste).Com área Administrativa.(PHP e MySql).

Laravel 5.2
Instalação

Vagrant
Apenas clonar este repositório e executar vagrant up . Uma vez que o script for concluído, deverá ser instalado e funcionando!

Visite localhost http://localhost:4567 para ver o website

A phpMyAdmin está disponível em http://localhost:4568

Username = root

Password = 

Clássico

git clone este repo
run instalar compositor
na raiz, criar .env arquivo e insira as seguintes linhas
APP_ENV = local 
APP_DEBUG = true 
APP_KEY = 

DB_HOST = localhost 
DB_DATABASE = larablog 
DB_USERNAME = root 
DB_PASSWORD =

1.executar chave artesão php: gerar
2.Editar informação banco de dados no arquivo .env
3.Criar o banco de dados e executar php artisan migrate
4.executar php artisan db:seed
5.executar php artisan serve e visite http://localhost:8000/

=====================================================================
Arquivos que usei para SEO

/* slug é um campo que nos permite usar URL'S amigavéis usando as boas práticas de SEO. 
Para que o Navegador de internet possa identificar de uma forma mais légivel */
/* Com isso tem um posicionamento melhor nos buscadores do Google,Bing Microsoft e muitos outros na Internet
facilitando os Posts do Blog serem encontrados com mais rapidez nas pesquisas. */

slug escreve automaticamente quando é preenchido o campo título.

/* Logo nesse site encontra-se um pacote de slug cviebrock / eloquente-Sluggable: https://packagist.org/ */

/* A instalação do pacotes do Composer usando o git Bash usa-se o código: composer require cviebrock/eloquent-sluggable:^4.0.2 */
