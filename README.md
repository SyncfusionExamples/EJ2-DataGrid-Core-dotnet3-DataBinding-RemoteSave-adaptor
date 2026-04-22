# EJ2-Grid-Core-dotnet3-DataBinding-RemoteSave-adaptor

## Repository Description

This repository demonstrates how to bind a Syncfusion EJ2 Grid to remote data sources in an ASP.NET Core 3 application using the RemoteSaveAdaptor for performing CRUD operations.

## Project Overview

This sample showcases server-side data binding for the Syncfusion EJ2 Grid component using a URL-based adaptor. It focuses on implementing remote insert, update, and delete operations while maintaining a responsive and editable Grid UI. The project is designed to help developers understand how to integrate Syncfusion EJ2 Grid with ASP.NET Core 3 when Json.NET is not included by default.

The Grid is configured with paging, toolbar actions, validation rules, and column formatting. Data is supplied through a JSON source and persisted to the server via dedicated controller endpoints.

## Features

- Remote data binding using RemoteSaveAdaptor  
- Full CRUD operations (Add, Edit, Delete, Update, Cancel)  
- Paging support for improved data navigation  
- Column-level validation and formatting  
- Numeric and currency column editing  
- Primary key configuration for data integrity  

## Prerequisites

- ASP.NET Core 3.x  
- Syncfusion EJ2 ASP.NET Core components  
- Basic knowledge of MVC pattern  

## Usage

The EJ2 Grid is configured with editing and paging enabled. CRUD actions are handled through controller URLs defined in the DataManager configuration. This setup allows seamless communication between the client-side Grid and server-side logic.

## Application Running Steps

1. Clone or download the repository
    ```
    git clone <repository-url>
    ```
2. Build and run the application
    ```
    dotnet build
    dotnet run
    ```

## Reference Documentation
 
- [Getting started with ASP.NET CORE Grid](https://ej2.syncfusion.com/aspnetcore/documentation/grid/getting-started-core) 
- [Remote Data Binding](https://ej2.syncfusion.com/aspnetcore/documentation/grid/data-binding/remote-data)
- [Remote Save Adaptor](https://ej2.syncfusion.com/aspnetcore/documentation/grid/connecting-to-adaptors/remote-save-adaptor)
- [API Reference](https://help.syncfusion.com/cr/aspnetcore-js2/syncfusion.ej2.grids.grid.html)