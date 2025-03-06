FROM mcr.microsoft.com/dotnet/aspnet:8.0-alpine3.20

EXPOSE 8080

WORKDIR /app
COPY . .

ENTRYPOINT [ "dotnet", "#WEBAPI_DLL#" ]