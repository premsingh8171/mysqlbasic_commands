# MySQL Commands

create databases

USE springdb

CREATE TABLE Emp99(
    id int,
    name varchar(255),
    salary varchar(255),
    designation varchar(255),
);

ALTER TABLE Emp99
ADD PRIMARY KEY (ID);

ALTER TABLE Emp99 MODIFY id int NOT NULL AUTO_INCREMENT;


DELETE FROM Emp99;
