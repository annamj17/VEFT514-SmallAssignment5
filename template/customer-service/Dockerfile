FROM mcr.microsoft.com/dotnet/core/sdk:2.2

LABEL maintainer="Anna Margret"

ENV ASPNETCORE_URLS=http://+:80

COPY . /app
WORKDIR /app/customer-service
RUN dotnet restore
ENTRYPOINT [ "dotnet", "run" ]