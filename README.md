# Pragmatic Clean Architecture Lesson 2

This project demonstrates the implementation of Clean Architecture principles in a .NET application.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Configuration](#configuration)
- [Build](#build)
- [Run](#run)

## Overview

This repository contains a sample project structured according to Clean Architecture principles. It includes multiple layers such as Core, Application, Infrastructure, and Client.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/lsantos2000/pragmatic-clean-architecture-lesson2.git
   cd pragmatic-clean-architecture-lesson2
   ```
2. Ensure you have [.NET 7.0 SDK](https://dotnet.microsoft.com/download/dotnet/7.0) installed.

## Configuration

1. Navigate to the `CleanArch/CleanArch.Client` directory.
2. Modify the `launchSettings.json` file to set the desired port or other settings:
   ```json
   {
     "profiles": {
       "CleanArch.Client": {
         "commandName": "Project",
         "commandLineArgs": "--port 7000",
         "launchBrowser": false
       }
     }
   }
   ```

## Build

1. Open a terminal and navigate to the root directory of the project.
2. Run the following command to build the solution:
   ```sh
   dotnet build
   ```

## Run

1. Navigate to the `CleanArch/CleanArch.Client` directory.
2. Run the application using the following command:
   ```sh
   dotnet run
   ```
3. The application will start and listen on the configured port (default is 7000).

You can now access the API endpoints, such as `http://localhost:7000/api/GetComments`, to interact with the application.
