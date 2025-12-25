# Centralized Package Version Management

This project demonstrates the use of centralized package and version management in a .NET application. It leverages the [Central Package Management](https://learn.microsoft.com/en-us/nuget/consume-packages/central-package-management) feature provided by NuGet to simplify dependency management.

## Features
- **Centralized .NET Verion Management**: .NET verion manged in a single file (`Directory.Build.props`), ensuring consistancy across the projects.
- **Centralized Package Management**: All package versions are managed in a single file (`Directory.Packages.props`), ensuring consistency across the projects.
- **Simplified Dependency Updates**: Updating a package version in the central file automatically applies the change to all projects in the solution.
- **Improved Maintainability**: Reduces duplication and ensures that all projects use the same version of a package.
