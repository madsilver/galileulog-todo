# galileulog-todo
Aplicação no padrão MVC utilizando symphony, doctrine e mysql

## Demo
http://galileutodo.herokuapp.com/

## Composer (dependências)
composer install

## Estrutura da base de dados
CREATE TABLE `todo` ( 
`id` int(11) NOT NULL AUTO_INCREMENT, 
`name` varchar(255) DEFAULT NULL, 
`category` varchar(255) DEFAULT NULL, 
`description` varchar(255) DEFAULT NULL, 
`priority` varchar(255) DEFAULT NULL, 
`due_date` datetime DEFAULT NULL, 
`create_date` datetime DEFAULT NULL, 
PRIMARY KEY (`id`) );
