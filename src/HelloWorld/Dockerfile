FROM microsoft/aspnetcore:1.0.1
ENTRYPOINT ["dotnet", "HelloWorld.dll"]
ARG source=.
WORKDIR /app
EXPOSE 5001/tcp
COPY $source .
