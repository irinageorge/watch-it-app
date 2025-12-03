# Watch-It 🍿🎬

A modern **movie and TV show discovery app** built with **React**.  
Search, explore, and save your favorite titles with a clean and responsive interface.

👉 Live Demo: [watch-it-app.vercel.app](https://watch-it-app.vercel.app)

---

## 📖 Features
- Browse trending movies and TV shows
- Search by title
- View detailed information (poster, description, release date, rating)
- Responsive design for desktop and mobile
- Built with **React** and styled components
- API integration for real-time data

---

## ⚙️ Installation

Follow these steps to run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/irinageorge/watch-it-app.git
   cd watch-it-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   - Create a `.env` file in the root directory
   - Add your API key (for example, from [The Movie Database](https://www.themoviedb.org/documentation/api)):
     ```
     REACT_APP_API_KEY=your_api_key_here
     ```

4. **Run the development server**
   ```bash
   npm start
   ```

5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

---

## 🚀 Usage

- Use the search bar to find movies or TV shows.
- Click on a title to view details such as description, release date, and rating.
- Explore trending content on the homepage.
- Extend functionality by customizing API calls in `src/api.js`.

---

## 📂 Project Structure

```
watch-it-app/
├── public/              # Static assets
├── src/                 # Source code
│   ├── components/      # React components (SearchBar, MovieCard, etc.)
│   ├── pages/           # Page views (Home, Details)
│   ├── api.js           # API integration
│   ├── App.js           # Main app logic
│   ├── index.js         # Entry point
│   └── styles.css       # Styling
├── package.json         # Dependencies & scripts
├── README.md            # Project documentation
└── .env.example         # Example environment variables
```

---

## 📜 License

This project is licensed under the MIT License.  
You are free to use, modify, and distribute it with attribution.

---

## 👩‍💻 Author

Developed by **Irina George**  
GitHub: [@irinageorge](https://github.com/irinageorge)

Would you like me to also add a **screenshots section** so users can visually preview the app interface directly in the README?

