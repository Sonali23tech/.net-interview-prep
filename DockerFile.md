Docker instructions-

FROM -provides base image
WORKDIR -all commands run from this workdirectory which is present in continer.
COPY - copy from source(local) to destination(container) copy . .
ENTRYPOINT - Run the application
Paths


dotnet restore myApp.csproj -> download nuget packages
dotnet build myApp.csproj -> build source code , create dlls 
dotnet publish myApp.csproj => deploy on the serviers 

--------------------------------------------------------------------------------
