# ChatApp

## Overview
**ChatApp** is a real-time chat application developed using C# for the backend and Angular for the frontend. It provides users with a seamless messaging experience, enabling them to connect, communicate, and collaborate in a secure and user-friendly environment. The application supports one-on-one chats, group conversations, and offers various features to enhance user interaction.

## Table of Contents
- [Features](#features)
- [Architecture](#architecture)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features
- **Real-time Messaging**: Instant messaging capabilities using WebSockets for real-time communication.
- **User Authentication**: Secure login and registration process with JWT (JSON Web Tokens).
- **Group Chats**: Create and manage group conversations with multiple participants.
- **Message History**: View and retrieve chat history for previous conversations.
- **Responsive Design**: Mobile-friendly UI that adapts to different screen sizes.
- **Emojis and Media Sharing**: Support for sending emojis and sharing images within chats.

## Architecture
The ChatApp follows a client-server architecture:
- **Frontend**: Developed in Angular, providing a dynamic and responsive user interface.
- **Backend**: Built with ASP.NET Core, handling API requests, user authentication, and message management.
- **Database**: Uses SQL Server for storing user data, chat history, and group information.

## Technologies Used
- **Frontend**: Angular, TypeScript, HTML, CSS
- **Backend**: ASP.NET Core, C#
- **Database**: SQL Server
- **Real-time Communication**: SignalR
- **Authentication**: JWT (JSON Web Tokens)
- **Development Tools**: Visual Studio, Visual Studio Code

## Installation
To install and run ChatApp, follow these steps:

### Prerequisites
- [.NET SDK](https://dotnet.microsoft.com/download)
- [Angular CLI](https://angular.io/cli) (install using `npm install -g @angular/cli`)

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/chatapp.git
   cd chatapp
