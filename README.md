# SQL_Assignment8
## 1-test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.  

**CREATE TABLE** employee (  
id **SERIAL PRIMARY KEY**,  
name **VARCHAR(50) not NULL**,  
birthday **DATE**,  
email **VARCHAR(100)**  
)  

## 2-Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.  

insert into employee (name, birthday, email) values ('Kean Esterbrook', '2021-12-23', 'kesterbrook0@youku.com');
insert into employee (name, birthday, email) values ('Gayla Harman', '2021-12-22', 'gharman1@typepad.com');
insert into employee (name, birthday, email) values ('Cammie Rivel', '2021-04-04', 'crivel2@bravesites.com');
insert into employee (name, birthday, email) values ('Mira Crossby', '2022-02-21', 'mcrossby3@walmart.com');
insert into employee (name, birthday, email) values ('Kasey Twigge', '2021-11-03', 'ktwigge4@hostgator.com');
insert into employee (name, birthday, email) values ('Kristan MacQuist', '2021-03-17', 'kmacquist5@umn.edu');
insert into employee (name, birthday, email) values ('Vasili MacCaig', '2022-01-09', 'vmaccaig6@home.pl');
insert into employee (name, birthday, email) values ('Kalila Roalfe', '2021-08-14', 'kroalfe7@oracle.com');
insert into employee (name, birthday, email) values ('Sonni Wiltshire', '2021-08-24', 'swiltshire8@about.me');
insert into employee (name, birthday, email) values ('Glendon Teissier', '2021-07-31', 'gteissier9@sbwire.com');
insert into employee (name, birthday, email) values ('Ciel Slany', '2021-07-17', 'cslanya@blinklist.com');
insert into employee (name, birthday, email) values ('Fayre Elcott', '2022-01-18', 'felcottb@sourceforge.net');
insert into employee (name, birthday, email) values ('Katharine Stanluck', '2022-01-24', 'kstanluckc@sina.com.cn');
insert into employee (name, birthday, email) values ('Shane Stuchbury', '2021-09-02', 'sstuchburyd@networkadvertising.org');
insert into employee (name, birthday, email) values ('Karlotte Wigzell', '2021-12-05', 'kwigzelle@meetup.com');
insert into employee (name, birthday, email) values ('Cymbre Brayshay', '2021-12-11', 'cbrayshayf@jigsy.com');
insert into employee (name, birthday, email) values ('Kristin Poor', '2021-04-09', 'kpoorg@google.com');
insert into employee (name, birthday, email) values ('Edyth Tracey', '2021-10-01', 'etraceyh@pinterest.com');
insert into employee (name, birthday, email) values ('Bess Mowsdale', '2021-10-15', 'bmowsdalei@google.it');
insert into employee (name, birthday, email) values ('Brittni Staneland', '2021-05-13', 'bstanelandj@hhs.gov');
insert into employee (name, birthday, email) values ('Marcelle Creane', '2022-03-04', 'mcreanek@craigslist.org');
insert into employee (name, birthday, email) values ('Alleen Crews', '2021-12-22', 'acrewsl@npr.org');
insert into employee (name, birthday, email) values ('Kathlin Rennard', '2021-04-09', 'krennardm@cdbaby.com');
insert into employee (name, birthday, email) values ('Verla Berndsen', '2021-10-04', 'vberndsenn@soundcloud.com');
insert into employee (name, birthday, email) values ('Jocelyne Lethieulier', '2021-11-16', 'jlethieuliero@sun.com');
insert into employee (name, birthday, email) values ('Eran Tyres', '2021-06-20', 'etyresp@prweb.com');
insert into employee (name, birthday, email) values ('Sansone Chaize', '2022-01-18', 'schaizeq@google.com.au');
insert into employee (name, birthday, email) values ('Alika Gregorin', '2021-08-09', 'agregorinr@prnewswire.com');
insert into employee (name, birthday, email) values ('Brnaby Saunton', '2021-11-13', 'bsauntons@globo.com');
insert into employee (name, birthday, email) values ('Rutherford Klimpke', '2021-10-30', 'rklimpket@sina.com.cn');
insert into employee (name, birthday, email) values ('Janette Ornils', '2022-02-15', 'jornilsu@china.com.cn');
insert into employee (name, birthday, email) values ('Kimbra Wile', '2021-09-06', 'kwilev@cnbc.com');
insert into employee (name, birthday, email) values ('Waylan Spires', '2021-12-11', 'wspiresw@ow.ly');
insert into employee (name, birthday, email) values ('Casey Pawsey', '2021-04-11', 'cpawseyx@google.com');
insert into employee (name, birthday, email) values ('Leelah Roseblade', '2021-06-11', 'lrosebladey@opensource.org');
insert into employee (name, birthday, email) values ('Stephie Notman', '2022-01-29', 'snotmanz@ucoz.com');
insert into employee (name, birthday, email) values ('Dawna Rodenhurst', '2021-11-05', 'drodenhurst10@miibeian.gov.cn');
insert into employee (name, birthday, email) values ('Appolonia Blyden', '2022-03-02', 'ablyden11@cargocollective.com');
insert into employee (name, birthday, email) values ('Merola Hyde', '2022-01-22', 'mhyde12@diigo.com');
insert into employee (name, birthday, email) values ('Isidora Dadds', '2021-09-10', 'idadds13@state.tx.us');
insert into employee (name, birthday, email) values ('Darnall Bosson', '2022-01-22', 'dbosson14@latimes.com');
insert into employee (name, birthday, email) values ('Tuesday Whelpton', '2021-04-18', 'twhelpton15@baidu.com');
insert into employee (name, birthday, email) values ('Farica Tukely', '2021-04-15', 'ftukely16@mashable.com');
insert into employee (name, birthday, email) values ('Shir Kinworthy', '2021-11-21', 'skinworthy17@meetup.com');
insert into employee (name, birthday, email) values ('Tabina Nipper', '2021-11-15', 'tnipper18@yolasite.com');
insert into employee (name, birthday, email) values ('Carlina Whithalgh', '2022-03-05', 'cwhithalgh19@squarespace.com');
insert into employee (name, birthday, email) values ('Meaghan Lequeux', '2021-11-14', 'mlequeux1a@bloglovin.com');
insert into employee (name, birthday, email) values ('Arturo Kneal', '2021-05-25', 'akneal1b@friendfeed.com');
insert into employee (name, birthday, email) values ('Annecorinne Tchir', '2021-03-11', 'atchir1c@google.ru');
insert into employee (name, birthday, email) values ('Brynn Sumers', '2021-07-01', 'bsumers1d@ucoz.ru');  

## 3-Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.  

**UPDATE** employee  
**SET** name = 'Anna Marie',  
**birthday** = 2021-03-02,  
**WHERE** id = 50;  

**UPDATE** employee  
**SET** email = 'abcdefg@gmail.com',  
**WHERE** id = 49;  

**UPDATE** employee  
**SET** name = 'Ahmet Mehmet',  
**WHERE** id= 23;  

**UPDATE** employee  
**SET** birthday = 2021-09-28,  
**WHERE** id = 13;

**UPDATE** employee  
**SET** name = 'Arturo Romano'  
**WHERE** id = 41;


## 4- Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.  
**DELETE FROM** employee  
**WHERE** id = 14  
**RETURNING** *;  
