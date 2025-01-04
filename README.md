# ASP.NET Core Template

## Package Installation

You can install this template using [NuGet](https://www.nuget.org/packages/AspNetCoreTemplate):

```powershell
dotnet new install .\TravelTech.Template
```

```powershell
dotnet new aspnet-core -n TravelTech.Template
```

## Pack this Template

```powershell
dotnet pack .\nuget.csproj
```

## Push to nuget

```powershell
 nuget push "TravelTech.Template.0.0.1.nupkg" -apikey "youre key" -Source "https://api.nuget.org/v3/index.json"
```

## License

This project is licensed with the [MIT license](LICENSE).
