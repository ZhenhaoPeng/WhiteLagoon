# WhiteLagoon 🏖️

**WhiteLagoon** is a clean architecture web application built with ASP.NET Core, following the layered domain-driven design principles. It serves as a property management system for managing villas, villa numbers, and amenities.

---

## 📁 Project Structure

- **WhiteLagoon.Application** – Application layer containing interfaces and DTOs.
- **WhiteLagoon.Domain** – Core domain models (e.g., `Villa`, `Amenity`, `VillaNumber`).
- **WhiteLagoon.Infrastructure** – Data access layer with Entity Framework Core setup.
- **WhiteLagoon.Web** – ASP.NET Core MVC web frontend.

---

## 💡 Features

- ✅ Clean Architecture with clear separation of concerns  
- ✅ Entity Framework Core with code-first migration  
- ✅ ASP.NET Core MVC views  
- ✅ SQL Server backend (local config ignored from Git)  
- ✅ Modular structure, easy to scale and maintain

---

## 📌 Roadmap

Planned features to be added in the future:

- 🔐 **Add user authentication and role management** (ASP.NET Identity)
- ☁️ **Deploy the application** to Azure or another cloud platform
- 📅 **Implement a Booking module** (date selection, availability check, confirmation)
- 🌐 **Create a RESTful API layer**
- 📊 **Add an admin dashboard** with data statistics and export
- 🧪 **Add unit and integration testing**

---

## 🛠️ Technologies

- ASP.NET Core 6+
- Entity Framework Core
- Microsoft SQL Server
- C#
- Bootstrap (for styling)


---

## 🚀 Getting Started

### Prerequisites

- .NET 6 SDK or newer  
- Visual Studio 2022+  
- SQL Server (LocalDB or Full)


