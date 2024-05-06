# Xbox Game Bar Widget Template

This repository provides a template for creating custom widgets for Xbox Game Bar. With this template, you can quickly get started with developing widgets to enhance the gaming experience for Xbox users.

## Development Environment

This project was developed using Visual Studio 2022 Community edition. Ensure you have this IDE installed for seamless development experience.

## Installation

To use this widget template, follow these steps:

1. Create a new repo from this template in the top right of this repo.
2. Clone or download your new repository to your local machine.
3. Open the solution file (`WidgetTemplate.sln`) in Visual Studio 2022.
4. Install the NuGet package listed in the [Prerequisites section](https://github.com/meltyli/WidgetTemplate/edit/master/README.md#getting-started).
5. You probably want to start out with editing Widget1.xaml file.

## Getting Started

1. Prerequisites:
- Visual Studio 2022 Community Edition (optional)
- Install the NuGet package Microsoft.Gaming.XboxGameBar for your project.
- Target a minimum of Windows 10 version 2004 (10.0 build 19041).
2. Implement Xbox Game Bar API calls to interact with the Game Bar environment.
3. Test your widget locally using Xbox Game Bar Developer Mode.
4. Deploy your widget to the Microsoft Store for distribution.

Refer to the official [Microsoft documentation](https://docs.microsoft.com/en-us/gaming/game-bar/) for detailed instructions on developing and deploying Xbox Game Bar widgets.

## Renaming Visual Studio Project Parts

These are the recommended files to rename the project (also look out for version number and author).

1. **Rename Namespace:**
   - Right-click project > Rename > Enter new name.

2. **Update Project Files:**

   Update all instances of the following using Find and Replace (Ctrl + Shift + H):
   1. `WidgetTemplate` > Replace with new name, eg. `MyWidget`.
   2. `Widget1` > Replace with new name, eg. `WidgetName` AND rename the file called "Widget1", eg. `WidgetName.xaml`.
   3. `widget1` > Replace with new name, eg. `widgetName`.
  
   **IMPORTANT: Check "Match case" when using find and replace.**

4. **Update Assembly Information:**
   - Rename the source folder (repo/WidgetTemplate) and solution file (WidgetTemplate.sln)
   - Update line 7 in the solution file: eg. `Project("{CB0B05F0-5107-42F6-83B2-16BAA5DD2D9B}") = "WidgetName", "src\WidgetName.csproj", "{EC5E77E8-A523-4658-9D73-D35C831C4810}"`
  
5. Debug/build the app to validate renaming
6. Push changes to remote

## Usage

This template provides a basic structure for creating Xbox Game Bar widgets. Customize the provided code according to your widget's requirements, including layout, functionality, and interaction with the Game Bar environment.

## License

This project is licensed under the [GNU General Public License v3.0](LICENSE). Feel free to use, modify, and distribute the code as per the terms of the license.

## Acknowledgements

Special thanks to the Xbox Game Bar development team at Microsoft for providing the tools and resources necessary for creating custom widgets. I've created this repo since the C# setup is not provided and Microsoft only refers to the samples.
