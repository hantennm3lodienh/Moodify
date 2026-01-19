# Moodify

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Overview
Moodify is an intuitive web application that leverages AI to generate personalized music playlists tailored to your current mood. Whether you're feeling happy, sad, or energized, Moodify curates the perfect soundtrack to accompany your day.

## Features
- AI-driven mood detection via simple user input
- Vast music database integration for diverse playlist creation
- Clean, responsive interface for seamless user experience
- Save and share your favorite playlists

## Tech Stack
- Frontend: React.js
- Backend: Node.js, Express
- AI Mood Detection: TensorFlow.js
- Music API: Spotify Web API

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/hantennm3lodienh/Moodify.git
   ```
2. Navigate to the project directory:
   ```
   cd Moodify
   ```
3. Install dependencies for both client and server:
   ```
   npm install
   cd client
   npm install
   cd ..
   ```
4. Set up your environment variables for Spotify API credentials in a `.env` file:
   ```
   SPOTIFY_CLIENT_ID=your_client_id
   SPOTIFY_CLIENT_SECRET=your_client_secret
   ```
5. Run the development server:
   ```
   npm run dev
   ```

## Usage
1. Visit `http://localhost:3000` in your browser.
2. Input your current mood using the provided selector or text input.
3. Let Moodify generate a personalized playlist.
4. Save or share playlists with friends!

## Screenshots
![Homepage](https://via.placeholder.com/800x400?text=Moodify+Homepage)

![Playlist View](https://via.placeholder.com/800x400?text=Playlist+View)

## Contributing
Contributions are welcome! To contribute:
1. Fork this repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request on GitHub.

Please make sure to update tests as appropriate and follow the existing code style.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Author
Made with ❤️ by [hantennm3lodienh](https://github.com/hantennm3lodienh)
