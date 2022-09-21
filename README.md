# Passo a passo para realização da atividade:

git clone https://github.com/marcellass/AtividadeContinua2_Framework_Fullstack

docker-compose up -d

  
# Dentro da imagem:
 
mysql -uroot -p

create schema produto;

use produto;

CREATE TABLE produtos_unidade ( user_id BIGINT NOT NULL AUTO_INCREMENT, user_name VARCHAR(45) NULL, user_preco VARCHAR(45) NULL, user_categoria VARCHAR(45) NULL, PRIMARY KEY (user_id));
