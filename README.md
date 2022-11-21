# TikTok Clone Backend

## Description
Backend of the TikTok clone developed in NodeJS and SQLite. 

## Installation steps
1. Clone the proyect with the command `git clone https://github.com/CarlosAlbertoR/TikTokClone_Backend.git` 
2. Install sequelize-cli globally with the command `sudo npm install -g sequelize-cli`
3. Install the dependencies required for the execution of the project with the command `npm install`
4. Install the required migrations of sequelize-cli with the command `sequelize-cli db:migrate`
5. Log in to [api.video](https://api.video/) and copy the ApiKey.
6. In the main folder create a file named `.env` 
6. In the main folder create a folder named `uploads` 
7. In the .env file replace the value of the variables 
   ~~~
   VIDEO_API_API_KEY=Yor API KEY
   JWT_SECRET=Your Token by The JWT (It's random)
   ~~~
8. Run the server with `npm run start`