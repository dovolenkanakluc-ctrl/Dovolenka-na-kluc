# Weather Dashboard 🌤️

A beautiful, responsive weather dashboard that fetches real-time weather data from the OpenWeatherMap API. Get detailed weather information, forecasts, and more for any location worldwide.

## ✨ Features

### Current Weather Information
- **Real-time Temperature** - Current, feels-like, min/max temperatures
- **Weather Conditions** - Description and weather icons
- **Atmospheric Data** - Humidity, pressure, wind speed
- **Visibility & Cloud Coverage** - Detailed atmospheric metrics
- **Geolocation Support** - Automatic location detection

### 5-Day Forecast
- Daily weather predictions
- Temperature ranges
- Weather conditions
- Interactive forecast cards

### Location Search
- **City Search** - Search by city name
- **Current Location** - One-click geolocation
- **Preset Cities** - Quick access to popular cities (London, New York, Tokyo, Paris, Sydney, Dubai, Singapore, Barcelona)

### Detailed Information Cards
- 📍 Location coordinates and details
- 🌡️ Temperature analysis
- 💨 Wind and atmospheric conditions
- 👁️ Visibility and cloud coverage

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/dovolenkanakluc-ctrl/dovolenka-na-kluc.git
   cd dovolenka-na-kluc
   ```

2. **Open the dashboard:**
   - Simply open `weather-dashboard.html` in your web browser
   - No installation or build process required

3. **That's it!** 🎉
   - The dashboard will load with New York weather by default
   - Start searching for any city or use your current location

## 🔧 Configuration

### API Key
The dashboard uses a free OpenWeatherMap API key. To use your own:

1. Visit [OpenWeatherMap](https://openweathermap.org/api)
2. Sign up for a free account
3. Get your API key
4. Replace the `API_KEY` in the code:
   ```javascript
   const API_KEY = 'your_api_key_here';
   ```

## 📱 How to Use

### Search by City
1. Enter a city name in the search box
2. Click "Search" or press Enter
3. View current weather and forecast

### Use Current Location
1. Click the "📍 Current Location" button
2. Allow browser permission to access location
3. Weather data for your location loads automatically

### Quick City Access
- Click any preset city button (London, New York, Tokyo, etc.)
- Weather data updates instantly

## 🎨 Design Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Modern UI** - Clean, intuitive interface with smooth animations
- **Color-Coded Cards** - Easy-to-read weather information
- **Gradient Backgrounds** - Beautiful purple gradient header
- **Interactive Elements** - Hover effects and smooth transitions

## 📊 Data Provided

### Current Weather
- Temperature (Celsius)
- Feels-like temperature
- Min/Max temperatures
- Weather condition
- Humidity percentage
- Atmospheric pressure
- Wind speed and direction
- Visibility distance
- Cloud coverage
- Last update time

### Forecast
- 5-day weather forecast
- Daily temperatures
- Weather conditions
- Weather icons

### Location Details
- City and country
- Latitude and longitude
- Coordinates

## 🌐 API Information

This dashboard uses the **OpenWeatherMap API**:
- **Endpoint**: `https://api.openweathermap.org/data/2.5`
- **Weather Data**: Real-time current weather
- **Forecast Data**: 5-day forecast
- **Free Tier**: Sufficient for personal use

### Rate Limits
- Free tier: 60 calls/minute
- Unlimited requests per day

## 🖥️ Browser Support

- ✅ Chrome/Chromium (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+ - Full 3-column layout
- **Tablet**: 768px - 1200px - 2-column layout
- **Mobile**: Below 768px - Single column layout

## 🔐 Privacy & Security

- No data is stored locally
- Geolocation data is only used to fetch weather
- All requests go directly to OpenWeatherMap API
- No personal information is collected or shared

## ⚡ Performance

- **Load Time**: < 2 seconds
- **API Calls**: Optimized with concurrent requests
- **Caching**: Browser caches static assets
- **Mobile Friendly**: Optimized for slower connections

## 🐛 Troubleshooting

### "City not found" Error
- Check spelling of city name
- Try using a larger city name
- Use the current location feature instead

### Geolocation Not Working
- Check browser permissions
- Allow location access in browser settings
- Ensure you have internet connection
- Try a different browser

### Weather Data Not Loading
- Check your internet connection
- Refresh the page
- Clear browser cache and cookies
- Check if OpenWeatherMap API is accessible

## 📚 Code Structure

```
weather-dashboard.html
├── HTML Structure
│   ├── Header
│   ├── Search Section
│   ├── Content Area (dynamically populated)
│   └── Footer
├── CSS Styling
│   ├── Root variables for colors
│   ├── Responsive grid layouts
│   ├── Animation effects
│   └── Media queries
└── JavaScript Functionality
    ├── Event listeners
    ├── API calls
    ├── Data processing
    └── DOM manipulation
```

## 🔗 Key JavaScript Functions

- `fetchWeatherByCity(city)` - Fetch weather by city name
- `fetchWeatherData(lat, lon)` - Fetch weather by coordinates
- `fetchForecastData(lat, lon)` - Fetch 5-day forecast
- `displayCurrentWeather(data)` - Render current weather
- `displayForecast(data)` - Render forecast cards
- `getGeolocation()` - Get user's location
- `showLoading()` - Show loading spinner
- `showError(message)` - Display error message

## 🌡️ Temperature Units

Currently displaying in **Celsius**. To change to Fahrenheit, modify the API calls:
```javascript
// Change from:
?units=metric

// To:
?units=imperial
```

## 🎯 Future Enhancements

Potential features to add:
- [ ] Hourly forecast
- [ ] Air quality data
- [ ] UV index
- [ ] Sunrise/Sunset times
- [ ] Weather alerts
- [ ] Temperature unit toggle
- [ ] Dark/Light mode theme
- [ ] Multiple city comparison
- [ ] Weather history
- [ ] Rain/Snow probability

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Credits

- **Weather Data**: [OpenWeatherMap](https://openweathermap.org/)
- **Icons**: OpenWeatherMap icon set
- **Fonts**: Google Fonts (Inter, Playfair Display)

## 📞 Support

For issues, questions, or suggestions:
1. Check the troubleshooting section
2. Review the code comments
3. Open an issue on GitHub
4. Contact the developer

## 🎓 Learning Resources

- [OpenWeatherMap API Documentation](https://openweathermap.org/api)
- [MDN Web Docs - Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
- [MDN Web Docs - Geolocation API](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API)

---

**Created**: 2026  
**Last Updated**: May 13, 2026  
**Version**: 1.0.0

Enjoy accurate, real-time weather information! 🌍☀️🌧️
