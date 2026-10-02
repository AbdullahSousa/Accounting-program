# Accounting Program

A Windows desktop application for managing a small business's finances, built with C# (WinForms, .NET Framework 4.7.2) and a MySQL database.

## Features

- **Login** screen backed by a users table
- **Income:** add, view and delete income records (source, amount, date, type)
- **Expenses** tracking
- **Customers** and **Employees** management
- **Subscriptions** management
- **Home / Main page** dashboard for moving between modules

## Project structure

```
Accounting program/
├── Login Form.cs      # authentication
├── Main Page.cs       # main navigation
├── Home.cs
├── income.cs          # income records (MySQL, parameterised queries)
├── Expenses.cs
├── Customers.cs
├── Employee.cs
├── Subscriptions.cs
└── Program.cs         # entry point
```

## Getting started

1. Open `Accounting program.sln` in Visual Studio.
2. Install the `MySql.Data` NuGet package if it isn't restored automatically.
3. Create a local MySQL database and update the connection string in the forms to match your server and credentials.
4. Build and run.

## Tech stack

C# · .NET Framework 4.7.2 · Windows Forms · MySQL
