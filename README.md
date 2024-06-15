La base de datos en mysql es:

CREATE SCHEMA `crudaapp` ;

CREATE TABLE `user` (
  `id` int NOT NULL,
  `fname` varchar(45) DEFAULT NULL,
  `lname` varchar(45) DEFAULT NULL,
  `email` varchar(45) DEFAULT NULL,
  PRIMARY KEY (`id`)
);
