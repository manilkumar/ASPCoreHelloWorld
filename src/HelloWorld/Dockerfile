FROM microsoft/aspnetcore:1.0.1
WORKDIR /app
COPY bin/Debug/netcoreapp1.0/publish /app
ENV ASPNETCORE_URLS http://*:5001
EXPOSE 5001
ENTRYPOINT /bin/bash -c "dotnet HelloWorld.dll"
