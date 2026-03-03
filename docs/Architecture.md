# URL Shortener — Architecture Notes
 
## Tech Stack
- Backend: TypeScript + Express
- Database: SQLite (simple, no external DB server needed)
- Frontend: React with Vite
- Testing: vitest + supertest
 
## Deployment
- Single Node.js process serving both API and static frontend
- SQLite file stored in ./data/ directory
 
## API Design
- RESTful, JSON request/response
- Short codes: 7-character alphanumeric (nanoid)
