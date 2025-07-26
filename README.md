# Disney+ Clone - OTT Streaming Platform

A modern, responsive Disney+ clone built with React, featuring a sleek UI design and real-time movie data from The Movie Database (TMDB) API.

![Disney+ Clone](https://img.shields.io/badge/React-19.0.0-blue?style=for-the-badge&logo=react)
![Vite](https://img.shields.io/badge/Vite-6.1.0-purple?style=for-the-badge&logo=vite)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.0.8-38B2AC?style=for-the-badge&logo=tailwind-css)

## 🎬 Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Movie Slider**: Interactive trending movies slider with navigation controls
- **Genre-based Filtering**: Browse movies by different genres
- **Production House Showcase**: Featured content from major production houses
- **Modern UI/UX**: Clean, Disney-inspired design with smooth animations
- **Real-time Data**: Live movie data from TMDB API
- **Search Functionality**: Search for movies and TV shows
- **Watchlist**: Save movies to your personal watchlist
- **User Profile**: User avatar and profile management

## 🚀 Tech Stack

- **Frontend Framework**: React 19.0.0
- **Build Tool**: Vite 6.1.0
- **Styling**: Tailwind CSS 4.0.8
- **HTTP Client**: Axios
- **Icons**: React Icons
- **API**: The Movie Database (TMDB) API
- **Linting**: ESLint

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/disney-clone-ott.git
   cd disney-clone-ott
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory and add your TMDB API key:
   ```env
   VITE_TMDB_API_KEY=your_tmdb_api_key_here
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:5173` to view the application

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🏗️ Project Structure

```
disney-clone-ott/
├── public/
├── src/
│   ├── Components/
│   │   ├── Header.jsx          # Navigation header with menu
│   │   ├── Slider.jsx          # Trending movies slider
│   │   ├── ProductionHouse.jsx # Production house showcase
│   │   ├── GenreMovieList.jsx  # Genre-based movie listings
│   │   ├── MovieCard.jsx       # Individual movie card component
│   │   ├── HrMovieCard.jsx     # Horizontal movie card
│   │   ├── MovieList.jsx       # Movie list container
│   │   └── HeaderItem.jsx      # Header menu item
│   ├── Services/
│   │   └── GlobalApi.jsx       # API service configuration
│   ├── Constant/               # Constants and configuration
│   ├── assets/                 # Static assets (images, icons)
│   ├── App.jsx                 # Main application component
│   ├── main.jsx               # Application entry point
│   └── index.css              # Global styles
├── package.json
├── vite.config.js
└── README.md
```

## 🎯 Key Components

### Header Component
- Responsive navigation with Disney logo
- Menu items: Home, Search, Watch List, Originals, Movies, Series
- Mobile-friendly hamburger menu
- User profile avatar

### Slider Component
- Horizontal scrolling movie carousel
- Navigation arrows for desktop
- Hover effects and smooth transitions
- Displays trending movies from TMDB

### Production House Component
- Showcases content from major studios
- Interactive hover effects
- Responsive grid layout

### Genre Movie List
- Categorized movie browsing
- Genre-based filtering
- Movie cards with posters and details

## 🔧 Configuration

### API Setup
The application uses The Movie Database (TMDB) API for movie data. To get your API key:

1. Visit [TMDB](https://www.themoviedb.org/)
2. Create an account and request an API key
3. Add the API key to your `.env` file

### Tailwind CSS
The project uses Tailwind CSS v4 for styling. The configuration is handled through the `@tailwindcss/vite` plugin.

## 🎨 Design Features

- **Dark Theme**: Disney-inspired dark color scheme
- **Smooth Animations**: CSS transitions and hover effects
- **Responsive Grid**: Flexible layouts for all screen sizes
- **Modern Typography**: Clean, readable fonts
- **Interactive Elements**: Hover states and click animations

## 📱 Responsive Design

The application is fully responsive with breakpoints for:
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🔒 Environment Variables

Create a `.env` file in the root directory:

```env
VITE_TMDB_API_KEY=your_tmdb_api_key_here
```

## 🚀 Deployment

### Build for Production
```bash
npm run build
```

### Deploy to Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel`
3. Follow the prompts to deploy

### Deploy to Netlify
1. Build the project: `npm run build`
2. Drag the `dist` folder to Netlify
3. Configure environment variables in Netlify dashboard

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [The Movie Database (TMDB)](https://www.themoviedb.org/) for providing the movie data API
- [React Icons](https://react-icons.github.io/react-icons/) for the beautiful icons
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [Vite](https://vitejs.dev/) for the fast build tool

## 📞 Support

If you have any questions or need help, please open an issue on GitHub or contact the maintainers.

---

**Note**: This is a clone project for educational purposes. All movie data and images are provided by TMDB API. This project is not affiliated with Disney+ or The Walt Disney Company.
