# SmartBook – Book Recommendation System

SmartBook is a modern, responsive **Book Recommendation System** created as a BCA college project. It recommends books based on user preferences such as genre, language, author, reading level, and book length.

## Features

- User preference input
- Preferred language selection
- Favourite author input
- Reading-level selection
- Preferred book length
- Multiple genre selection
- Personalized recommendation generation
- Recommendation matching score
- Book ratings and details
- Search books by title, author, or genre
- Add/remove favourite books
- Personal book rating (1–5 stars)
- Reading dashboard
- Browser Local Storage for saving preferences, favourites, and ratings
- Responsive design for mobile, tablet, and desktop

## Technologies Used

- **HTML5** – Website structure
- **CSS3** – Styling, responsive layout, animations, and UI design
- **JavaScript** – Recommendation logic and interactive features
- **Local Storage** – Saves user preferences, favourites, and ratings in the browser

## Project Structure

```text
SmartBook/
├── index.html
├── style.css
├── script.js
└── README.md
```

## How the Recommendation System Works

SmartBook uses a simple **content-based scoring algorithm**.

The system compares the user's preferences with each book:

- Genre match → **+5 points**
- Favourite author match → **+4 points**
- Language match → **+3 points**
- Reading-level match → **+2 points**
- Book-length match → **+1 point**

Books are sorted according to their matching score. If two books have the same score, their rating is used to determine the order.

## How to Run the Project

### Method 1 – Directly in a browser

1. Extract the `SmartBook` folder.
2. Open the folder.
3. Double-click `index.html`.
4. The website will open in your browser.

### Method 2 – Using VS Code

1. Open the `SmartBook` folder in Visual Studio Code.
2. Open `index.html`.
3. Run it using **Live Server** if the extension is installed.
4. Open the displayed local website in your browser.

## How to Use

1. Enter your name.
2. Select your preferred language.
3. Enter a favourite author if desired.
4. Select reading level and book length.
5. Choose one or more genres.
6. Click **Generate Recommendations**.
7. View the recommended books and their matching scores.
8. Use **View Details** to see book information.
9. Add books to **My Favourites**.
10. Give books your own rating using the star buttons.
11. Use the search box to find books by title, author, or genre.

## Data Storage

SmartBook uses browser **Local Storage**. The following information is stored locally:

- `smartbook_preferences` – User preferences
- `smartbook_favourites` – Favourite book IDs
- `smartbook_ratings` – User ratings

No backend server or database is required for this version.

## Sample Book Categories

The project includes books from categories such as:

- Fiction
- Romance
- Mystery
- Thriller
- Fantasy
- Science Fiction
- Self-Help
- Psychology
- History
- Biography
- Education

It also includes selected English, Marathi, and Kannada books.

## Project Objective

The objective of SmartBook is to demonstrate how a simple web application can use user preferences and a basic recommendation algorithm to provide personalized book suggestions.

## Future Enhancements

The project can be extended with:

- Login and user accounts
- Online database
- More books and genres
- Real book-cover images
- API integration such as Google Books API
- AI/ML-based recommendations
- Book reviews and comments
- Reading progress tracking
- Dark mode
- Admin panel for adding books

## BCA Project

**Project Name:** SmartBook – Book Recommendation System  
**Project Type:** BCA Web Development Project  
**Frontend:** HTML, CSS, JavaScript  
**Storage:** Browser Local Storage
