# SafePath - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_69b2b54c3d1a2f8c41d76816_user:oDknaEmAqRKDo0gYq%25HOBg6I%24%23%2ApG%21eP@ep-misty-bonus-akzotxtm.c-3.us-west-2.aws.neon.tech:5432/AppDB_69b2b54c3d1a2f8c41d76816?sslmode=require`

**Swagger API Tester URL:** /swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.
