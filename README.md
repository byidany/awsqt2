# .NET 9 ASP.NET Core Web Application

This is a sample web application built with .NET 9 and ASP.NET Core, demonstrating the basic project structure and configuration.

## Project Structure

- **Controllers**: Contains MVC controllers that handle HTTP requests
  - `HomeController.cs`: Handles requests for the home and privacy pages
- **Models**: Contains data models used in the application
  - `ErrorViewModel.cs`: Model for error information display
- **Views**: Contains the UI templates
  - `Home/Index.cshtml`: Landing page with application description
  - `Home/Privacy.cshtml`: Privacy policy page
  - `Shared/_Layout.cshtml`: Main layout template for the site
  - `Shared/Error.cshtml`: Error display page
- **wwwroot**: Contains static files (CSS, JavaScript, etc.)

## Getting Started

### Prerequisites

- [.NET 9 SDK](https://dotnet.microsoft.com/download)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)

### Running the Application

1. Clone this repository
   ```
   git clone https://github.com/yourusername/WebApp.git
   ```

2. Navigate to the project directory
   ```
   cd WebApp
   ```

3. Run the application
   ```
   dotnet run
   ```

4. Open your browser and navigate to `https://localhost:5001` or `http://localhost:5000`

## Development Environment

The application is configured with different settings for development and production environments:

- **Development**: More detailed logging, developer exception page
- **Production**: Error handling, HTTPS redirection, HSTS

## Features

- MVC architecture with Controllers, Views, and Models
- Responsive design using Bootstrap
- Error handling
- Environment-specific configuration

## License

This project is licensed under the MIT License - see the LICENSE file for details.