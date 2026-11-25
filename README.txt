EX-10: STUDENT MANAGEMENT REST API USING ASP.NET CORE

Requirements:
- .NET 8 SDK
- Visual Studio 2022 or VS Code

Run using Visual Studio:
1. Extract the ZIP file.
2. Open StudentManagementAPI.csproj in Visual Studio.
3. Allow NuGet package restore.
4. Press F5 or Ctrl+F5.
5. Swagger opens at the /swagger URL.

Run using terminal:
1. Open a terminal in this folder.
2. Run: dotnet restore
3. Run: dotnet run
4. Open the Swagger URL printed in the terminal.

Endpoints:
GET     /api/students       Get all students
GET     /api/students/1     Get student by ID
POST    /api/students       Add a student
PUT     /api/students/1     Update a student
DELETE  /api/students/1     Delete a student

Sample POST JSON:
{
  "name": "Abhay Kumar",
  "email": "abhay@gmail.com",
  "course": "BTech",
  "age": 22
}

This is an in-memory demonstration. Data is reset when the application restarts.
Custom middleware logs request method, path, and response status in the application console.
