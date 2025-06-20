# dataBaseAssignment

## Overview
NetEaseDB is a web application built with ASP.NET Core MVC that allows users to manage event bookings, venues, and event information.

## Features
- Create, view, edit, and delete Venues, Events, and Bookings
- Prevent deletion of Venues and Events if they are associated with active Bookings
- Display success and error messages using TempData
- Venue image support via URL (e.g., for Azure Blob Storage)
- Prevention of double bookings
- Search Filter for Booking Page by Booking ID or Event Name
- Search Filters for Event Page by Event Type, Venue and Date

## Technologies Used
- ASP.NET Core MVC
- Entity Framework Core
- SQL Server / LocalDB
- Bootstrap (styling)
- Azure Blob Storage (for images)

## How to Run
1. Clone this repository.
2. Open the solution in Visual Studio.
3. Install Nuget packages
   - Microsoft.EntityFrameworkCore by Microsoft
   - Microsoft.EntityFrameworkCore.SqlServer by Microsoft
   - Microsoft.EntityFrameworkCore.Tools by Microsoft
   - Azure Blob Storage
4. Apply migrations and update the database.
5. Account for any secrets:
   - Azure Blob Storage connection string
   - Database connection string
6. Run the project.

## Folder Structure
- `Controllers/` – MVC Controllers
- `Models/` – Entity Models
- `Views/` – Razor Pages
- `wwwroot/` – Static files
- `README.md` – Project documentation

## Future Enhancements
- Client Log in system