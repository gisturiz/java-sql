# java-sql

A student that completes this project shows that they can:
* Query data from a single table
* Query data from multiple tables
* Create a new datadaase using PostgreSQL

# Introduction

Working with SQL

# Instructions

Surf to [SQL Try Editor at W3Schools.com](https://www.w3schools.com/Sql/tryit.asp?filename=trysql_select_top)  
Answer the following data queries. Keep track of the SQL you write by pasting it into this document under its appropriate header below. You will be submitting that through the regular fork, change, pull process.

### **Clicking the `Restore Database` button in the page will repopulate the database with the original data and discard all changes you have made**.

### find all customers that live in London. Returns 6 records.
> This can be done with SELECT and WHERE clauses

Number of Records: 6
CustomerID	CustomerName	ContactName	Address	City	PostalCode	Country
4	Around the Horn	Thomas Hardy	120 Hanover Sq.	London	WA1 1DP	UK
11	B's Beverages	Victoria Ashworth	Fauntleroy Circus	London	EC2 5NT	UK
16	Consolidated Holdings	Elizabeth Brown	Berkeley Gardens 12 Brewery	London	WX1 6LT	UK
19	Eastern Connection	Ann Devon	35 King George	London	WX3 6FW	UK
53	North/South	Simon Crowther	South House 300 Queensbridge	London	SW7 1RZ	UK
72	Seven Seas Imports	Hari Kumar	90 Wadhurst Rd.	London	OX15 4NB	UK

### find all customers with postal code 1010. Returns 3 customers.
> This can be done with SELECT and WHERE clauses

Number of Records: 3
CustomerID	CustomerName	ContactName	Address	City	PostalCode	Country
12	Cactus Comidas para llevar	Patricio Simpson	Cerrito 333	Buenos Aires	1010	Argentina
54	Océano Atlántico Ltda.	Yvonne Moncada	Ing. Gustavo Moncada 8585 Piso 20-A	Buenos Aires	1010	Argentina
64	Rancho grande	Sergio Gutiérrez	Av. del Libertador 900	Buenos Aires	1010	Argentina

### find the phone number for the supplier with the id 11. Should be (010) 9984510.
> This can be done with SELECT and WHERE clauses

Number of Records: 1
SupplierID	SupplierName	ContactName	Address	City	PostalCode	Country	Phone
11	Heli Süßwaren GmbH & Co. KG	Petra Winkler	Tiergartenstraße 5	Berlin	10785	Germany	(010) 9984510

### list orders descending by the order date. The order with date 1997-02-12 should be at the top.
> This can be done with SELECT, WHERE, and ORDER BY clauses

Number of Records: 196
OrderID	CustomerID	EmployeeID	OrderDate	ShipperID
10443	66	8	1997-02-12	1
10442	20	3	1997-02-11	2
10440	71	4	1997-02-10	2
10441	55	3	1997-02-10	2
10439	51	6	1997-02-07	3
10438	79	3	1997-02-06	2
10436	7	3	1997-02-05	2
10437	87	8	1997-02-05	1
10435	16	8	1997-02-04	2
10433	60	3	1997-02-03	3
10434	24	3	1997-02-03	2
10432	75	3	1997-01-31	2
10430	20	4	1997-01-30	1
10431	10	4	1997-01-30	2
10429	37	3	1997-01-29	2
10428	66	7	1997-01-28	1
10426	29	4	1997-01-27	1
10427	59	4	1997-01-27	2
10425	41	6	1997-01-24	2
10423	31	6	1997-01-23	3
10424	51	7	1997-01-23	2
10422	27	2	1997-01-22	1
10420	88	3	1997-01-21	1
10421	61	8	1997-01-21	1
10419	68	4	1997-01-20	2
10418	63	4	1997-01-17	1
10416	87	8	1997-01-16	3
10417	73	4	1997-01-16	3
10415	36	3	1997-01-15	1
10413	41	3	1997-01-14	2
10414	21	2	1997-01-14	3
10412	87	8	1997-01-13	2
10410	10	3	1997-01-10	3
10411	10	9	1997-01-10	3
10409	54	3	1997-01-09	1
10408	23	8	1997-01-08	1
10406	62	7	1997-01-07	1
10407	56	2	1997-01-07	2
10405	47	1	1997-01-06	1
10403	20	4	1997-01-03	3
10404	49	2	1997-01-03	1
10402	20	8	1997-01-02	2
10400	19	1	1997-01-01	3
10401	65	1	1997-01-01	1
10399	83	8	1996-12-31	3
10398	71	2	1996-12-30	3
10396	25	1	1996-12-27	3
10397	60	5	1996-12-27	1
10395	35	6	1996-12-26	1
10393	71	1	1996-12-25	3
10394	36	1	1996-12-25	3
10392	59	2	1996-12-24	3
10390	20	6	1996-12-23	1
10391	17	3	1996-12-23	3
10389	10	4	1996-12-20	2
10388	72	2	1996-12-19	1
10386	21	9	1996-12-18	3
10387	70	1	1996-12-18	2
10385	75	1	1996-12-17	2
10383	4	8	1996-12-16	3
10384	5	3	1996-12-16	3
10382	20	4	1996-12-13	1
10380	37	8	1996-12-12	3
10381	46	3	1996-12-12	3
10379	61	2	1996-12-11	1
10378	24	5	1996-12-10	3
10376	51	1	1996-12-09	2
10377	72	1	1996-12-09	3
10375	36	3	1996-12-06	2
10373	37	4	1996-12-05	3
10374	91	1	1996-12-05	3
10372	62	5	1996-12-04	2
10370	14	6	1996-12-03	2
10371	41	1	1996-12-03	1
10369	75	8	1996-12-02	2
10368	20	2	1996-11-29	2
10366	29	8	1996-11-28	2
10367	83	7	1996-11-28	3
10365	3	3	1996-11-27	2
10363	17	4	1996-11-26	3
10364	19	1	1996-11-26	1
10362	9	3	1996-11-25	1
10360	7	4	1996-11-22	3
10361	63	1	1996-11-22	2
10359	72	5	1996-11-21	3
10358	41	5	1996-11-20	1
10357	46	1	1996-11-19	3
10356	86	6	1996-11-18	2
10355	4	6	1996-11-15	1
10354	58	8	1996-11-14	3
10353	59	7	1996-11-13	3
10352	28	3	1996-11-12	3
10350	41	6	1996-11-11	2
10351	20	1	1996-11-11	1
10349	75	7	1996-11-08	1
10348	86	4	1996-11-07	2
10347	21	4	1996-11-06	3
10346	65	3	1996-11-05	3
10345	63	2	1996-11-04	2
10344	89	4	1996-11-01	2
10343	44	4	1996-10-31	1
10342	25	4	1996-10-30	2
10340	9	1	1996-10-29	3
10341	73	7	1996-10-29	3
10339	51	2	1996-10-28	2
10338	55	4	1996-10-25	3
10337	25	4	1996-10-24	3
10336	60	7	1996-10-23	2
10335	37	7	1996-10-22	2
10334	84	8	1996-10-21	2
10333	87	5	1996-10-18	3
10332	51	3	1996-10-17	2
10330	46	3	1996-10-16	1
10331	9	9	1996-10-16	1
10329	75	4	1996-10-15	2
10328	28	4	1996-10-14	3
10327	24	2	1996-10-11	1
10326	8	4	1996-10-10	2
10325	39	1	1996-10-09	3
10324	71	9	1996-10-08	1
10323	39	4	1996-10-07	1
10322	58	7	1996-10-04	3
10320	87	5	1996-10-03	3
10321	38	3	1996-10-03	2
10319	80	7	1996-10-02	3
10318	38	8	1996-10-01	2
10317	48	6	1996-09-30	1
10316	65	1	1996-09-27	3
10315	38	4	1996-09-26	2
10314	65	1	1996-09-25	2
10313	63	2	1996-09-24	2
10312	86	2	1996-09-23	2
10310	77	8	1996-09-20	2
10311	18	1	1996-09-20	3
10309	37	3	1996-09-19	1
10308	2	7	1996-09-18	3
10307	48	2	1996-09-17	2
10306	69	1	1996-09-16	3
10305	55	8	1996-09-13	3
10304	80	1	1996-09-12	2
10303	30	7	1996-09-11	2
10302	76	4	1996-09-10	2
10300	49	2	1996-09-09	2
10301	86	8	1996-09-09	2
10299	67	4	1996-09-06	2
10298	37	6	1996-09-05	2
10297	7	5	1996-09-04	2
10296	46	6	1996-09-03	1
10295	85	2	1996-09-02	2
10294	65	4	1996-08-30	2
10293	80	1	1996-08-29	3
10292	81	1	1996-08-28	2
10290	15	8	1996-08-27	1
10291	61	6	1996-08-27	2
10289	11	7	1996-08-26	3
10288	66	4	1996-08-23	1
10287	67	8	1996-08-22	3
10286	63	8	1996-08-21	3
10285	63	1	1996-08-20	2
10284	44	4	1996-08-19	1
10283	46	3	1996-08-16	3
10282	69	4	1996-08-15	1
10280	5	2	1996-08-14	1
10281	69	4	1996-08-14	1
10279	44	8	1996-08-13	2
10278	5	8	1996-08-12	2
10277	52	2	1996-08-09	3
10276	80	8	1996-08-08	3
10275	49	1	1996-08-07	1
10274	85	6	1996-08-06	1
10273	63	3	1996-08-05	3
10272	65	6	1996-08-02	2
10270	87	1	1996-08-01	1
10271	75	6	1996-08-01	2
10269	89	5	1996-07-31	1
10268	33	8	1996-07-30	3
10267	25	4	1996-07-29	1
10266	87	3	1996-07-26	3
10265	7	2	1996-07-25	1
10264	24	6	1996-07-24	3
10263	20	9	1996-07-23	3
10262	65	8	1996-07-22	3
10260	55	4	1996-07-19	1
10261	61	4	1996-07-19	2
10259	13	4	1996-07-18	3
10258	20	1	1996-07-17	1
10257	35	4	1996-07-16	3
10256	88	3	1996-07-15	2
10255	68	9	1996-07-12	3
10254	14	5	1996-07-11	2
10253	34	3	1996-07-10	2
10252	76	4	1996-07-09	2
10250	34	4	1996-07-08	2
10251	84	3	1996-07-08	1
10249	81	6	1996-07-05	1
10248	90	5	1996-07-04	3

### find all suppliers who have names longer than 20 characters. You can use `length(SupplierName)` to get the length of the name. Returns 11 records.
> This can be done with SELECT and WHERE clauses

Number of Records: 11
SupplierID	SupplierName	ContactName	Address	City	PostalCode	Country	Phone
2	New Orleans Cajun Delights	Shelley Burke	P.O. Box 78934	New Orleans	70117	USA	(100) 555-4822
3	Grandma Kelly's Homestead	Regina Murphy	707 Oxford Rd.	Ann Arbor	48104	USA	(313) 555-5735
5	Cooperativa de Quesos 'Las Cabras'	Antonio del Valle Saavedra	Calle del Rosal 4	Oviedo	33007	Spain	(98) 598 76 54
8	Specialty Biscuits, Ltd.	Peter Wilson	29 King's Way	Manchester	M14 GSD	UK	(161) 555-4448
10	Refrescos Americanas LTDA	Carlos Diaz	Av. das Americanas 12.890	São Paulo	5442	Brazil	(11) 555 4640
11	Heli Süßwaren GmbH & Co. KG	Petra Winkler	Tiergartenstraße 5	Berlin	10785	Germany	(010) 9984510
12	Plutzer Lebensmittelgroßmärkte AG	Martin Bein	Bogenallee 51	Frankfurt	60439	Germany	(069) 992755
13	Nord-Ost-Fisch Handelsgesellschaft mbH	Sven Petersen	Frahmredder 112a	Cuxhaven	27478	Germany	(04721) 8713
14	Formaggi Fortini s.r.l.	Elio Rossi	Viale Dante, 75	Ravenna	48100	Italy	(0544) 60323
18	Aux joyeux ecclésiastiques	Guylène Nodier	203, Rue des Francs-Bourgeois	Paris	75004	France	(1) 03.83.00.68
19	New England Seafood Cannery	Robb Merchant	Order Processing Dept. 2100 Paul Revere Blvd.	Boston	02134	USA	(617) 555-3267


### find all customers that include the word "market" in the name. Should return 4 records.
> This can be done with SELECT and a WHERE clause using the LIKE keyword

Number of Records: 4
CustomerID	CustomerName	ContactName	Address	City	PostalCode	Country
10	Bottom-Dollar Marketse	Elizabeth Lincoln	23 Tsawassen Blvd.	Tsawassen	T2F 8M4	Canada
32	Great Lakes Food Market	Howard Snyder	2732 Baker Blvd.	Eugene	97403	USA
71	Save-a-lot Markets	Jose Pavarotti	187 Suffolk Ln.	Boise	83720	USA
89	White Clover Markets	Karl Jablonski	305 - 14th Ave. S. Suite 3B	Seattle	98128	USA

> Don't forget the wildcard '%' symbols at the beginning and end of your substring to denote it can appear anywhere in the string in question

### add a customer record for _"The Shire"_, the contact name is _"Bilbo Baggins"_ the address is _"1 Hobbit-Hole"_ in _"Bag End"_, postal code _"111"_ and the country is _"Middle Earth"_.
> This can be done with the INSERT INTO clause

You have made changes to the database. Rows affected: 1	

### update _Bilbo Baggins_ record so that the postal code changes to _"11122"_.
> This can be done with UPDATE and WHERE clauses

You have made changes to the database. Rows affected: 1	

### list orders grouped by customer showing the number of orders per customer. _Rattlesnake Canyon Grocery_ should have 7 orders.
> This can be done with SELECT, COUNT, JOIN and GROUP BY clauses. Your count should focus on a field in the Orders table, not the Customer table

Number of Records: 74
OrdersPerCustomer	CustomerName
1	Ana Trujillo Emparedados y helados
1	Antonio Moreno Taquería
2	Around the Horn
1	B's Beverages
3	Berglunds snabbköp
4	Blondel père et fils
3	Bon app'
4	Bottom-Dollar Marketse
1	Bólido Comidas preparadas
1	Centro comercial Moctezuma
2	Chop-suey Chinese
1	Comércio Mineiro
1	Consolidated Holdings
4	Die Wandernde Kuh
2	Drachenblut Delikatessend
1	Du monde entier
2	Eastern Connection
10	Ernst Handel
3	Familia Arquibaldo
1	Folies gourmandes
4	Folk och fä HB
1	Franchi S.p.A.
4	Frankenversand
2	Furia Bacalhau e Frutos do Mar
1	GROSELLA-Restaurante
2	Galería del gastrónomo
1	Godos Cocina Típica
1	Gourmet Lanchonetes
2	HILARIÓN-Abastos
2	Hanari Carnes
3	Hungry Coyote Import Store
6	Hungry Owl All-Night Grocers
3	Island Trading
2	Königlich Essen
5	LILA-Supermercado
1	LINO-Delicateses
5	La maison d'Asie
3	Lehmanns Marktstand
2	Lonesome Pine Restaurant
3	Magazzini Alimentari Riuniti
1	Morgenstern Gesundkost
5	Mère Paillarde
1	Océano Atlántico Ltda.
4	Old World Delicatessen
1	Ottilies Käseladen
2	Pericles Comidas clásicas
3	Piccolo und mehr
3	Princesa Isabel Vinhoss
7	QUICK-Stop
4	Que Delícia
2	Queen Cozinha
7	Rattlesnake Canyon Grocery
3	Reggiani Caseifici
2	Ricardo Adocicados
2	Richter Supermarkt
3	Romero y tomillo
1	Santé Gourmet
4	Save-a-lot Markets
3	Seven Seas Imports
2	Simons bistro
6	Split Rail Beer & Ale
2	Suprêmes délices
1	The Big Cheese
1	Toms Spezialitäten
4	Tortuga Restaurante
2	Tradição Hipermercados
2	Vaffeljernet
2	Victuailles en stock
2	Vins et alcools Chevalier
7	Wartian Herkku
2	Wellington Importadora
2	White Clover Markets
1	Wilman Kala
1	Wolski

> There is more information about the COUNT clause on [W3 Schools](https://www.w3schools.com/sql/sql_count_avg_sum.asp)

### list customers names and the number of orders per customer. Sort the list by number of orders in descending order. _Ernst Handel_ should be at the top with 10 orders followed by _QUICK-Stop_, _Rattlesnake Canyon Grocery_ and _Wartian Herkku_ with 7 orders each.
> This can be done by adding an ORDER BY clause to the previous answer

Number of Records: 74
OrdersPerCustomer	CustomerName
10	Ernst Handel
7	QUICK-Stop
7	Rattlesnake Canyon Grocery
7	Wartian Herkku
6	Hungry Owl All-Night Grocers
6	Split Rail Beer & Ale
5	LILA-Supermercado
5	La maison d'Asie
5	Mère Paillarde
4	Blondel père et fils
4	Bottom-Dollar Marketse
4	Die Wandernde Kuh
4	Folk och fä HB
4	Frankenversand
4	Old World Delicatessen
4	Que Delícia
4	Save-a-lot Markets
4	Tortuga Restaurante
3	Berglunds snabbköp
3	Bon app'
3	Familia Arquibaldo
3	Hungry Coyote Import Store
3	Island Trading
3	Lehmanns Marktstand
3	Magazzini Alimentari Riuniti
3	Piccolo und mehr
3	Princesa Isabel Vinhoss
3	Reggiani Caseifici
3	Romero y tomillo
3	Seven Seas Imports
2	Around the Horn
2	Chop-suey Chinese
2	Drachenblut Delikatessend
2	Eastern Connection
2	Furia Bacalhau e Frutos do Mar
2	Galería del gastrónomo
2	HILARIÓN-Abastos
2	Hanari Carnes
2	Königlich Essen
2	Lonesome Pine Restaurant
2	Pericles Comidas clásicas
2	Queen Cozinha
2	Ricardo Adocicados
2	Richter Supermarkt
2	Simons bistro
2	Suprêmes délices
2	Tradição Hipermercados
2	Vaffeljernet
2	Victuailles en stock
2	Vins et alcools Chevalier
2	Wellington Importadora
2	White Clover Markets
1	Ana Trujillo Emparedados y helados
1	Antonio Moreno Taquería
1	B's Beverages
1	Bólido Comidas preparadas
1	Centro comercial Moctezuma
1	Comércio Mineiro
1	Consolidated Holdings
1	Du monde entier
1	Folies gourmandes
1	Franchi S.p.A.
1	GROSELLA-Restaurante
1	Godos Cocina Típica
1	Gourmet Lanchonetes
1	LINO-Delicateses
1	Morgenstern Gesundkost
1	Océano Atlántico Ltda.
1	Ottilies Käseladen
1	Santé Gourmet
1	The Big Cheese
1	Toms Spezialitäten
1	Wilman Kala
1	Wolski


### list orders grouped by customer's city showing number of orders per city. Returns 58 Records with _Aachen_ showing 2 orders and _Albuquerque_ showing 7 orders.
> This is very similar to the previous two queries, however, it focuses on the City rather than the CustomerName

Number of Records: 58
OrdersPerCity	City
2	Aachen
7	Albuquerque
4	Anchorage
2	Barcelona
5	Barquisimeto
3	Bergamo
2	Bern
4	Boise
2	Brandenburg
4	Bräcke
1	Buenos Aires
1	Campinas
1	Caracas
2	Charleroi
6	Cork
3	Cowes
7	Cunewalde
3	Elgin
3	Frankfurt a.M.
2	Genève
10	Graz
1	Helsinki
1	I. de Margarita
1	Köln
2	København
6	Lander
1	Leipzig
1	Lille
5	Lisboa
9	London
3	Luleå
2	Lyon
4	Madrid
3	Marseille
5	Montréal
9	México D.F.
4	München
1	Münster
1	Nantes
7	Oulu
3	Portland
3	Reggio Emilia
2	Reims
2	Resende
8	Rio de Janeiro
3	Salzburg
2	San Cristóbal
2	Seattle
1	Sevilla
1	Stavern
4	Strasbourg
4	Stuttgart
8	São Paulo
1	Torino
5	Toulouse
4	Tsawassen
1	Walla
2	Århus


## Stretch Goals

### delete all customers that have no orders. Should delete 17 (or 18 if you haven't deleted the record added) records.
> This is done with a DELETE query



> In the WHERE clause, you can provide another list with an IN keyword this list can be the result of another SELECT query. Write a query to return a list of CustomerIDs that meet the criteria above. Pass that to the IN keyword of the WHERE clause as the list of IDs to be deleted


 
> Use a LEFT JOIN to join the Orders table onto the Customers table and check for a NULL value in the OrderID column

## Create Database and Table

### Keep track of the code you write and paste at the end of this document

- use pgAdmin to create a database, naming it `budget`.
- add an `accounts` table with the following _schema_:

  - `id`, numeric value with no decimal places that should autoincrement.
  - `name`, string, add whatever is necessary to make searching by name faster.
  - `budget` numeric value.

- constraints
  - the `id` should be the primary key for the table.
  - account `name` should be unique.
  - account `budget` is required.
