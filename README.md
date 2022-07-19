# sql8
patika.dev linkim: https://app.patika.dev/cmilakonur <br />

1- test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım. <br />
drop table if exists employee; <br />
create table employee ( <br />
	id int, <br />
	name varchar(50), <br />
	birthday date, <br />
	email varchar(100) <br />
); <br />

2- Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim. <br />
insert into employee (id, name, birthday, email) values (1, 'Adele', '1971-02-08', 'ageraldini0@ucla.edu'); <br />
insert into employee (id, name, birthday, email) values (2, 'Stevena', '2008-05-16', 'skobera1@ovh.net'); <br />
insert into employee (id, name, birthday, email) values (3, 'Ferdinand', '2007-01-06', 'fchetham2@cpanel.net'); <br />
insert into employee (id, name, birthday, email) values (4, 'Kerrie', '1998-12-14', 'klovelace3@youtu.be'); <br />
insert into employee (id, name, birthday, email) values (5, 'Ladonna', '1975-12-19', 'lbeelby4@sitemeter.com'); <br />
insert into employee (id, name, birthday, email) values (6, 'Waylin', '2000-02-27', 'wtitterell5@surveymonkey.com'); <br />
insert into employee (id, name, birthday, email) values (7, 'Camila', '1956-04-26', 'ccoyne6@php.net'); <br />
insert into employee (id, name, birthday, email) values (8, 'Lynelle', '1968-05-13', 'lchristene7@fotki.com'); <br />
insert into employee (id, name, birthday, email) values (9, 'Othelia', '1952-12-25', 'okubicek8@hatena.ne.jp'); <br />
insert into employee (id, name, birthday, email) values (10, 'Sara', '1957-01-14', 'srenoden9@sina.com.cn'); <br />
insert into employee (id, name, birthday, email) values (11, 'Drusi', '2009-09-07', 'dpinckneya@apache.org'); <br />
insert into employee (id, name, birthday, email) values (12, 'Eleanore', '1968-06-13', 'ebisterb@skype.com'); <br />
insert into employee (id, name, birthday, email) values (13, 'Gerhardine', '1988-08-26', 'gslorac@symantec.com'); <br />
insert into employee (id, name, birthday, email) values (14, 'Tull', '2013-06-16', 'toertzend@blogspot.com'); <br />
insert into employee (id, name, birthday, email) values (15, 'Hugh', '1989-08-28', 'hhardwickee@printfriendly.com'); <br />
insert into employee (id, name, birthday, email) values (16, 'Marven', '1957-03-03', 'mschottf@themeforest.net'); <br />
insert into employee (id, name, birthday, email) values (17, 'Chico', '1962-10-18', 'cbaumaierg@people.com.cn'); <br />
insert into employee (id, name, birthday, email) values (18, 'Tanhya', '1983-09-08', 'tmcbeithh@msn.com'); <br />
insert into employee (id, name, birthday, email) values (19, 'Penelope', '2014-03-28', 'pormei@walmart.com'); <br />
insert into employee (id, name, birthday, email) values (20, 'Ramsey', '2003-12-27', 'rbernettej@usnews.com'); <br />
insert into employee (id, name, birthday, email) values (21, 'Rozamond', '1996-09-25', 'rscrowstonk@geocities.com'); <br />
insert into employee (id, name, birthday, email) values (22, 'Clemens', '1978-02-03', 'cadiel@1688.com'); <br />
insert into employee (id, name, birthday, email) values (23, 'Penelope', '1980-03-12', 'pregorzm@intel.com'); <br />
insert into employee (id, name, birthday, email) values (24, 'Rozelle', '1999-08-07', 'rrainn@pinterest.com'); <br />
insert into employee (id, name, birthday, email) values (25, 'Sallyann', '1966-01-16', 'ssheepyo@foxnews.com'); <br />
insert into employee (id, name, birthday, email) values (26, 'Ynes', '1974-10-12', 'yjohnp@jimdo.com'); <br />
insert into employee (id, name, birthday, email) values (27, 'Ginevra', '2007-11-20', 'gcastanieq@mtv.com'); <br />
insert into employee (id, name, birthday, email) values (28, 'Marcos', '1955-06-03', 'mduggonr@gravatar.com'); <br />
insert into employee (id, name, birthday, email) values (29, 'Karena', '1982-06-04', 'kchurchyards@issuu.com'); <br />
insert into employee (id, name, birthday, email) values (30, 'Emmaline', '1958-02-13', 'eseniort@google.com'); <br />
insert into employee (id, name, birthday, email) values (31, 'Aguie', '2014-11-27', 'abattyeu@sitemeter.com'); <br />
insert into employee (id, name, birthday, email) values (32, 'Danya', '1952-08-26', 'ddouchv@csmonitor.com'); <br />
insert into employee (id, name, birthday, email) values (33, 'Vinita', '1966-02-21', 'vsantryw@nbcnews.com'); <br />
insert into employee (id, name, birthday, email) values (34, 'Merilyn', '2003-06-27', 'mstuddx@princeton.edu'); <br />
insert into employee (id, name, birthday, email) values (35, 'Xena', '2006-09-15', 'xcurtisy@deviantart.com'); <br />
insert into employee (id, name, birthday, email) values (36, 'Jamima', '1993-02-18', 'jdarmodyz@senate.gov'); <br />
insert into employee (id, name, birthday, email) values (37, 'Benyamin', '1997-08-25', 'bindgs10@amazon.com'); <br />
insert into employee (id, name, birthday, email) values (38, 'Philippine', '1957-08-09', 'pmccurry11@booking.com'); <br />
insert into employee (id, name, birthday, email) values (39, 'Yoshiko', '1950-08-01', 'yfavelle12@rakuten.co.jp'); <br />
insert into employee (id, name, birthday, email) values (40, 'Georas', '1986-01-13', 'gtilt13@sakura.ne.jp'); <br />
insert into employee (id, name, birthday, email) values (41, 'Reginauld', '1969-12-27', 'rmatteucci14@uol.com.br'); <br />
insert into employee (id, name, birthday, email) values (42, 'Sigfried', '2003-01-29', 'sminshull15@g.co'); <br />
insert into employee (id, name, birthday, email) values (43, 'Griselda', '1969-10-13', 'geddicott16@unc.edu'); <br />
insert into employee (id, name, birthday, email) values (44, 'Jaquenetta', '2009-02-06', 'jballister17@sun.com'); <br />
insert into employee (id, name, birthday, email) values (45, 'Saree', '2009-04-06', 'scurrall18@geocities.jp'); <br />
insert into employee (id, name, birthday, email) values (46, 'Kimberlee', '1974-05-27', 'kpiesold19@usatoday.com'); <br />
insert into employee (id, name, birthday, email) values (47, 'Ed', '1963-04-26', 'epieterick1a@com.com'); <br />
insert into employee (id, name, birthday, email) values (48, 'Harris', '1980-02-25', 'hhendrik1b@wordpress.com'); <br />
insert into employee (id, name, birthday, email) values (49, 'Mauricio', '1970-01-01', 'mfairbanks1c@wordpress.org'); <br />
insert into employee (id, name, birthday, email) values (50, 'Celina', '1998-04-27', 'cmatuska1d@mayoclinic.com'); <br />

3- Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım. <br />
update employee <br />
set name='Eddard', <br />
	birthday='1972-07-23', <br />
	email='eddard@gmail.com' <br />
where id=1; <br />

update employee <br />
set id=53, <br />
	birthday='2022-01-04', <br />
	email='skode@gm.com' <br />
where name='Stevena'; <br />

update employee <br />
set id=103, <br />
	name='Kaan', <br />
	email='kaan.senel@edu' <br />
where birthday='2007-01-06'; <br />

update employee <br />
set id=2, <br />
	name='Ahmet', <br />
	birthday='2000-12-21' <br />
where email='ccoyne6@php.net'; <br />

update employee <br />
set name='Kerrigan', <br />
	birthday='1999-04-21', <br />
	email='kerrigan@youtube.com' <br />
where id=4; <br />

4- Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım. <br />
delete from employee where id=53; <br />
delete from employee where name='Saree'; <br />
delete from employee where birthday='2003-06-27'; <br />
delete from employee where email='cadiel@1688.com'; <br />
delete from employee where id=14; <br />
