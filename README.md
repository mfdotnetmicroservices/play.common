# Play.Common

Common libraries used by Play Economy services.


# Create and publish package
### For Windows (PowerShell):
```powershell
$version="1.0.7"
$owner="mfdotnetmicroservices"
dotnet pack src\Play.Common\ --configuration Release -p:PackageVersion=$version -p:RepositoryUrl=https://github.com/$owner/play.common -o ..\packages 
```

### For macOS
```bash
version="1.0.7"
owner="mfdotnetmicroservices"
dotnet pack src/Play.Common/ --configuration Release -p:PackageVersion=$version -p:RepositoryUrl=https://github.com/$owner/play.common -o ../packages 
```