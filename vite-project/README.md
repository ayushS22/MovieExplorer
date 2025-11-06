# 🎬 Movie Explorer

A simple and interactive **React.js** web application that allows users to **search, browse, and view detailed information** about movies using the **OMDb API** (The Open Movie Database).  
This project demonstrates concepts of **React routing, state management, API integration, and reusable components**.

---

## 🚀 Features

- 🔍 **Search movies** by title using the OMDb API  
- 🧭 **Browse trending movies** (default search: *Avengers*)  
- 📄 **View detailed movie information** including title, poster, genre, release date, and plot  
- 🧩 **Modular component structure** for scalability  
- 🛣️ **Routing using React Router v6**  
- ⚡ **Responsive and fast UI**

---

## 🧱 Tech Stack

- **React.js** – Frontend library  
- **React Router DOM** – For client-side routing  
- **OMDb API** – Public movie data API  
- **CSS** – Styling components  

---

## 🗂️ Folder Structure

movie-explorer/
├── public/
│ └── index.html
├── src/
│ ├── components/
│ │ ├── Navbar.jsx
│ │ ├── MovieCard.jsx
│ │ └── MovieList.jsx
│ ├── pages/
│ │ ├── Home.jsx
│ │ └── MovieDetail.jsx
│ ├── App.jsx
│ ├── App.css
│ └── main.jsx
├── package.json
└── README.md



---

## ⚙️ Installation & Setup

1. **Clone this repository**

   ```bash
   git clone https://github.com/your-username/movie-explorer.git


Navigate to the project directory
cd movie-explorer

Install dependencies
npm install

Start the development server
npm run dev

API Configuration

This project uses the OMDb API.
You can use the included demo API key (6d50cdca) or get your own key here
.

Example API calls:

Search movies:
http://www.omdbapi.com/?apikey=6d50cdca&s=Avengers

Get movie details:
http://www.omdbapi.com/?apikey=6d50cdca&i=tt0848228

Screenshots
🏠 Home Page

Displays a list of movies with a search bar.

🎥 Movie Detail Page

Shows detailed info such as poster, genre, release date, and plot.



