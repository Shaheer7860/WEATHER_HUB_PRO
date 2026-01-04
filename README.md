# 🌤️ WeatherHub Pro - Advanced Weather Analytics Platform

A professional-grade weather application featuring real-time forecasts, interactive 3D globe, air quality monitoring, and advanced data visualizations.

## ✨ Features

- **Interactive 3D Globe** - Click anywhere on the world map to get weather data
- **Real-time Weather Data** - Current conditions, 5-day forecasts, and 24-hour hourly breakdowns
- **Air Quality Index (AQI)** - PM2.5, PM10, O₃, NO₂ metrics with health recommendations
- **Historical Weather Data** - Access past weather information
- **Severe Weather Alerts** - Automatic notifications for dangerous conditions
- **Advanced Charts** - Temperature curves, precipitation bars, wind speed/gusts using Chart.js
- **Dark/Light Mode** - Smooth theme transitions with preference saving
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile

## 🚀 Deployment

### GitHub Pages

1. **Push your code to GitHub:**
   ```bash
   git add .
   git commit -m "Deploy WeatherHub Pro"
   git push origin main
   ```

2. **Enable GitHub Pages:**
   - Go to repository Settings → Pages
   - Source: Select "GitHub Actions"
   - The workflow will automatically deploy your site

3. **Your site will be live at:**
   ```
   https://YOUR_USERNAME.github.io/Weather-Hub-PRO/
   ```

### Netlify

1. **Option 1: Drag & Drop**
   - Go to [netlify.com](https://netlify.com)
   - Sign up/login
   - Drag your project folder to the deploy area
   - Your site is live instantly!

2. **Option 2: Git Integration**
   - Connect your GitHub repository
   - Netlify will auto-detect settings
   - Deploy automatically on every push

3. **Your site will be live at:**
   ```
   https://your-site-name.netlify.app
   ```

## 📁 Project Structure

```
Weather-Hub-PRO/
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── script.js           # JavaScript functionality
├── sw.js              # Service worker for offline support
├── netlify.toml       # Netlify configuration
├── _redirects         # Netlify redirects
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Actions workflow
```

## 🔧 Setup

1. **Get WeatherAPI Key:**
   - Visit [weatherapi.com](https://www.weatherapi.com/)
   - Sign up for a free account
   - Get your API key

2. **Configure API Key:**
   - Open `script.js`
   - Replace the API key on line 13:
   ```javascript
   this.apiKey = 'YOUR_API_KEY_HERE';
   ```

3. **Deploy:**
   - Follow the deployment instructions above

## 🌐 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 📝 Notes

- API key is visible in client code (normal for static sites)
- HTTPS required for geolocation (provided by GitHub Pages/Netlify)
- Free API tier has rate limits (1 million calls/month)

## 🎯 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables
- **Vanilla JavaScript** - ES6+ features
- **Three.js** - 3D globe rendering
- **Chart.js** - Data visualization
- **WeatherAPI.com** - Weather data source

## 📄 License

This project is open source and available for personal and commercial use.

---

**Enjoy your professional weather application! 🌤️**

