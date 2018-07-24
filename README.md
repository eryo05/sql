# sql


CREATE DATABASE IF NOT EXISTS languages
CREATE DATABASE IF NOT EXISTS webDevelopment CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci
CREATE DATABASE IF NOT EXISTS frameworks CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci
CREATE DATABASE IF NOT EXISTS languages CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci
DROP DATABASE languages
DROP DATABASE IF EXISTS frameworks
DROP DATABASE IF EXISTS languages
CREATE TABLE languages ( id INT PRIMARY KEY NOT NULL, language varchar(100) )
CREATE TABLE tools ( id INT AUTO_INCREMENT PRIMARY KEY, tool VARCHAR(40) )
CREATE TABLE webDevelopment.frameworks ( id INT PRIMARY KEY AUTO_INCREMENT, name VARCHAR(40) )
CREATE TABLE webDevelopment.librairies ( id INT PRIMARY KEY AUTO_INCREMENT, librairy VARCHAR(40) )
CREATE TABLE webDevelopment.ide ( id INT PRIMARY KEY AUTO_INCREMENT, ideName VARCHAR(40) )
CREATE TABLE IF NOT EXISTS webDevelopment.frameworks ( id INT PRIMARY KEY AUTO_INCREMENT, name VARCHAR(40) )
DROP TABLE IF EXISTS webDevelopment.tools
DROP TABLE IF EXISTS webDevelopment.librairies
DROP TABLE IF EXISTS webDevelopment.ide
CREATE DATABASE codex
CREATE TABLE codex.clients ( id INT PRIMARY KEY AUTO_INCREMENT, lastName VARCHAR(40), firstName VARCHAR(40), birthDate DATE, adress VARCHAR(40), firstPhoneNumber INT, secondPhoneNumber INT, mail VARCHAR(40) )
​
