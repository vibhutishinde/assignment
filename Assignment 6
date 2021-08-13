create table country (id int auto_increment not null,name varchar(256)not null,primary key(id)); insert into country (name) values ('India'); insert into country (name) values ('USA'); insert into country (name) values ('Japan');

create table genre (id int auto_increment not null,name varchar(256)not null,primary key(id)); insert into genre (name) values ('Action');insert into genre (name) values ('Drama'); insert into genre (name) values ('Horror');

create table name(id int auto_increment not null,name varchar(256)not null, primary key(id)); insert into name (name) values ('Hundred');insert into name (name) values ('Riverdale');insert into name (name) values ('Dark');


create table director(id int auto_increment not null,name varchar(256)not null, primary key(id)); insert into director (name) values ('Jason Rothenberg');insert into director (name) values ('Jason Moore');insert into director (name) values ('Baran bo Odar');

create table series_details(id int auto_increment not null, name int not null, director int not null, genre int not null, country int not null, status varchar(256) not null, yor int, yoe int, primary key(id)); 

create table series_details(id int auto_increment not null, name int not null, director int not null, genre int not null, country int not null, status varchar(256) not null, yor int, yoe int, primary key(id)); 
insert into series_details(name,director,genre,country,status,yor) values(1,1,2,2,'ongoing',2013); insert into series_details(name,director,genre,country,status,yor,yoe) values(2,2,1,3,'End',2003,2006);insert into series_details(name,director,genre,country,status,yor,yoe) values(6,6,4,4,'End',2016,2020);

select series_details.id as id,name.name as name,director.name as director,genre.name as genre,country.name as country,series_details.status as status,series_details.yor as yor, series_details.yoe as yoe from series_details join name on series_details.name=name.id join director on series_details.director=director.id join genre on series_details.genre=genre.id join country on series_details.country=country.id;

select series_details.id as id,name.name as name,director.name as director,genre.name as genre,country.name as country,series_details.status as status,series_details.yor as yor, series_details.yoe as yoe from series_details join name on series_details.name=name.id join director on series_details.director=director.id join genre on series_details.genre=genre.id join country on series_details.country=country.id where country.name='usa' and status='end';

select series_details.id as id,name.name as name,director.name as director,genre.name as genre,country.name as country,series_details.status as status,series_details.yor as yor, series_details.yoe as yoe from series_details join name on series_details.name=name.id join director on series_details.director=director.id join genre on series_details.genre=genre.id join country on series_details.country=country.id where yor>=2010 and yor<=2021;
