# galileulog-todo
Todo list utilizando symphony php

## Composer
### Utilize o comando abaixo para instalar as dependências do projeto
composer install

## Estrutura da base ded dados

CREATE DATABASE "galileu";
CREATE TABLE "todo" (
  "id" int(11) NOT NULL AUTO_INCREMENT,
  "name" varchar(255) DEFAULT NULL,
  "category" varchar(255) DEFAULT NULL,
  "description" varchar(255) DEFAULT NULL,
  "priority" varchar(255) DEFAULT NULL,
  "due_date" datetime DEFAULT NULL,
  "create_date" datetime DEFAULT NULL,
  PRIMARY KEY ("id")
);
