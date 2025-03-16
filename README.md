# Music-Controller-Web-App

A web application that allows users to collaboratively control music playback in a shared room. Users can vote to skip songs, set customized room sizes, and enjoy an interactive UI. Authentication is required before joining a room. Users can either join a room using a code or create a new room and share the music room code.

## Features
- **Vote-to-Skip**: If more than 50% of users vote to skip a song, it will be changed automatically.
- **Room Customization**: Set a custom room size for better control.
- **Interactive UI**: A seamless and engaging user experience.
- **Authentication**: Users must authenticate before joining a room.
- **Room Join & Creation**: Join a room with a unique code or create a new one and share the code with others.

---

## Setup Instructions

### Backend Setup (Django)
1. **Install Required Python Modules**
   ```sh
   pip install -r requirements.txt
   ```
2. **Navigate to the Django Project Directory**
   ```sh
   cd "music-room" 
   ```
3. **Start the Django Web Server**
   ```sh
   python manage.py runserver
   ```

### Frontend Setup (React)
1. **Install Node.js** *(Ensure you have Node.js installed before proceeding)*
2. **Navigate to the Frontend Folder**
   ```sh
   cd frontend
   ```
3. **Install Dependencies**
   ```sh
   npm install
   ```
4. **Compile the Frontend**
   - For production:
     ```sh
     npm run build
     ```
   - For development:
     ```sh
     npm run dev
     ```

---

## Technologies Used
- **Backend**: Django, Django REST Framework
- **Frontend**: React.js
- **Database**: SQLite (default, can be configured)
- **Authentication**: OAuth / Django Authentication System

---

## How to Use
1. Authenticate and log in.
2. Join a room using a room code or create a new room.
3. If you're in a room, you can vote to skip the currently playing song.
4. If over 50% of users vote to skip, the song will automatically change.
5. Enjoy the music experience with your friends!

---

## Contribution
Feel free to contribute to the project by opening issues or submitting pull requests!

---

## License
This project is licensed under the MIT License.

