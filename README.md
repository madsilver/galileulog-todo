# galileulog-todo
Todo list utilizando symphony php

## Composer (dependências)
composer install

## Estrutura da base de dados

CREATE DATABASE `galileu`;
CREATE TABLE `todo` ( 
`id` int(11) NOT NULL AUTO_INCREMENT, 
`name` varchar(255) DEFAULT NULL, 
`category` varchar(255) DEFAULT NULL, 
`description` varchar(255) DEFAULT NULL, 
`priority` varchar(255) DEFAULT NULL, 
`due_date` datetime DEFAULT NULL, 
`create_date` datetime DEFAULT NULL, 
PRIMARY KEY (`id`) );
