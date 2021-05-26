* Install try-convert
* Install latest .net core sdk
```
dotnet tool install -g try-convert
```
* Go to ContosoUniversity directory
* Run try-convert
```
try-convert
```
* Choose your target .net core sdk

Commands:
dotnet tool install -g try-convert
try-convert

Result:
'C:\Project\ContosoUniversityCore\src\ContosoUniversityCore\ContosoUniversityCore.csproj' is already a .NET SDK-style project, so it won't be converted.
'C:\Project\ContosoUniversityCore\test\ContosoUniversityCore.UnitTests\ContosoUniversityCore.UnitTests.csproj' is already a .NET SDK-style project, so it won't be converted.
'C:\Project\ContosoUniversityCore\test\ContosoUniversityCore.IntegrationTests\ContosoUniversityCore.IntegrationTests.csproj' is already a .NET SDK-style project, so it won't be converted.
No projects converted.

Readings:
[Github try-convert](https://github.com/dotnet/try-convert)



