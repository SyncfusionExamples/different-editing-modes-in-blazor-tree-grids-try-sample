# Different Editing Modes in Blazor Tree Grids - Try Sample

## Overview

This sample demonstrates editing functionality using the Syncfusion [Blazor TreeGrid](https://www.syncfusion.com/blazor-components`) component in a hosted Blazor WebAssembly application. The application displays hierarchical data in a TreeGrid and shows how editing can be enabled directly within the grid interface. Developers can use this sample as a starting point for implementing create, update, and delete workflows for hierarchical records while preserving parent-child relationships. The solution uses a hosted architecture with separate Client, Server, and Shared projects.

**Documentation**: https://blazor.syncfusion.com/documentation/treegrid/edit 

**Online example**: https://blazor.syncfusion.com/demos/tree-grid/inline-editing

## Key Features

- Demonstrates editing support in the Syncfusion TreeGrid component.
- Displays hierarchical data using parent-child relationships.
- Configures TreeGrid columns and binds data records to the grid.
- Shows how editing can be performed directly from the TreeGrid interface.
- Demonstrates editing workflows for hierarchical business records.
- Uses a hosted Blazor WebAssembly architecture with Client, Server, and Shared projects.
- `Pages/Index.razor` hosts the primary TreeGrid implementation.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file:

   `DifferentEditModes.sln`

3. Restore NuGet packages.
4. Build the solution.
5. Run the project using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory containing the solution.

```bash
dotnet restore
dotnet run
```

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official TreeGrid editing documentation: https://help.syncfusion.com/grid-sdk/blazor/tree-grid/editing/edit

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
