# Parts Unlimited E2E Tests

This repository contains the end-to-end tests for the Parts Unlimited application.

## Requirements
- Visual Studio 2015
- .Net 4.5.1

## How to Build

```powershell
& "C:\Program Files (x86)\MSBuild\14.0\Bin\MSBuild.exe" PartsUnlimited.sln /t:Rebuild /p:Configuration=Debug /p:RestorePackages=true
```

## Contributing

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
