🎬 Popflix - Movie Streaming Website

A Netflix-inspired movie streaming website built with Flask and TMDB API. Features a stunning dark theme with electric purple colors, smooth animations, and responsive design.

✨ Features
Beautiful UI/UX: Modern gradient design with floating orbs and smooth animations

Home Page: Hero banner with featured movies slideshow and multiple movie categories
Movie Details: Comprehensive movie information including trailers, cast, and ratings
Search Functionality: Real-time search with TMDB integration
Responsive Design: Works on desktop, tablet, and mobile devices
Dynamic Content: Fetches live movie data from TMDB API

🚀 Tech Stack
Frontend:
HTML5, CSS3 with CSS Grid & Flexbox
JavaScript for interactivity
Custom CSS animations and transitions

Backend:
Python Flask
TMDB API integration
RESTful API design

Design:
Purple/electric color scheme
Glass morphism effects
Smooth hover animations
Floating elements 

📁 Project Structure
popflix/
├── app.py                    # Main Flask application
├── templates/
│   ├── home.html            # Main homepage
│   ├── movie_detail.html    # Movie details page
│   └── search.html          # Search results page
└── README.md                # This file

🛠️ Setup & Installation
Prerequisites
Python 3.8+

TMDB API key (free from https://www.themoviedb.org/)
pip (Python package manager)


🎨 Color Scheme
Color	Hex	Usage
Electric Purple	#8A2BE2	Primary brand color
Indigo	#4B0082	Secondary color
Magenta	#FF00FF	Accent color
Dark Blue-Black	#0A0A1A	Background
Cyan	#00FFFF	Electric blue accents
Deep Pink	#FF1493	Neon pink highlights

🔧 API Endpoints
TMDB API Integration
The app uses these TMDB API endpoints:
movie/popular - Get popular movies
movie/top_rated - Get top-rated movies
movie/now_playing - Get currently playing movies
movie/upcoming - Get upcoming movies
movie/{id} - Get movie details
movie/{id}/credits - Get cast information
movie/{id}/videos - Get trailers
search/movie - Search movies

Flask Routes
/ - Homepage
/movie/<id> - Movie details page
/search?q=<query> - Search results

🎥 Features in Detail
Home Page
Rotating hero banner with featured movies
Four movie categories:
Popular on Popflix
Top Rated Movies
Now Playing in Theaters
Coming Soon
Hover effects on movie cards
Animated navbar on scroll
Movie Details Page
Full movie information
Official trailer (if available)
Cast list with photos
Movie metadata (rating, runtime, genres)
Backdrop and poster images
Search Page
Real-time movie search
Display search results in grid
No results state
Persistent search query

📱 Responsive Design
The website is designed to work on:
Desktop (≥ 1024px): Full grid layouts
Tablet (768px - 1023px): Adjusted columns
Mobile (< 768px): Single column, optimized spacing

