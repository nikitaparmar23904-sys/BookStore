# BookNest - Online Book Store (ASP.NET Core MVC)

A complete MCA-level online bookstore project designed to run with **Visual Studio 2019 + .NET Core 3.1 + SQL Server LocalDB**.

## Features
- Professional customer-facing bookstore UI
- Search and category filter
- Book details page
- Register / Login / Logout
- Shopping cart: Add, Update quantity, Remove, Clear
- Checkout with shipping address and order creation
- My Orders with status and order details
- Admin dashboard
- Admin Book CRUD: Add, Edit, Delete, Stock, Price, Rating, Image URL
- Category management
- Order management with status updates
- Automatic database creation and demo seed data
- Admin account: `admin@booknest.com` / `Admin@123`

## Run in Visual Studio 2019
1. Extract the ZIP.
2. Open `BookNestStore.csproj` in Visual Studio 2019.
3. Restore NuGet packages.
4. Make sure SQL Server LocalDB is installed (Visual Studio installer normally provides it).
5. Press **Ctrl + F5**.
6. The database `BookNestDb` is created automatically on first run.

If your SQL Server instance is different, edit `appsettings.json` connection string.

## Important
The cover images use Open Library image URLs. Internet is needed for those images; the UI automatically shows a styled fallback cover if an image cannot be loaded.
