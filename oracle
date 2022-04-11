------------------------------------------------------------------------------------------------
create table for airline reservation system
------------------------------------------------------------------------------------------------------------------
create table fare1 (id number(19), fare varchar2(255), flight_date varchar2(255), flight_number varchar2(255));

insert into fare1 values(101,'1000','01-jun-2022','10000');
insert into fare1 values(102,'1500','03-jun-2022','10101');
insert into fare1 values(103,'2000','07-jun-2022','12211');
insert into fare1 values(104,'2500','11-jun-2022','13122');

select * from fare1;
-------------------------------------------------------------------------------------------------------------------
create table flight1 (id number(19) , destination varchar2(255), flight_date varchar2(255), 
flight_number varchar2(255), origin varchar2(255));

insert into flight1 values(200,'gorakhpur','1-May-2022','55555','patna');
insert into flight1 values(201,'patna','3-may-2022','55556','Delhi');
insert into flight1 values(202,'Delhi','5-may-2022','55557','Mumbai'); 
insert into flight1 values(203,'Mumbai''7-may-2022','55558','pune');

select * from flight1;
-----------------------------------------------------------------------------------------------------------------------
create table booking_record1 (id number(19) primary key, booking_date timestamp, destination varchar2(255), price varchar2(255), flight_date varchar2(255), flight_number varchar2(255), origin varchar2(255), status varchar2(255));

insert into booking_record1 values(201,'10-april-2022','patna','10000','13-april-2022','111112','mumbai','active');
insert into booking_record1 values(202,'15-april-2022','mumbai','12000','20-april-2022','123111','pune','waiting');
insert into booking_record1 values(203,'25-april-2022','pune','14000','30-april-2022','132212','banglore','confirm');
insert into booking_record1 values(204,'1-may-2022','Bangalore','5000','10-may-2022','142311','chennai','confirm'); 

select * from booking_record1;
-----------------------------------------------------------------------------------------------------------------------------
create table inventory1 (id number(19) , available number(10) , flight_date varchar2(255), flight_number varchar2(255));

insert into inventory1 values(300,201,'02-july-2022',10230);
insert into inventory1 values(301,202,'02-july-2022',10240);
insert into inventory1 values(302,203,'02-july-2022',10025);
insert into inventory1 values(303,204,'02-july-2022',10260);

select*from inventory1;
-------------------------------------------------------------------------------------------------------------------------------
create table passenger1 (id number(19), first_name varchar2(255), gender varchar2(255), last_name varchar2(255), booking_id number(19));

insert into passenger1 values(101,'ram','male','shri',1008);
insert into passenger1 values(102,'shayam','male','shri',1008);
insert into passenger1 values(103,'ganesh','male','shri',1008);
insert into passenger1 values(104,'vishnu','male','shri',1008);

select*from passenger1;

-------------------------------------------------------------------
