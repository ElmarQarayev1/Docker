FROM mcr.microsoft.com/dotnet/sdk:7.0

WORKDIR /app

COPY . .

RUN dotnet build -c Release 

ENTRYPOINT ["dotnet","run", "--no-launch-profile"]