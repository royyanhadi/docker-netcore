FROM mcr.microsoft.com/dotnet/core/aspnet:2.2 AS runtime
WORKDIR /app
ENV TZ=Asia/Jakarta
COPY /app ./
ENTRYPOINT ["dotnet", "YourApplication.dll"]