dotnet new xunit -o webapp.Tests

 dotnet tool install --global dotnet-aspnet-codegenerator

dotnet aspnet-codegenerator razorpage -m Student -dc webapp.Data.RazorClubContext -udl -outDir Pages/Students --referenceScriptLibraries -sqlite


