# Cretaceous Park

#### By Cristina Plesa

#### A C# application that uses an API call.

## Technologies Used

* C#
* Entity Framework
* Identity
* .NET 5 SDK
* VS Code
* MySQL Workbench
* License
* MIT License.

## Setup and Use

### Prerequisites

* .NET 5 SDK
* MySQL Workbench
* A text editor like VS Code
* A command line interface like Terminal or GitBash to run and interact with the console app.

### Installation

1. Clone the repository: $ git clone {https://github.com/CristinaPlesa/CretaceousPark.Solution}
2. Navigate to the {CretaceousPark.Solution} directory on your computer
3. Open with your preferred text editor to view the code base

4. To run the console app:
  * Navigate to {CretaceousPark.Solution/CretaceousPark} in your command line
  * Run the command dotnet restore to restore the dependencies that are listed in {CretaceousPark.csproj}
  * Run the command dotnet build to build the project and its dependencies into a set of binaries
  * Finally, run the command dotnet run to run the project!
  * Note: dotnet run also restores and builds the project, so you can use this single command to start the console app

5. Add an appsettings.json file to the CretaceousPark.Solution/CretaceousPark directory and add the following:
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=cretaceous_park;uid=root;pwd=YourPassword;"
  }
}

## Known Bugs

* No known bugs

## License

[MIT](https://opensource.org/licenses/MIT) Copyright (c) 2021 Cristina Plesa

## Contact Information

Please reach out through my GitHub account.
[github.com/CristinaPlesa](https://github.com/CristinaPlesa)