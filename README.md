# Cafe Management System (Desktop App)

A Windows desktop application for managing a cafe, built with C# and Windows Forms on .NET Framework 4.7.2.

## Features

- Login and registration
- Add and manage menu items / stock
- Billing and payment screens
- Printable bills as PDF (iTextSharp)
- Due, loss and sales graph views

## Tech stack

- C# / Windows Forms (.NET Framework 4.7.2)
- MySQL (via `MySql.Data`)
- iTextSharp for PDF generation

## Getting started

1. Install Visual Studio 2019 or later with the **.NET desktop development** workload.
2. Install MySQL and create a database named `log`.
3. Update the connection string in `login and regi/DB.cs` to match your MySQL setup
   (host, port, username, password). Avoid committing real credentials.
4. Open `main.sln` in Visual Studio, restore packages and press **F5** to run.

## Project structure

- `main.sln` – Visual Studio solution
- `login and regi/` – application source (forms, database helper, resources)

## Author

[hasibul-nafiz](https://github.com/hasibul-nafiz)
