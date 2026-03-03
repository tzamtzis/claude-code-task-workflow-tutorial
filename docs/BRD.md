# URL Shortener — Business Requirements Document
 
## Business Goal
We need an internal URL shortener so the marketing team can create
branded short links for campaigns and track how many people click them.
 
## User Stories
- As a marketer, I want to paste a long URL and get a short one back
- As a marketer, I want to see how many times each short link was clicked
- As a marketer, I want to see when and where clicks come from
- As a marketer, I want to optionally choose a custom short code
 
## Constraints
- Must be self-hosted (no third-party SaaS dependency)
- Must have a web dashboard (not just an API)
- Must handle at least 100 requests/second
- Budget: 1 developer-week
 
## Out of Scope (for now)
- User authentication / multi-tenancy
- QR code generation
- Link expiration
