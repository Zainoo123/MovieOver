# Movieover

Movieover is a web application designed for movie enthusiasts to create private chat rooms, discuss their favorite films, and connect with other movie lovers. This app leverages the Chat Engine API for its chat functionalities and is built using Next.js, JavaScript, and CSS.

This project was created as part of the ALX School curriculum and a movie club community initiative.

## Features
- Real-time chat functionality for movie discussions.
- Create, join, and manage private chat rooms.
- User authentication with username and password.

## Screenshots
[Authentication Page](<public/MovieOver's screenshot of the auth form.PNG>)
*Authentication Page: Users can sign up with a username and password to enter the chat rooms.*

[Chat Room](<public/screenshot of the chat.PNG>)
*Chat Room: Users can discuss their favorite movies in real-time.*

## Technologies Used
- CSS3
- JavaScript
- Next.js
- Chat Engine API

## Setup

### Prerequisites
1. Node.js and npm installed on your machine.
2. An account on [Chat Engine](https://chatengine.io/).

2. **Create a Chat Engine Account and Project:**
   - Go to [Chat Engine](https://chatengine.io/) and sign up for an account.
   - Create a new project and take note of your **Private Key** and **Project ID**.

3. **Configure API Keys:**
   - In `index.js`, set the private key in the headers:
     ```js
     { headers: {"Private-key": ''} }
     ```
   - In `chats.js`, set the project ID:
     ```js
     const projectID = '';
     ```

4. **Install Dependencies:**
   ```bash
   npm install
   ```

5. **Run the Development Server:**
   ```bash
   npm run dev
   ```
   This will start the development server on `localhost:3000`.

## Usage
Once the server is running, open your browser and navigate to `http://localhost:3000`. You can sign up with a username and password to enter the chat rooms, create new chat groups, and start discussing your favorite movies with others.

