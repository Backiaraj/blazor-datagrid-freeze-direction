# Blazor DataGrid Freeze Direction

This sample demonstrates how to freeze columns in both left and right directions using the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component.

## Overview

This is a Blazor web application that showcases the column freezing feature of the Blazor DataGrid component. The sample displays a data-rich grid with columns frozen at both the left and right edges, allowing users to scroll horizontally while maintaining visibility of critical columns like Order ID and Ship Country.

### Key Features

- **Left Freeze**: Lock columns on the left side of the grid (e.g., Order ID)
- **Right Freeze**: Lock columns on the right side of the grid (e.g., Ship Country)
- **Horizontal Scrolling**: Scroll through middle columns while keeping frozen columns visible
- **Responsive Layout**: Grid height of 364px with hover effects disabled
- **Column Sorting**: Built-in sorting support for enhanced data exploration
- **Formatted Data**: Currency formatting, date formatting, and text alignment

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-datagrid-freeze-direction.git
cd blazor-datagrid-freeze-direction
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/frozen-column

**Online example**: https://blazor.syncfusion.com/demos/datagrid/frozen-rows?theme=fluent2