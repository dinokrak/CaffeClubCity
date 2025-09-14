# Caffe Club City Web Application

ASP.NET Core MVC web application for Caffe Club City management.

## Features

- 🎯 Menu management (Food & Drinks)
- 📅 Reservation system for tables (Billiards, Darts, Digital games)
- 📰 News/Events feed with social media integration
- 🖼️ Gallery management
- 📞 Contact form with admin panel 
- 👨‍💼 Admin panel with authentication 
- 🔐 User roles and authorization 

## Tech Stack

- **Backend**: ASP.NET Core 8 MVC, Entity Framework Core
- **Frontend**: Bootstrap 5, JavaScript
- **Database**: MS SQL Server
- **Authentication**: ASP.NET Identity 
- **Authorization**: Role-based 

## Project Structure
CaffeClubCity/
├── CaffeClubCity.Web/ # MVC Web Application
├── CaffeClubCity.Core/ # Business Models & Logic
├── CaffeClubCity.Infrastructure/ # Data Access & EF Core

## Setup
1. Clone repository
2. Restore NuGet packages  
3. Run migrations: `Update-Database` 👈 DODAJ
4. Default admin user: admin@caffeclubcity.com / Admin123! 👈 DODAJ
5. Run application
