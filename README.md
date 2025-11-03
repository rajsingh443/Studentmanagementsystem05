# Student Management System (.NET 8 MVC)

A fully functional ASP.NET Core MVC project using **SQLite** and **Identity Authentication**.

## Features
- Role-based access: Admin and Student
- Admin can manage student records (CRUD)
- Student can view and update their details
- SQLite for local database storage
- ASP.NET Core Identity authentication

## Getting Started
1. Open in Visual Studio Code.
2. Run these commands:
   ```bash
   dotnet restore
   dotnet ef migrations add InitialCreate
   dotnet ef database update
   dotnet run
   ```
3. Open `https://localhost:5001` in your browser.

## Default Roles & Accounts
- Admin: admin@demo.com / Admin123!
- Student: student@demo.com / Student123!
