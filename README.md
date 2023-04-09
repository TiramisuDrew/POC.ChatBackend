# Chat Backend

This repository contains the backend implementation for a chat application. The application demonstrates modern best practices in software development and includes features like real-time messaging, user search, and end-to-end encryption.

## Technologies

- ASP.NET Core
- Entity Framework Core
- SQLite
- Elasticsearch
- SignalR
- OpenPGP.js
- MediatR
- FluentValidation
- Microsoft Identity

## Features

- Real-time messaging using SignalR
- User search as you type
- End-to-end encryption of messages using OpenPGP.js
- Authorentication and Authorization using Microsoft Identity
  
## Setup

Install the required tools:
- .NET SDK
- Elasticsearch
- Clone the repository:
```bash
git clone https://github.com/your-username/chat-application-backend.git
```

Change to the project directory:
```bash
cd chat-application-backend
```


Update the appsettings.json file with your Elasticsearch connection string and other necessary configurations.

Run the application:  
```bash
dotnet run
```

  

The backend API will be available at http://localhost:5000