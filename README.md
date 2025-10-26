# 🌍 GeoQuest - City Location Game

An interactive geography learning game that challenges players to locate major cities on a real world map.

## 🎮 How to Play

1. The game shows you the name of a city
2. Click on the map where you think the city is located
3. Get instant feedback with your score based on accuracy
4. Complete 10 rounds and see your total score!

## ✨ Features

- **Real world map** with country borders (no labels to spoil the challenge!)
- **27 major cities** from around the globe
- **Accurate scoring** based on distance (closer = more points)
- **Visual feedback** with markers and distance lines
- **Sound effects** for correct and incorrect guesses
- **Interactive map** with zoom and pan controls
- **Responsive design** works on desktop and mobile

## 🎯 Scoring System

- **100 points**: Exact location (0 km away)
- **0 points**: 500 km or more away
- **Quadratic scoring**: Points decrease quadratically as distance increases
  - 100 km away ≈ 96 points
  - 200 km away ≈ 84 points
  - 300 km away ≈ 64 points
  - 400 km away ≈ 36 points
  - 500 km away = 0 points
- Maximum possible score: **1000 points** (10 cities × 100 points)

The quadratic formula means you need to be quite accurate to score well - being twice as far away costs you much more than twice the points!

## 🏙️ Cities Included

The game randomly selects 10 cities from this list each round:

- Istanbul, New York, Chicago, Mexico City, Los Angeles
- Rio de Janeiro, São Paulo, Buenos Aires
- Paris, London, Moscow
- Cairo, Lagos, Tehran
- Mumbai, Karachi, Delhi, Dhaka, Kolkata
- Bangkok, Manila, Hong Kong
- Shanghai, Beijing, Seoul, Osaka, Tokyo

## 🚀 Deployment

This is a single-file HTML application with no backend requirements. Deploy it anywhere:

### Netlify (Recommended)

1. Drag and drop `index.html` to [Netlify Drop](https://app.netlify.com/drop)
2. Done! Get instant live URL

### GitHub Pages

1. Push to GitHub repository
2. Enable GitHub Pages in Settings → Pages
3. Select main branch and save

### Other Options

- Vercel
- Cloudflare Pages
- Surge.sh
- Any static hosting service

## 🛠️ Technologies Used

- **Leaflet.js** - Interactive map library
- **OpenStreetMap** - Map tiles
- **CartoDB** - Base map tiles without labels
- **Vanilla JavaScript** - No frameworks needed
- **Web Audio API** - Sound effects

## 📝 Local Development

Simply open `index.html` in any modern web browser. No build process or dependencies to install!

## 🌐 Browser Support

Works on all modern browsers:

- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

## 📄 License

Feel free to use, modify, and distribute this game for educational purposes.

## 🤝 Contributing

Suggestions and improvements are welcome! Feel free to:

- Add more cities
- Improve the UI/UX
- Add difficulty levels
- Implement leaderboards

---

**Have fun learning geography! 🗺️**
