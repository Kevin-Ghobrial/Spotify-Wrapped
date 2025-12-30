# Spotify-Wrapped

🎧 Spotify Wrapped Web App
A web application that recreates the Spotify Wrapped experience by visualizing a user’s listening data in a clean, interactive, and shareable format. Users can log in with Spotify, explore their top artists, tracks, and genres, and view personalized insights based on their listening habits.

🚀 Features
🔐 Spotify Authentication using OAuth
📊 Personalized Wrapped Summary
Top artists
Top tracks
Listening trends
🎨 Modern, responsive UI inspired by Spotify Wrapped
⚡ Fast and interactive data loading and transitions
📱 Mobile-friendly design

🛠️ Tech Stack
Frontend: React / Next.js (or replace with your actual framework)
Backend: Node.js / Express (if applicable)

API: Spotify Web API
Auth: Spotify OAuth 2.0
Styling: CSS / Tailwind / Styled Components (replace as needed)

🔑 Spotify API Setup
To run this project locally, you’ll need Spotify API credentials:
Go to the Spotify Developer Dashboard
Create a new app
Add a Redirect URI (e.g. http://localhost:3000/callback)
Copy your Client ID and Client Secret
Create a .env file in the root directory:

SPOTIFY_CLIENT_ID=your_client_id
SPOTIFY_CLIENT_SECRET=your_client_secret
REDIRECT_URI=http://localhost:3000/callback

▶️ Running Locally
# Install dependencies
npm install

# Start development server
npm run dev


Then open:
http://localhost:3000

📈 How It Works
User logs in with Spotify
App requests permission to read listening data
Spotify API returns user stats (top tracks, artists, etc.)
Data is processed and displayed as a “Wrapped” experience


📄 License
This project is for educational and personal use.
Spotify is a trademark of Spotify AB — this project is not affiliated with or endorsed by Spotify.
