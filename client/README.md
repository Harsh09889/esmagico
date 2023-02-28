# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## What are the things that i have implemented :

- JWT User Authentication, I have implemented not only the token based authentication but also there is expiry of the token after which refresh token is used by default in order to get a new token and thus the application works fine.

- Email based Authentication i have done using nodemailer but it is not completely implemented as it required an account that does not have 2FA but i had to set it up and because of the time constraint i was not able to test it 

- all the requirements i have checked and they are working fine

- User is landed on the page where is asked to authenticate themselves as an Admin or User

- choosing one of the options user can continue and register or login themselves as per the requirement and after that they are redirected to their respective panel

- protected routes have been implemented and they can switch back forth 

- this project uses backend for most of the functionalities and in backend i have implemented routes and middlewares to authorize user,admin and so on.

- MVC pattern have been used in order to keep the structure of the application clean and tidy

In the project directory, you can run:

### `npm install`

To install all the dependencies required to run the app.

### Adding .env file

I have already given my .env file so it should work fine but in any case it does not then you may have to add your credentials

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

