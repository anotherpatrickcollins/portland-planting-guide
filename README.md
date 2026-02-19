# Portland Planting Guide
## About

This site is a lightweight, privacy-friendly tool that lets you:

- Search crops quickly
- Filter by planting timing and method
- See recommended planting windows at a glance
- Share filtered views with a copyable link

## How It Works

The site is intentionally simple:

- A CSV file acts as the data source
- The browser loads and parses the CSV at runtime
- Filters and search are generated dynamically
- No backend, database, or tracking

## Tech Stack

- HTML
- Tailwind CSS 
- Alpine.js
- PapaParse 

Everything runs client-side.

## Project Structure
```
/portland-planting-guide
│
├── index.html        # Main application
├── about.html        # About page
├── data.csv          # Planting data source
├── gardener.svg      # Decorative illustration
└── README.md
```

## The Data

All planting information lives in `data.csv`.

Planting guidance is compiled from materials shared by Portland Nursery, drawing on:

- The Maritime Northwest Garden Guide (Tilth Alliance)
- The Old Farmer’s Almanac
- Territorial Seed Catalogue
- Growing Vegetables West of the Cascades (Steve Solomon)

This project reorganizes and presents that information in a different interface; all credit for the gardening expertise belongs to the original sources.

## Contributing

This started as a personal project, but suggestions and improvements are welcome. Feel free to open an issue or submit a pull request.

## Support

If this tool helps your garden grow, you can support the project here:
- Buy me a coffee: https://www.buymeacoffee.com/anotherpatrickcollins

# Happy planting 🌱
