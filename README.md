🎵 YouTube Song Finder (HTML, CSS, JavaScript)

YouTube Song Finder ek simple web app hai jisme user sirf ek keyword likhta hai —
jaise “sad songs”, “motivational songs”, “romantic songs” — aur app YouTube API ke through top 5 videos fetch karke show karta hai.
Ye project pure frontend (HTML, CSS, JS) se bana hai — koi backend, Node.js, ya Python ki zarurat nahi. 🚀

🌟 Features

🔍 Search any type of songs (e.g. sad songs, romantic songs, party songs)

🎥 Shows top 5 YouTube videos using YouTube Data API v3

💻 Fully responsive and works directly in any browser

🎨 Simple and attractive UI with hover animation

⚡ No server required — runs in one single HTML file

🧩 Technologies Used

HTML5 — structure

CSS3 — design & responsiveness

JavaScript (ES6) — API calls & interactivity

YouTube Data API v3 — to fetch real video data

⚙️ How It Works

App uses YouTube Data API to search for videos based on the user's query.

It fetches the top 5 videos and displays their thumbnail, title, and watch link.

Clicking on the “Watch” button opens the YouTube video in a new tab.

🚀 How to Run

Clone or download this repository.

Open the folder and double-click on the file index.html.

That’s it! The app will open directly in your browser.

Type something like “sad songs” and enjoy the results.

🔑 Setup (Add Your YouTube API Key)

This project needs a YouTube Data API Key (free).
To get your own key:

Go to Google Cloud Console
.

Create a new project and enable YouTube Data API v3.

Create API credentials → copy your API key.

In index.html, replace the placeholder key:

const API_KEY = "YOUR_API_KEY_HERE";


✅ Done! Now you can fetch real YouTube results.

📸 Demo Preview

(You can add a screenshot here later)
Example search:

“Sad Songs” → shows top trending sad songs from YouTube with thumbnails & titles.

🧠 Future Enhancements

▶️ Play videos directly on the same page (embedded player)

🌙 Dark Mode toggle

💾 Save favorite songs locally

🔁 Pagination to show more than 5 videos

👨‍💻 Author

siddharth pandey

Siddharth Pandey
Created with ❤️ using HTML, CSS, and JavaScript
