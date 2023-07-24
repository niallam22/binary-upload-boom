# Binary upload boom

A CRUD photo sharing and social networking applicaiton.

![App login and upload](bub.gif?raw=true "Logging in and uploading image to app")

## About this project

This project is a fullstack CRUD application, built with MVC architecture.

Tech used: HTML, CSS, JavaScript, Express 

This app is rendered using .ejs templates and dynamically styled using Bootstrap 5.

Flash errors are used on the sig in/sign up forms to instruct users and control data entry.

MongoDB is used to store user sessions, encrypted user login information and uploaded user text content. 

Cloudinary api is used to store user uploaded photo content.

Authenticated users are able to access protected routes/views including user content.

## Optimisations and future work

1. Add comment feature to photos
2. Enable video upload/playback
3. Improve design aesthetic/branding

## Running Locally

# Install

`npm install`

---

# Things to add

- Create a `.env` file in config folder and add the following as `key = value`
  - PORT = 2121 
  - DB_STRING = `your database URI`
  - CLOUD_NAME = `your cloudinary cloud name`
  - API_KEY = `your cloudinary api key`
  - API_SECRET = `your cloudinary api secret`

---

# Run

`npm start`
