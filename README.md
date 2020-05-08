# netcore-webapi

Basics of building a web API with ASP.NET Core.

see https://docs.microsoft.com/de-de/aspnet/core/tutorials/first-web-api?view=aspnetcore-3.1&tabs=visual-studio-code

# Configuration

The project is using the typical .NET Core system defined in the package Microsoft.Extensions.Configuration.

Differnet configuration providers are stacked, details see https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration/?view=aspnetcore-3.1

Like this, configuration could be taken from environment variables rather than from appsettings.Environment.json files.

appsettings.Environment.json files still could be used alteratively, the hosting environment is set by defining the ASPNETCORE_ENVIRONMENT environment variable, see also https://andrewlock.net/how-to-set-the-hosting-environment-in-asp-net-core/

