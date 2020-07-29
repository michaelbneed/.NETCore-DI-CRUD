README:

Place these files in your .NET Core startup.cs in the ConfigureServices method like so:

// Injectable data access service
services.AddScoped<IDbReadService, DbReadService>();
services.AddScoped<IDbWriteService, DbWriteService>();