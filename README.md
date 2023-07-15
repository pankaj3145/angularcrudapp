We have set up our MEAN Stack Angular app’s backend using Node js, Express js, Angular and MongoDB.

We have to start the backend server using given command, each command will be executed in separate terminal window.

Start Nodemon Server

In order to start nodemon server, first enter into the backend folder using given below command.

---> cd backend

Then run the following command to start the nodemon server.

---> npx nodemon server

Start Angular App

open src folder then cmd and then 

---> npm start

Pass the MongoDB database URL to the mongoose.connect(‘…’) method in the backend/index.js file.

--->  "mongodb://0.0.0.0:27017" note pass 0.0.0.0 instead of localhost

Check your Angular frontend on – http://localhost:4200

You can check your api url on – http://localhost:4000/api