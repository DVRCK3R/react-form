# react-form

A lightweight React application for collecting and submitting user registration data. The form captures a first name, last name, date of birth, age, email address, and phone number, then sends the submitted data to a backend API and displays the records in a table.

## Features
- Modern React form UI
- Client-side validation
- Country-aware phone input
- API submission to a backend endpoint
- Submitted data table for viewing entries
- Routing between the form and a welcome/table view

## Tech Stack
- React
- React Router
- react-phone-input-2
- Create React App

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the app in development mode:
   ```bash
   npm start
   ```

3. Open the app in your browser at:
   ```text
   http://localhost:3000
   ```

## Notes
This project is designed to submit data to an API endpoint such as:
```text
http://localhost:5000/api/register
```

