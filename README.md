# .NET 9 ASP.NET Core Web Application

This repository contains a .NET 9 ASP.NET Core web application with a basic MVC structure.

## Project Structure

- **Controllers**: Contains the application controllers
  - `HomeController.cs`: Handles requests for the home page and privacy page
- **Models**: Contains the application data models
  - `ErrorViewModel.cs`: Model for error information
- **Views**: Contains the application views
  - `Home/Index.cshtml`: Landing page view
  - `Home/Privacy.cshtml`: Privacy policy view
  - `Shared/_Layout.cshtml`: Main layout template
  - `Shared/Error.cshtml`: Error page view
- **wwwroot**: Contains static files
  - `css/site.css`: Custom CSS styles
  - `js/site.js`: Custom JavaScript
  - `lib/`: Client-side libraries (Bootstrap, jQuery, etc.)

## Getting Started

### Prerequisites

- [.NET 9 SDK](https://dotnet.microsoft.com/download)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)

### Running the Application

1. Clone the repository
   ```
   git clone https://github.com/yourusername/WebApp.git
   ```

2. Navigate to the project directory
   ```
   cd WebApp
   ```

3. Restore dependencies
   ```
   dotnet restore
   ```

4. Run the application
   ```
   dotnet run
   ```

5. Open your browser and navigate to `https://localhost:5001` or `http://localhost:5000`

## Development Environment

The application is configured with development-specific settings in `appsettings.Development.json`. When running in development mode, detailed error information is displayed.

## Features

- Responsive design using Bootstrap
- MVC architecture
- Static file serving
- Error handling

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.