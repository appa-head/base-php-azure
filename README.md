# PHP Azure App

## Overview
This project is a simple PHP application designed to be deployed on Azure Web Apps. It serves as a demonstration of how to set up a PHP application with continuous integration and deployment using Azure Pipelines.

## Project Structure
```
php-azure-app
├── src
│   └── index.php        # Entry point for the PHP application
├── azure-pipelines.yml   # Azure Pipeline configuration for CI/CD
└── README.md             # Documentation for the project
```

## Setup Instructions

1. **Clone the Repository**
   Clone this repository to your local machine using:
   ```
   git clone <repository-url>
   ```

2. **Install PHP**
   Ensure you have PHP installed on your machine. You can download it from [php.net](https://www.php.net/downloads).

3. **Run the Application Locally**
   Navigate to the `src` directory and run the PHP built-in server:
   ```
   cd src
   php -S localhost:8000
   ```
   You can access the application at `http://localhost:8000`.

## Usage
- The `index.php` file serves as the entry point for the application. You can modify this file to change the content displayed by the application.

## Continuous Integration and Deployment
This project uses Azure Pipelines for continuous integration and deployment. The `azure-pipelines.yml` file contains the configuration for building and deploying the application to Azure Web Apps.

## Contributing
Feel free to submit issues or pull requests for any improvements or bug fixes.