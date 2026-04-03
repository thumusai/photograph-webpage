# photograph-webpage
I Created Photograph Webpage using HTML and CSS
🍔 Sidebar Menu Project
A responsive sidebar navigation menu built with HTML & CSS only — no JavaScript needed!
Built as part of learning Web Development at Apna College 🎓


✨ Features

🍔 Hamburger Menu — Click ☰ to open the sidebar
✕ Close Button — Click ✕ to close the sidebar
🎨 Beautiful Background — Full screen background image
📱 Smooth Animation — Sidebar slides in and out smoothly
🔗 Social Media Icons — Facebook, Twitter, Instagram, YouTube
✨ Hover Effects — Menu items highlight on hover
💡 Pure CSS Trick — No JavaScript used at all!


🛠️ Built With

HTML5 — Structure
CSS3 — Styling & Animations
Font Awesome 6 — Icons
Google Fonts (Poppins) — Typography


📁 Project Structure
sidebar-menu/
│
├── index.html       # Main HTML file
├── practise.css     # All CSS styles
├── photo.jpg        # Background image
└── README.md        # Project documentation

🚀 How to Run

Clone the repository

bashgit clone https://github.com/YourUsername/sidebar-menu.git

Open the folder

bashcd sidebar-menu

Open in browser

Just double click index.html
OR
Right click → Open with Live Server in VS Code
No installations needed! ✅

💡 How It Works (The CSS Trick!)
Hidden Checkbox   →  Acts as ON/OFF switch
Label (☰ button)  →  Clicking toggles checkbox
Label (✕ button)  →  Also toggles same checkbox
CSS :checked      →  Detects if checkbox is ON
Sidebar slides    →  left:-300px → left:0
css/* The magic line! */
#check:checked ~ .sidebar_menu {
    left: 0;   /* slides sidebar into view */
}
No JavaScript — just pure CSS magic! 🪄

🎨 Menu Items
IconLink🖼️Gallery⚡Shortcuts🎬Exhibits📅Events🏪Store📞Contact💬Feedback

🐛 Bugs Fixed During Development

✅ Fixed missing : in CSS properties
✅ Fixed absoulte typo → absolute
✅ Fixed missing semicolons
✅ Fixed wrong class selectors .sidebar_menu.logo → .sidebar_menu .logo
✅ Fixed background image not appearing
✅ Fixed sidebar always visible (left: 0 → left: -300px)
✅ Fixed missing closing HTML tags


🌱 Future Improvements

 Add smooth dark/light mode toggle
 Make fully responsive for all screens
 Add active state for menu items
 Add more pages to navigate to
 Add JavaScript for extra animations


🙌 Acknowledgements

Built while learning HTML & CSS at Apna College 🎓
Icons by Font Awesome
Font by Google Fonts
Background photo — personal collection 📷




📄 License
This project is open source and free to use for learning purposes.
