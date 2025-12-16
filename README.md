🎬 Popflix - Movie Streaming Website

A Netflix-inspired movie streaming website built with Flask and TMDB API. Features a stunning dark theme with electric purple colors, smooth animations, and responsive design.

✨ Features
1.Beautiful UI/UX: Modern gradient design with floating orbs and smooth animations

2.Home Page: Hero banner with featured movies slideshow and multiple movie categories

3.Movie Details: Comprehensive movie information including trailers, cast, and ratings

4.Search Functionality: Real-time search with TMDB integration

5.Responsive Design: Works on desktop, tablet, and mobile devices

6.Dynamic Content: Fetches live movie data from TMDB API

🚀 Tech Stack
Frontend:

1.HTML5, CSS3 with CSS Grid & Flexbox

2.JavaScript for interactivity

3.Custom CSS animations and transitions

Backend:

1.Python Flask

2.TMDB API integration

3.RESTful API design

Design:

1.Purple/electric color scheme

2.Glass morphism effects

3.Smooth hover animations

4.Floating elements 

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

1.Electric Purple	#8A2BE2	Primary brand color

2.Indigo	#4B0082	Secondary color

3.Magenta	#FF00FF	Accent color

4.Dark Blue-Black	#0A0A1A	Background

5.Cyan	#00FFFF	Electric blue accents

6.Deep Pink	#FF1493	Neon pink highlights

🔧 API Endpoints

1.TMDB API Integration

.The app uses these TMDB API endpoints:

2.movie/popular - Get popular movies

3.movie/top_rated - Get top-rated movies

4.movie/now_playing - Get currently playing movies

5.movie/upcoming - Get upcoming movies

6.movie/{id} - Get movie details

7.movie/{id}/credits - Get cast information

8.movie/{id}/videos - Get trailers

9.search/movie - Search movies

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

Responsive Design
The website is designed to work on:

Desktop (≥ 1024px): Full grid layouts

Tablet (768px - 1023px): Adjusted columns

Mobile (< 768px): Single column, optimized spacing

