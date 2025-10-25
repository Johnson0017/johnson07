📝 Blog Site with Comment Section

A simple and interactive blog website that allows users to read articles and share their thoughts through a built-in comment section. This project demonstrates how frontend and backend components can work together to store, display, and manage comments in real time.

🚀 Features

📰 Displays blog posts with title, author, and publication date.

💬 Interactive comment section for each post.

💾 Comments stored and retrieved dynamically (localStorage or backend).

🧭 Responsive layout for desktop and mobile users.

⚡ Real-time comment updates without page reload.

🛠 Technologies Used
Frontend  - HTML, CSS, JavaScript

🧩 How It Works

The blog post content is displayed dynamically in the main section.

A comment form lets users enter their name and message.

When submitted, the comment is either:

Saved in localStorage (static version), or

Sent to a backend API (Node/Express + MongoDB) for storage.

All comments are fetched and rendered instantly below the post.

Users can refresh or revisit the page — the comments persist.

💡 Challenges Faced & Solutions

Challenge 1: Maintaining comment data without a database.
Solution: Used browser localStorage to temporarily store user comments in the static version.

Challenge 2: Handling user input validation.
Solution: Added required form fields and trimmed empty or invalid entries before submission.

Challenge 3: Keeping the UI responsive on all screens.
Solution: Applied flexible CSS grid and media queries to adapt to various device widths.

Challenge 4: Managing real-time comment updates.
Solution: Used JavaScript DOM manipulation to dynamically append comments without reloading the page.
