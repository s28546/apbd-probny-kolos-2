# apbd-probny-kolos-2

nuget packages:
Microsoft.AspNetCore.OpenApi
Microsoft.EntityFrameworkCore
Microsoft.EntityFrameworkCore.Design
Microsoft.EntityFrameworkCore.SqlServer
Swashbuckle.AspNetCore - to jest by default zawsze

entitites -> configs -> komendy 

config metody
https://learn.microsoft.com/en-us/ef/ef6/modeling/code-first/fluent/types-and-properties


dotnet ef migrations add init -> generuje migracje na podstawie dbcontextu i configow
-v -> sciana logow co co robi

dotnet ef migrations remove -> cofa ostatnia migracje, niezaaplikowana

dotnet ef database update -> aplikuje migracje na bazie danych

connection string w appsettings.json i builder.Services.AddDbContext<> w Program.cs
