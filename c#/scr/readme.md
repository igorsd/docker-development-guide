1. RUN dotnet new webapp

	Add line to Program.cs file

                    webBuilder.UseUrls("http://*:5000");
					
	before UseStartup<Startup>();

2. RUN dotnet build

3. RUN dotnet run

4. Open Browser localhost:5000
