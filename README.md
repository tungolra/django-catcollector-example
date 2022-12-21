# Cat Collector

### About 
A single-page application using Django, Python, and PostgreSQL as a webstack. This app also features the use of Django's session-based authentication and the use of AWS S3 to upload images. Users can sign up and create their own account or log in with existing credentials. 

A minimal web application that allows users to create a collection of cats. Users can utilize middleware to perform CRUD functions on Cats and Toys which adopt a many-to-many relationship model. Cats and Photos, as well as Cats and Feedings, share a one-to-many relationship. The application is given a minimal UI design using Materialize's styling framework and minimal CSS as it's main purpose is to demonstrate the leveraging of Django's framework to quickly launch a web application from start to finish. 

Employed is the use REST APIs to create, update, and delete Cat and Toy objects and assign toys to cats through PSQL's relational database. This app also demonstrates familiarity using Django's template language, performing Python methods to render data held in the database. 

### Cat Details Page 
Once a cat is created, they can view the details of their cat. Here, users can then add a photo of their cat, give their cat toys, and even input a feeding time. 
<img src="https://i.imgur.com/l5pJBnw.png">

### Cat List Page 
This page makes an API call for all Cat objects held in the database. The page design makes use of Materialize's cards templates to populate the cat's name, breed, description, and age. 

<img src="https://i.imgur.com/XRVS4RA.png">

### Add Cat Page 
Users can input form data to create a new cat. Once submitted, a POST request is triggered to insert a new Cat object into the database.  
<img src="https://i.imgur.com/spQFg8q.png">

### Add Toy Page 
Similar to adding a cat, users can also create new Toys. 
<img src="https://i.imgur.com/qPfTLYo.png">


### Toy List Page 
Similar to the Cat List Page, users can navigate to this page to view their list of toys that they can later give to each of their cats. 
<img src="https://i.imgur.com/IILOYjv.png">

### Log In Page 
Users can use existing credentials to log into their Cat Collectors account. 
<img src="https://i.imgur.com/wx7QL4c.png">

### Sign Up Page 
New users can register a new account by inputting form data. 
<img src="https://i.imgur.com/wVtGorO.png">

### Technologies
- Django
- Python
- PostgreSQL 
- Django template language/ HTML
- Django session-based authorization 
- CSS/Materialize
- AWS S3

### Credits
This application was created through a General Assembly module.

Completed Nov 2022. 