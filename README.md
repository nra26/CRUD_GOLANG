Hello! if you want to try out the program you can do go run main.go 
on terminal where the main.go is. 

for database you can make it with xampp mysql 
for the code in mysql

CREATE DATABASE Database_Universitas;

USE Database_Universitas;

CREATE TABLE mahasiswa (
id int(6) unsigned NOT NULL AUTO_INCREMENT PRIMARY KEY,
npm CHAR(8) NOT NULL,
nama VARCHAR(30) NOT NULL,
kelas CHAR(5) NOT NULL,
profile VARCHAR(30) NOT NULL);

INSERT INTO mahasiswa VALUES 
("","362849","yourname","yourclass","gambar1.jpg");

and make sure your mysql port is the same as the port in main.go file
line 56

thats all<3
