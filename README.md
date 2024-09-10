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
    <td><img src="https://private-user-images.githubusercontent.com/165982458/365993716-a4716cd0-d436-444c-af5c-368be44310b7.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjU5NjI3ODgsIm5iZiI6MTcyNTk2MjQ4OCwicGF0aCI6Ii8xNjU5ODI0NTgvMzY1OTkzNzE2LWE0NzE2Y2QwLWQ0MzYtNDQ0Yy1hZjVjLTM2OGJlNDQzMTBiNy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwOTEwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDkxMFQxMDAxMjhaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1iMmI5N2I3YzViNWRkZTc1OTYwZTgxNjUzOGM2ZjllNzMwMzExYTgwODgzNzFmMzgyYjM2M2Y3OGYyZmQ1MTdiJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.Y8evrQ6NsAc-NytkHKX5zSeLbliQ6bezrnZqenlrXy4" width=270 height=480></td>
    <td><img src="https://private-user-images.githubusercontent.com/165982458/365993865-3c7a6f83-f556-4542-9fb2-aacaac21e631.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjU5NjI3ODgsIm5iZiI6MTcyNTk2MjQ4OCwicGF0aCI6Ii8xNjU5ODI0NTgvMzY1OTkzODY1LTNjN2E2ZjgzLWY1NTYtNDU0Mi05ZmIyLWFhY2FhYzIxZTYzMS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwOTEwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDkxMFQxMDAxMjhaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT05NGMyZjUxZWY5MmFiYWRjM2NlN2I1YTEwMDdmY2ZkN2M4MzlkZjc3ODg5M2I5ZjUyM2ZhMTdhN2FiNGE3MDkzJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.Hd5lrZGqWrcNoE7BbokQkx_2hGG70wI0Xmz1ihwRnso" width=270 height=480></td>
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
    <img alt="rspec passed" src="https://private-user-images.githubusercontent.com/165982458/365995143-4e9db5c3-ccda-47ed-aab0-bf5d02b8210f.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjU5NjMwMzUsIm5iZiI6MTcyNTk2MjczNSwicGF0aCI6Ii8xNjU5ODI0NTgvMzY1OTk1MTQzLTRlOWRiNWMzLWNjZGEtNDdlZC1hYWIwLWJmNWQwMmI4MjEwZi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwOTEwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDkxMFQxMDA1MzVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yYmRiNDUzZjU2ZDJmMGNlMDM2OTI5ZTNlNmI4ZTM5NWY0YmY5MmFhODg0ZjUzYWZiNmFhZjA3ZDI2NmIzYjFiJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.UxykpYtQ8kZTyHy42PBDpCDY5cBTjVIJVXC1OhesTKo" width=90% />
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

