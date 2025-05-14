
📝 Overview
Nilura is a full-featured e-commerce platform specialized for fashion and apparel retail, developed as a graduation project using ASP.NET MVC. The platform delivers a complete online shopping experience from product discovery to checkout, with built-in order management and administrative capabilities.
The system implements industry best practices for web development, ensuring scalability, maintainability, and security throughout the application.


🏗️ Architecture
The application follows the N-Tier Architecture pattern with clearly separated concerns:
Nilura E-Commerce/
│
├── E-Commerce/                  # Presentation Layer (MVC)
│   ├── Areas/                   # Feature areas (Admin, Customer, Identity)
│   ├── Controllers/             # MVC controllers
│   ├── Views/                   # Razor views
│   ├── wwwroot/                 # Static files (CSS, JS, images)
│   └── Program.cs               # Application entry point
│
├── E-Commerce.DataAccess/       # Data Access Layer
│   ├── Data/                    # DbContext and database configuration
│   ├── Repository/              # Generic and specific repositories
│   ├── DbInitializer/           # Database seeding and initialization
│   └── Migrations/              # EF Core migrations
│
├── E-Commerce.Models/           # Business Models Layer
│   ├── Models/                  # Domain entities
│   ├── ViewModels/              # View-specific models
│   └── DTOs/                    # Data transfer objects
│
└── E-Commerce.Utility/          # Utility Layer
    ├── SD.cs                    # Static details and constants
    ├── EmailSender.cs           # Email service
    └── Helpers/                 # Helper classes and extensions

Design Patterns Implemented
Repository Pattern: Abstracts the data layer, making the application more testable
Unit of Work: Maintains a list of objects affected by a business transaction
Dependency Injection: Reduces coupling between classes
MVC Pattern: Separates the application into Model, View, and Controller



🛠️ Technologies Used

   Backend
   ASP.NET Core MVC
   Entity Framework Core
   C#
   SQL Server
   Identity Framework for authentication and authorization
   Frontend
   Razor Views
   Bootstrap
   JavaScript/jQuery
   AJAX
   HTML5/CSS3
   Payment Processing
   Stripe API Integration
   Development Tools
   Visual Studio
   Git for version control
   Azure for deployment (optional)





