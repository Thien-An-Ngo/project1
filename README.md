# Project 1

Web Programming with Python and JavaScript

## 0.1 Setup

  `DATABASE_URL=postgres://srnwovmyccfpnj:37640f4bf3c4b28f2b3ee99fbbb1d9ffe72cd04a203a8ba98c9ea44520dcf691@ec2-52-6-143-153.compute-1.amazonaws.com:5432/daus1tm2bsv6d2 FLASK_APP=application.py FLASK_ENV=development flask run`



## TO DO

* SET UP A heroku DATABASE
* SET UP THE FLASK SERVER CONNECTED TO THE HEROKU DATABASE
* BUILD A BASIC PAGE WITH A LOGIN AND AN OPTION TO REGISTER
* BUILD A REGISTRATION PAGE
* IMPORT books.csv INTO THE DATABASE VIA AN import.py FILE
* BUILD A BASE PAGE WITH A NAVBAR CONTAINING A SEARCH PAGE LINK AND A LOGOUT OPTION
* BUILD A SEARCH PAGE WHICH SEARCHES BOOKS BY ISBN, AUTHOR NAME, OR TITLE
* BUILD A BOOK PAGE ON WHICH A REVIEW CAN BE SUBMITTED CONTAINING
    * A RATING SCALE FROM 1 TO 5
    * A TEXT COMPONENT FOR AN OPINION
    * USERS SHOULD NOT BE ABLE TO SUBMIT MULTIPLE REVIEWS
* THE BOOK PAGE ALSO DISPLAYS THE AVAILABLE AVERAGE RATING AND NUMBER OF RATINGS FROM GOODREADS
* BUILD A ``/api/<isbn>`` WHERE <isbn> IS THE ISBN OF THE BOOK RESULTING IN A JSON WITH
    * THE TITLE
    * THE AUTHOR
    * THE PUBLISHING YEAR
    * THE ISBN
    * THE REVIEW COUNT
    * AND THE AVERAGE SCORE
* IF THE ISBN IS NOT IN THE DATABASE, THE PAGE SHOULD SHOW A 404 Error

### TO USE

* RAW SQL COMMANDS
* ALL ADDITIONAL PYTHON PACKAGES SHOULD BE CONTAINED WITHIN THE requirements.txt FILE

## 
