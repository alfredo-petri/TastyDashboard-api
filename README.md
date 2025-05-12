# Tasty Dashboard API 

A backend API for a food delivery platform, integrated with a custom React frontend. 

The main goal is to use this existing API and integrate it with a frontend project developed by me using React.

---

## ℹ️ About the Project

Backend application for a food delivery system (similar to iFood/Uber Eats), with support for:

- Restaurant and customer registration
- Ratings and metrics
- Opening/closing restaurant status

---

## Technologies Used

- Bun
- ElysiaJS
- Drizzle ORM
- Docker
- TypeScript

---

## Running the Project

This project depends on Docker to set up the database.  
With Docker installed, clone the repository, install the dependencies, start the Docker containers, and run the application.

> You must also run the database migrations to create the tables, and execute the seed command to populate it with fake data.

```bash
bun i
docker compose up -d
bun migrate
bun seed
bun dev
```
---

## Frontend Integration
This API will be connected to a React frontend that I’m developing.

→ Link to the frontend repository: [TastyDashboard](https://github.com/alfredo-petri/TastyDashboard)


---

## Credits

This repository **is not my original work**. It was cloned purely for educational and demonstrational purposes.

All rights for the original code belong to the respective creators.

Original project by: [Rocketseat](https://github.com/rocketseat-education/pizzashop-api#).
