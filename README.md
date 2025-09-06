# Personal Notes Web App

## Overview
This is a simple Personal Notes Web App built with Node.js and Express. The application allows users to add, display, and delete notes. Notes are stored persistently in a JSON file.

## Features
- Add new notes
- Display all notes
- Delete existing notes

## Project Structure
```
personal-notes-app
├── src
│   ├── app.js                # Entry point of the application
│   ├── routes
│   │   └── notes.js          # Routes for notes functionality
│   ├── controllers
│   │   └── notesController.js # Logic for handling notes
│   ├── models
│   │   └── notesModel.js      # Data persistence layer
│  
├── package.json               # npm configuration file
└── README.md                  # Project documentation
```

## Installation
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd personal-notes-app
   ```
3. Install the dependencies:
   ```
   npm install
   ```

## Usage
1. Start the server:
   ```
   npm start
   ```
2. Use a tool like Postman or curl to interact with the API:
   - **Add a note**: POST `/notes` with a JSON body containing the note.
   - **Get all notes**: GET `/notes`.
   - **Delete a note**: DELETE `/notes/:id` where `:id` is the note's identifier.

## License
This project is licensed under the MIT License.