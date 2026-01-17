# YouTube Clone

A YouTube interface clone built with pure HTML and CSS, replicating the YouTube user interface and experience.

## 📋 Description

This project is a YouTube interface clone with the following main components:
- Header with search bar and navigation buttons
- Sidebar with navigation menu
- Video grid displaying a list of videos with thumbnails, channel information, and statistics

## ✨ Features

- **Header**
  - YouTube logo
  - Search bar with search button and voice search
  - Upload button, YouTube apps, notifications (with badge count)
  - User avatar

- **Sidebar**
  - Navigation menu: Home, Shorts, Subscriptions, You
  - Hover effects

- **Video Grid**
  - Displays 12 sample videos
  - Each video card includes:
    - Thumbnail with video duration
    - Channel profile picture
    - Video title (with link)
    - Channel name (with link)
    - View count and upload date

- **Responsive Design**
  - Optimized for desktop (3 columns)
  - Tablet (2 columns)
  - Mobile (1 column, sidebar and search bar hidden)

## 🛠️ Technologies Used

- **HTML5** - Web page structure
- **CSS3** - Styling and layout
  - Flexbox
  - CSS Grid
  - Media Queries for responsive design
- **Google Fonts** - Roboto font

## 📁 Project Structure

```
youtube-clone/
│
├── index.html              # Main HTML file
├── styles/                 # CSS files directory
│   ├── style.css          # General CSS
│   ├── header.css         # Header CSS
│   ├── sidebar.css        # Sidebar CSS
│   └── video.css         # Video grid CSS
│
├── icons/                 # SVG icons directory
│   ├── youtube-logo.svg
│   ├── hamburger-menu.svg
│   ├── search.svg
│   ├── voice-search-icon.svg
│   ├── upload.svg
│   ├── youtube-apps.svg
│   ├── notifications.svg
│   ├── home.svg
│   ├── youtube-shorts.svg
│   ├── subscription.svg
│   └── user.svg
│
├── thumbnails/           # Video thumbnails directory
│   ├── thumbnail-1.webp
│   ├── thumbnail-2.webp
│   └── ...
│
├── channel-profile-pics/ # Channel profile pictures directory
│   ├── channel-1.jpeg
│   ├── channel-2.jpeg
│   ├── profile.jpg
│   └── ...
│
├── .gitignore            # Gitignore file
└── README.md            # This README file
```

## 🚀 Getting Started

1. **Clone the repository or download the project**
   ```bash
   git clone <repository-url>
   cd youtube-clone
   ```

2. **Open the `index.html` file**
   - Open `index.html` directly in your web browser
   - Or use Live Server extension in VS Code
   - Or run a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (if you have http-server)
     npx http-server
     ```

3. **Access the application**
   - If opened directly: `file:///path/to/youtube-clone/index.html`
   - If using a server: `http://localhost:8000`

## 📱 Responsive Breakpoints

- **Desktop**: > 1140px - Displays 3 video columns
- **Tablet**: 481px - 1140px - Displays 2 video columns
- **Mobile**: ≤ 480px - Displays 1 video column, sidebar and search bar hidden

## 🎨 Design Features

- Color scheme and layout similar to YouTube
- Hover effects on buttons and links
- Tooltips when hovering over buttons
- Border radius and shadows for depth
- Typography using Roboto font

## 📝 Notes

- This is a static front-end project with no backend functionality
- Video links point to real YouTube videos
- Video data is sample data (hardcoded)
- No actual search functionality

## 🔮 Future Improvements

- Add JavaScript for search functionality
- Connect to YouTube API for real video data
- Add video playback functionality
- Add dark mode
- Add login/registration functionality
- Add like, comment, and share features

## 📄 License

This project is created for educational and demonstration purposes.

---

**Note**: This is an interface clone, not a full-featured YouTube replica. The project is still in development.
