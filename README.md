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
     <td>Index Page</td>
     <td>Categories Page</td>
  </tr>
  <tr>
    <td><img src="https://private-user-images.githubusercontent.com/165982458/371873124-563f32f0-9a3b-4bb8-a131-6c9c625e88ef.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Mjc2Mjk4MzUsIm5iZiI6MTcyNzYyOTUzNSwicGF0aCI6Ii8xNjU5ODI0NTgvMzcxODczMTI0LTU2M2YzMmYwLTlhM2ItNGJiOC1hMTMxLTZjOWM2MjVlODhlZi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwOTI5JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDkyOVQxNzA1MzVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wMzM4N2UyMDljZDMzY2VjNTVhNTNiZmJkODE5OGUwZWY1ZWVjZTEyOTgxNmQ5MTIyYzA5ZWY1ZjA4YTdlODY2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.HQ3TjRtZG_9lKHQzt2hRkEGo5AuBxuBWx7aBOQDGUO4" width=270 height=480></td>
    <td><img src="https://private-user-images.githubusercontent.com/165982458/371873407-e5086b27-e1ad-4ad7-9758-a7ec2b6b03a0.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Mjc2Mjk4MzUsIm5iZiI6MTcyNzYyOTUzNSwicGF0aCI6Ii8xNjU5ODI0NTgvMzcxODczNDA3LWU1MDg2YjI3LWUxYWQtNGFkNy05NzU4LWE3ZWMyYjZiMDNhMC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwOTI5JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDkyOVQxNzA1MzVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03MDRkN2RlODQ0MTQ3OGVlYmNiZWZmMDVlZDI3NTQ0ZmRlYmJmZDYxMDhjMDBkZDc5NTYyN2MxNDhmNzZkM2E4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.eD-C1bKy283_oVJENt0HPjVG51-WwTFoth7mMEpALPg" width=270 height=480></td>
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
    <img alt="rspec passed" src="https://private-user-images.githubusercontent.com/165982458/371873527-1aa3ec40-57f1-4330-89a1-6f4ebc5fefa7.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Mjc2Mjk5NjcsIm5iZiI6MTcyNzYyOTY2NywicGF0aCI6Ii8xNjU5ODI0NTgvMzcxODczNTI3LTFhYTNlYzQwLTU3ZjEtNDMzMC04OWExLTZmNGViYzVmZWZhNy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwOTI5JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDkyOVQxNzA3NDdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xZDI0MjljYjdmYTM3MDgxNzE1Zjc2YmE1NzlkYjczM2E5NDI1MWEwNzk2NDZlN2VhNGEyNjc2YzAxOGFmZTcyJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.RkjqDmDyl4njv7c8x8trtC21VMe2-CmMhW5xV31WCNA" width=90% />
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

