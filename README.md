# Blazor DataGrid Freeze Direction

This sample demonstrates how to freeze columns in both left and right directions using the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component.

## Overview

This is a Blazor web application that showcases the column freezing feature of the Blazor DataGrid component. The sample displays a data-rich grid with columns frozen at both the left and right edges, allowing users to scroll horizontally while maintaining visibility of critical columns like Order ID and Ship Country.

### Key features

- **Left Freeze**: Lock columns on the left side of the grid (e.g., Order ID)
- **Right Freeze**: Lock columns on the right side of the grid (e.g., Ship Country)
- **Horizontal Scrolling**: Scroll through middle columns while keeping frozen columns visible
- **Responsive Layout**: Grid height of 364px with hover effects disabled
- **Column Sorting**: Built-in sorting support for enhanced data exploration
- **Formatted Data**: Currency formatting, date formatting, and text alignment

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2026](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Code](https://code.visualstudio.com/)

## Run with Visual Studio

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`FreezeDirection.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Checkout this project to a location in your disk.
* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

```bash
cd blazor-datagrid-freeze-direction
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## References

**Documentation**: https://help.syncfusion.com/grid-sdk/blazor/data-grid/frozen-column

**Online example**: https://blazor.syncfusion.com/demos/datagrid/frozen-rows?theme=fluent2