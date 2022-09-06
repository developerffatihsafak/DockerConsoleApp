FROM mcr.microsoft.com/dotnet/runtime:3.1
WORKDIR /appcore
COPY  /bin/Release/netcoreapp3.1/publish /appcore/
ENTRYPOINT ["dotnet","CoreDocker.dll"]