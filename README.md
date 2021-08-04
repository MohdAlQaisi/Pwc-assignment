# Pwc-assignment
Company ABC is looking to create a complaint management portal. Users will be able to register, login, send a complaint and check the status of the complaint.


# Prerequisites
1. .NET Core 5 or Later
2. Visual Studio 2019
3. SQL Server 2017 (Local Instance)
4. nodeJS latest version
5. @angular/cli ~12.1.1

# How To Run
1. Download solution.
2. Restore AppDb.bak.
3. Open the angular app then on the same path open cmd. 
   - Run command "npm install".
   - Run comman "ng server".
4. Run App.Api application on IIS(not iisExpress, angular app pointint to 'http://localhost/App.Api/api/').
5. users:
   - Username: "admin@app.com" Password:"P@ssw0rd" - Admin Role.
   - Username: "mohd@app.com" Password:"P@ssw0rd" - User Role.
