# Continnum
Microservice "Continue Watching", created using Node.js y Redis 🎬⌚


## Requeriments

- NodeJS v10+
- Redis


## Development

> git clone https://github.com/CinelarTV/Continnum.git

> cd Continnum

> npm install

> Start Redis locally or insert the needed keys into the .env file

> "npm start" to run the server



## Endpoints

- POST /position/{user-id}/{content-id}/{position} - Where "position" must be a numeric value

- GET /position/{user-id}/{content-id} - Get the last position of the user in a specific content

- GET /position/{user-id} - Get all positions for a specific user, newest first.



## Environment Vars

- NODE_ENV || if set to development there will be some logging made into the console
- REDIS_URL || local
- REDIS_PORT || (6379)
- REDIS_AUTH ||



---

If you have any suggestion or improvement do not hesitate to create an Issue or PR
