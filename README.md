# Red-Blocks-intern-assessment

Backend: ASP.NET Core API
- Run: Press F5 in Visual Studio
- URL: https://localhost:7191
- Endpoints: GET /api/tasks, POST /api/tasks

Frontend: React App
- Run: npm install then npm start
- URL: http://localhost:3000

Architecture:
1. API Layer - Controllers handle HTTP requests
2. Application Layer - Business logic in controller methods
3. Domain Layer - TaskItem model class
4. Infrastructure - In-memory list (simulated database)

Async Operations:
- Backend: Task.Delay simulates async database calls
- Frontend: Async fetch() for API communication

Time Constraints:
Built within 1 hour. Used simple in-memory storage instead of database
for quick demonstration. Full solution would include database and error handling.

To Test:
1. Run backend first (F5)
2. Run frontend (npm start)
3. Add tasks using form
4. See them appear in list
