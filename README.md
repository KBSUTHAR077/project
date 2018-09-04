# project
    E-Library Management System Project
    Project on Java Programming Language..
    In this Project we use Core Java , Servelt and Java Server Pages (JSP).
    Database is SQL Yog Server.
    Client Side Programming Language Javascript's plugin JQuery in widely used 
    Integrated Development Environment (IDE) Tool Eclipse Mars..

-------------------------------------------------------------------------------------------------------------------------------------
# Vision
    A library management software where admin can add/view/delete librarian and librarian can add/view books, issue, view issued books and return books.
----------------------------------------------------------------------------------------------------------------------------------------
# Functional Requirements
    1. Admin
    Can add/edit/view/delete librarian
    Can logout
    2. Librarian
    Can add/edit/delete/view books
    Can issue books
    View issued books
    Return Books
    Can logout

---------------------------------------------------------------------------------------------------------------------------------------
# Tools to be used
    Use any IDE to develop the project. It may be Eclipse /Myeclipse / Netbeans etc.
    Oracle/MySQL for the database.

# Front End and Back End
     Front End: Servlet, HTML, CSS, Bootstrap
     Back End: SQLYog

----------------------------------------------------------------------------------------------------------------------------------------
# Table Stracture is..
     CREATE TABLE  "E_BOOK" 
       (	"CALLNO" VARCHAR2(4000), 
	"NAME" VARCHAR2(4000), 
	"AUTHOR" VARCHAR2(4000), 
	"PUBLISHER" VARCHAR2(4000), 
	"QUANTITY" NUMBER, 
	"ISSUED" NUMBER, 
	 CONSTRAINT "E_BOOK_PK" PRIMARY KEY ("CALLNO") ENABLE
       )
      /
            CREATE TABLE  "E_LIBRARIAN" 
        (	"ID" NUMBER, 
	 "NAME" VARCHAR2(4000), 
	"PASSWORD" VARCHAR2(4000), 
	"EMAIL" VARCHAR2(4000), 
	"MOBILE" NUMBER, 
	 CONSTRAINT "E_LIBRARIAN_PK" PRIMARY KEY ("ID") ENABLE
      )
      /
     Note: ID must be generated through sequence in E_LIBRARIAN table.

     CREATE TABLE  "E_ISSUEBOOK" 
       (	"CALLNO" VARCHAR2(4000) NOT NULL ENABLE, 
	  "STUDENTID" VARCHAR2(4000) NOT NULL ENABLE, 
	"STUDENTNAME" VARCHAR2(4000), 
	"STUDENTMOBILE" NUMBER, 
	"ISSUEDDATE" DATE, 
	"RETURNSTATUS" VARCHAR2(4000)
     )
   /
# How to run Project
# Welcome Page
![screenshot 35](https://user-images.githubusercontent.com/42708591/45014054-d866af00-b03a-11e8-86e3-183f7758f75e.png)
![screenshot 36](https://user-images.githubusercontent.com/42708591/45014057-da307280-b03a-11e8-9b20-5a48453656f6.png)
![screenshot 37](https://user-images.githubusercontent.com/42708591/45014060-dbfa3600-b03a-11e8-9b39-0d6403295570.png)
![screenshot 38](https://user-images.githubusercontent.com/42708591/45014063-dd2b6300-b03a-11e8-86dc-403a86181e9b.png)
![screenshot 39](https://user-images.githubusercontent.com/42708591/45014067-df8dbd00-b03a-11e8-83a6-6b2f13a64366.png)
![screenshot 40](https://user-images.githubusercontent.com/42708591/45014070-e1578080-b03a-11e8-8003-19e27f7faa25.png)
![screenshot 41](https://user-images.githubusercontent.com/42708591/45014074-e288ad80-b03a-11e8-8d05-eff9105f0654.png)
