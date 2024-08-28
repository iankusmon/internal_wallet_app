# internal_wallet_app


A **Budget app** is a web application where you can manage your internal wallet transaction sysyem: you have a list of transactions associated with a category, so that you can see how much money you spent and on what.

Everything will be based on the ERD class diagram presented below. 

</br>
 <div align="center">
    
    <p>Entity Relationship Diagram (ERD) of Internal Wallet App project</p>
</div>

<div align="center">
    <p>Entity Relationship Diagram (ERD) of Blog App project</p>
    <a href="https://drive.google.com/file/d/12uvMYRWAN22VOZutHliIGC8qnQkzDxgM/view?usp=sharing">Link Draw IO</a>
</div>

#### App Screenshots

<table>
  <tr>
     <td>Splash Page</td>
     <td>Categories Page</td>
  </tr>
  <tr>
    <td><img src="https://private-user-images.githubusercontent.com/165982458/362075689-d2c2bc12-f8cd-41e3-bec9-d44c5a547a2e.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjQ4MDk5NjYsIm5iZiI6MTcyNDgwOTY2NiwicGF0aCI6Ii8xNjU5ODI0NTgvMzYyMDc1Njg5LWQyYzJiYzEyLWY4Y2QtNDFlMy1iZWM5LWQ0NGM1YTU0N2EyZS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwODI4JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDgyOFQwMTQ3NDZaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0zNDM2NjEzMDgyOTJjNGM3NGFmMzQ5YjU4YjcxZjc0YmVlMzYwMTJlNWYyZDUyM2EzNWZlYjcyOTE1NTg2ZjY1JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.aXFQSTQ-SbJDiR_h0SKNCik7xhjC05fA1pjgNQk9yoo" width=270 height=480></td>
    <td><img src="https://private-user-images.githubusercontent.com/165982458/362076156-39703fa6-e463-417b-83d8-4d4cf8eb9eca.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjQ4MDk5NjYsIm5iZiI6MTcyNDgwOTY2NiwicGF0aCI6Ii8xNjU5ODI0NTgvMzYyMDc2MTU2LTM5NzAzZmE2LWU0NjMtNDE3Yi04M2Q4LTRkNGNmOGViOWVjYS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwODI4JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDgyOFQwMTQ3NDZaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xMzgzY2ZlNTJiMWY1NGRkZDA3MjQwYmIxMDkyOWU4ZWJmNDNkYWVjNDFhNjA4OWQwOGI2YjE4NWMzNjk3MWQzJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.vg7tCigCQ9AKYgL8JU_dTxThdjgXO9DrBgnW2Z6b_Kk" width=270 height=480></td>
  </tr>
 </table>

## Getting Started
To run the project locally, copy up and running follow these simple example steps :

 - First of all make sure you have both `Ruby` & `Rails` installed in your machine
 (else You can install `Rails` just with this simple command  ```gem install rails```)
 - clone the project with the following command line : 
```
$ git clone https://github.com/iankusmon/internal_wallet_app.git
```
 - Then go to the right folder 
```
$ cd internal_wallet_app
```
```
$ bundle
```
and run to install npm package
```
$ npm install
```

make sure the database is up and running.
```
$ rails db:create
```
When you will add migration file then, you can add command like
```
$ rails db:migrate
```

 - Finaly run `rails s` and visit http://localhost:3000/  in your browser!

 ## Run tests :

 To run Request specs locally you need just to run this following command in your terminal :

 ```
 $ bundle exec rspec
 ```
 </br>
 <div align="center">
    <kbd>
    
    <p>23 Request Specs passed</p>
       </kbd>
</div>

## Built With

 - Ruby on RAils  <img src="https://cdn.emojidex.com/emoji/seal/Ruby.png" width=15px>
 - PostgreSQL <img src="https://user-images.githubusercontent.com/80895497/142954032-f7072df9-3586-48f9-a9e0-7fdd284eb833.png" width=15px>
 
</br>

## Authors

👤 **Ian Kusmon**

- GitHub: [Ian Kusmon](https://github.com/iankusmon)
- LinkedIn : [M Rahardian K](https://www.linkedin.com/in/muhammad-rahardian-k-659090164/)
- Instagram: [@iian_kusmon](https://www.instagram.com/iiann_kusmon/)

