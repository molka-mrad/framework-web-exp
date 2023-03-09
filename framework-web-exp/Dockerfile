FROM mcr.microsoft.com/dotnet/aspnet:7.0
COPY bin/Release/net7.0/publish/ /inetpub/wwwroot
WORKDIR /inetpub/wwwroot
ENTRYPOINT ["dotnet", "MyWebApplication.dll"]
