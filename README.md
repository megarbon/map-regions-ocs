# Regional Map Visualization

Interactive world map displaying countries grouped by geographic and linguistic regions.

## 🗺️ Regions

| Color | Region | Description |
|-------|--------|-------------|
| ![#d71515](https://via.placeholder.com/15/d71515/d71515.png) | **CHINA** | China |
| ![#f39c12](https://via.placeholder.com/15/f39c12/f39c12.png) | **INDIA+** | India, Pakistan, Bangladesh, Sri Lanka, Nepal, Bhutan, Maldives |
| ![#c277f0](https://via.placeholder.com/15/c277f0/c277f0.png) | **RUSSIA+** | Russian-speaking countries: Russia, Belarus, Kazakhstan, Ukraine, Armenia, Azerbaijan, Georgia, Moldova, Kyrgyzstan, Tajikistan |
| ![#2ecc71](https://via.placeholder.com/15/2ecc71/2ecc71.png) | **BRAZIL+** | Portuguese-speaking countries: Brazil, Portugal, Cape Verde, Guinea-Bissau, São Tomé and Príncipe, Timor-Leste |
| ![#3e6360](https://via.placeholder.com/15/3e6360/3e6360.png) | **REPUBLIC OF KOREA** | South Korea |
| ![#e91e63](https://via.placeholder.com/15/e91e63/e91e63.png) | **JAPAN** | Japan |
| ![#e7d919](https://via.placeholder.com/15/e7d919/e7d919.png) | **LATAM+** | Spanish-speaking countries: Spain, Mexico, Central America, South America (excluding Brazil), Cuba, Dominican Republic, Equatorial Guinea |
| ![#3353d6](https://via.placeholder.com/15/3353d6/3353d6.png) | **FRANCE+** | French-speaking countries: France, Belgium, Switzerland, Luxembourg, Monaco, French-speaking African countries (Algeria, Morocco, Tunisia, Senegal, Mali, Ivory Coast, Cameroon, DR Congo, Madagascar, etc.), Haiti |

## 📋 Grouping Logic

- **Language-based**: Countries grouped primarily by shared language (Russian, Spanish, Portuguese, French, Hindi/Urdu)
- **Geographic proximity**: South Asian countries grouped with India
- **Cultural ties**: Historical and cultural connections considered (e.g., Portugal with Brazil)
- **Ungrouped**: USA, Canada, Greenland, UK, Australia, and other countries remain uncolored (gray)

## 🚀 Usage

Simply open `index.html` in a web browser. The map is interactive:
- **Hover** over countries to highlight them
- **Click** on countries to see their name and region

## 🛠️ Tech Stack

- Leaflet.js for mapping
- OpenStreetMap for base tiles
- GeoJSON for country boundaries
- Pure HTML/CSS/JavaScript (no build process required)