# Play.Common

Common libraries used by Play Economy services.


# Create and publish package
### For Windows (PowerShell):
```powershell
$version="1.0.11"
$owner="mfdotnetmicroservices"
$gh_pat="[PAT HERE]"
dotnet pack src\Play.Common\ --configuration Release -p:PackageVersion=$version -p:RepositoryUrl=https://github.com/$owner/play.common -o ..\packages 

dotnet nuget push ..\packages\Play.Common.$version.nupkg --api-key $gh_pat --source "github"
```

### For macOS
```bash
version="1.0.11"
owner="mfdotnetmicroservices"
gh_pat="[PAT HERE]"
dotnet pack src/Play.Common/ --configuration Release -p:PackageVersion=$version -p:RepositoryUrl=https://github.com/$owner/play.common -o ../packages 

dotnet nuget push ../packages/Play.Common.${version}.nupkg --api-key ${gh_pat} --source "github"
```

