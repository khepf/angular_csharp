dotnet new sln
dotnet new webapi -o API
dotnet sln add API
cd API
dotnet run
dotnet dev-certs https --trust
dotnet watch run

- Entity Framework allows for communication between backend and db

dotnet tool install --global dotnet-ef --version 5.0.7
// Creating Database
dotnet ef migrations add InitialCreate -o Data/Migrations
// create the database
dotnet ef database update

git init
dotnet new gitignore