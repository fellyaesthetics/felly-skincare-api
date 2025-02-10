# felly-skincare-api
# Felly Skincare API

A Node.js backend API for the Felly Skincare application that provides personalized skincare advice using GPT-4 and handles contact form submissions.

## Features

- Personalized skincare advice using OpenAI's GPT-4
- Contact form submission handling with email notifications
- CORS enabled for secure cross-origin requests
- Built with Express.js and Node.js

## API Endpoints

- `POST /api/skincare-advice`: Get personalized skincare advice
- `POST /api/contact`: Submit contact form information

## Environment Variables Required

- `OPENAI_API_KEY`: OpenAI API key
- `EMAIL_USER`: Gmail address for sending notifications
- `EMAIL_PASS`: Gmail app password
- `PORT`: Server port (defaults to 3000)

## Tech Stack

- Node.js
- Express.js
- OpenAI GPT-4
- Nodemailer
