run dotnet new webapi -n "name" to create new webapi

dotnet add package Microsoft.EntityFrameworkCore
dotnet add package Npgsql.EntityFrameworkCore.PostgreSQL
dotnet add package Npgsql.EntityFrameworkCore.PostgreSQL.Design
dotnet add package Microsoft.EntityFrameworkCore.Design

create postgresql database: CREATE DATABASE cholapi;

install entity framework
dotnet tool install --global dotnet-ef

run migration
dotnet ef migrations add "name"

update database
dotnet ef database update

build
dotnet build

run
dotnet run
