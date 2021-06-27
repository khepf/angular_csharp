- dotnet new sln
- dotnet new webapi -o API
- dotnet sln add API
- cd API
- dotnet run
- dotnet dev-certs https --trust
- dotnet watch run

- Entity Framework allows for communication between backend and db

- dotnet tool install --global dotnet-ef --version 5.0.7
// Creating Database
- dotnet ef migrations add InitialCreate -o Data/Migrations
// create the database
- dotnet ef database update

- git init
- dotnet new gitignore
- git remote add origin https://github.com/khepf/angular_csharp.git
- git push -u origin master

# Angular
- npm install -g @angular/cli
- ng serve
 - VS CODE Extensions - Angular Langueage Service, Angular Snippets, Bracke Pair Colorizer 2
- ng add ngx-bootstrap
- npm install font-awesome