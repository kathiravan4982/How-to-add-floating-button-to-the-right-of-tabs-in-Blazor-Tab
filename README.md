# How to Add a Floating Button to the Right of Tabs in Blazor Tab

## Overview

This sample demonstrates how to display a floating button on the right side of the tab header area in the Syncfusion [Blazor Tabs](https://www.syncfusion.com/blazor-components/blazor-tabs) component. The application uses the Blazor Tabs component together with a Syncfusion Blazor Button component to position the button alongside the tab headers and add a new tab when the button is clicked. This approach provides users with a prominent action control without placing it inside an individual tab's content area.

## Key Features

- Uses the Syncfusion Blazor `SfTab` component to display content in separate tabs.
- Uses `TabItems` to define the collection of tabs rendered by the component.
- Uses individual `TabItem` components to define the initial content tab and the button tab.
- Defines the visible text for the initial tab using the `TabHeader` component.
- Uses the Syncfusion Blazor `SfButton` component to provide the floating button.
- Uses `HeaderTemplate` to render the button alongside the tab headers.
- Handles the button click through the `@onclick` event.
- Uses the `AddTab` method to add a new tab when the button is clicked.
- Keeps the button separate from the content displayed within individual tabs.
- Provides a convenient action that remains accessible alongside the tab headers.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file:

   `AddFloatingButton.sln`

3. Restore the NuGet packages by rebuilding the solution.
4. Set the startup project to:

   `AddFloatingButton`

5. Build the solution.
6. Run the application using `Ctrl+F5`.
7. Open the application URL displayed by Visual Studio after launch.
8. Verify that the floating button is displayed on the right side of the tab header area.

**Visual Studio Code**

1. Clone or download this repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the project directory:

```bash
cd How-to-add-floating-button-to-the-right-of-tabs-in-Blazor-Tab
```

5. Restore the NuGet packages:

```bash
dotnet restore
```

6. Run the project:

```bash
dotnet run
```

7. Open the local URL displayed in the terminal after the application starts.
8. Verify that the floating button is displayed on the right side of the tab header area.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation: [Blazor Tabs getting started documentation](https://blazor.syncfusion.com/documentation/tabs/getting-started)

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.