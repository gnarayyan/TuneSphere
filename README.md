# TuneSphere

Welcome to TuneSphere, a dynamic music player app that allows users to explore, stream, and discover their favorite tunes! This project features a Flutter frontend and a FastAPI backend, providing a smooth and efficient user experience.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Architecture](#architecture)
- [Installation](#installation)
  - [Frontend (Flutter)](#frontend-flutter)
  - [Backend (FastAPI)](#backend-fastapi)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Authentication**: Secure login and registration.
- **Music Streaming**: Listen to a wide variety of songs.
- **Playlist Creation**: Create and manage your own playlists.
- **Search Functionality**: Easily find tracks, albums, and artists.
- **Responsive Design**: Optimized for both mobile and tablet devices.

## Technologies

- **Frontend**: Flutter
- **Backend**: FastAPI
- **Database**: PostgreSQL (or your choice of database)
- **State Management**: Provider / Riverpod (or your choice)
- **Deployment**: Docker, AWS, or Heroku (optional)

## Architecture

The application follows a client-server architecture:

- **Frontend (Flutter)**: Provides a responsive and user-friendly interface.
- **Backend (FastAPI)**: Handles API requests, authentication, and data management.

## Installation

### Frontend (Flutter)

1. Make sure you have Flutter installed on your machine. Follow the [Flutter installation guide](https://flutter.dev/docs/get-started/install) if needed.
2. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/tunesphere.git
   cd tunesphere/frontend
   ```
3. Install dependencies:
   ```bash
   flutter pub get
   ```
4. Run the app:
   ```bash
   flutter run
   ```

### Backend (FastAPI)

1. Ensure you have Python 3.7+ installed.
2. Navigate to the backend directory:
   ```bash
   cd tunesphere/backend
   ```
3. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Run the FastAPI server:
   ```bash
   uvicorn main:app --reload
   ```

## Usage

1. Open the Flutter app on your device or emulator.
2. Register or log in to your account.
3. Start exploring music, creating playlists, and enjoying your favorite tracks!

## Contributing

We welcome contributions! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Thank you for checking out TuneSphere! We hope you enjoy using the app as much as we enjoyed building it.
