# ExpandoObject-data-binding-with-EditTemplate-in-Blazor-DataGrid

This sample demonstrates how to bind the Syncfusion Blazor DataGrid to an `ExpandoObject` and use the `EditTemplate` feature to dynamically render a custom editor such as `SfTextBox`.

## Overview

In this example:

- The Grid is bound to a dynamic list of `ExpandoObject` items (`Orders`).

- The **CustomerID** column uses an `EditTemplate` to render a `SfTextBox` during edit operations.

- Changes made to the textbox are tracked using the `ValueChange` event and updated during the `RowUpdating` event.

- `ExpandoObject` allows flexible, dynamic property management without predefined model classes.

## Getting Started

### Prerequisites

- [.NET 6.0 SDK or later](https://dotnet.microsoft.com/en-us/download)
- [Visual Studio 2022](https://visualstudio.microsoft.com/) or any IDE that supports Blazor
- Syncfusion Blazor NuGet packages

### Project Setup

1. Clone the repository:

   ```bash
    git clone https://github.com/SyncfusionExamples/ExpandoObject-data-binding-with-EditTemplate-in-Blazor-DataGrid.git
   ```
2. Navigate to the project folder:

    ```bash
    cd ExpandoObject-data-binding-with-EditTemplate-in-Blazor-DataGrid
    ```
3. Restore the NuGet packages:

    ```bash
    dotnet restore
    ```
4. Build and run the application:

    ```bash
    dotnet run
    ```
5. Open the browser at https://localhost:port (port varies).