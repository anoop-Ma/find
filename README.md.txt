# Wrote ~\AppData\Local\Temp\opencode\TrendVerseAI\README.md
# TrendVerse AI

**One Dashboard to Discover Every Trending Topic on the Internet**

TrendVerse AI is a premium, enterprise-grade static web application for content creators, marketers, SEO experts, and researchers to discover trending topics, generate content ideas, and optimize their content strategy across 35+ platforms.

## Features

### Dashboard
- Global search bar with autocomplete suggestions
- Trending keywords tracker with volume data
- Category-based filtering (Tech, Business, Health, etc.)
- Animated statistics counters
- Interactive charts (Chart.js)
- Quick access to all tools

### Platform Trends Discovery
- 35+ platform cards with direct search links
- One-click search on any platform
- Search by keyword across all platforms
- Platform filtering
- Bookmark any search result

### Viral Hook Generator
- 8 hook categories: Curiosity, Fear, Story, Benefit, Emotional, Myth vs Fact, Challenge, Mistake
- Post generator for Instagram, X, and LinkedIn
- Blog, YouTube, and Shorts title generator
- One-click copy to clipboard

### SEO Toolkit
- Meta title and description generator
- URL slug generator
- Keyword suggestions
- Heading outline generator
- Schema markup (JSON-LD) generator
- Image ALT text suggestions
- Readability score
- Search intent analysis
- Content checklist

### YouTube Creator Hub
- Video title generator
- Thumbnail text overlay suggestions
- Description generator with timestamps
- Tags generator
- Chapters generator
- Ending CTA generator
- Pinned comment generator
- Community post ideas
- Shorts and playlist suggestions

### Content Planner
- Interactive monthly calendar
- Content plan management (type, date, status)
- Progress tracker (ideas → drafting → published)
- Publishing checklist
- Idea vault

### Notes & Bookmarks
- Rich text notes with timestamps
- Quick prompt templates
- Export notes to text file
- Bookmark keywords and searches
- Export bookmarks to JSON

### Affiliate Research
- Track products with brand, price, pros/cons
- Rating system
- Affiliate link storage
- Competitor tracking

## Tech Stack

- **HTML5** - Semantic structure
- **CSS3** - Glassmorphism UI, custom properties, responsive design
- **Vanilla JavaScript** - No frameworks, all logic in `script.js`
- **Bootstrap 5** - Layout and components
- **Chart.js** - Interactive charts
- **Font Awesome** - Icons
- **Google Fonts (Inter)** - Typography
- **LocalStorage** - All data persistence

## File Structure

```
/
├── index.html         # Main dashboard
├── trends.html        # Platform trends discovery
├── hooks.html         # Viral hook generator
├── seo.html           # SEO toolkit
├── youtube.html       # YouTube creator hub
├── planner.html       # Content planner
├── notes.html         # Notes & ideas
├── bookmarks.html     # Bookmarks & affiliate research
├── style.css          # Global styles (glassmorphism, themes, animations)
├── script.js          # All application logic
├── data/
│   ├── categories.json      # Category definitions
│   ├── mock-trends.json     # Mock trend data for demo
│   └── templates.json       # Title/hook/post templates
└── README.md
```

## Deployment

### GitHub Pages
1. Push this repository to GitHub
2. Go to Settings → Pages
3. Select `main` branch and `/ (root)` folder
4. Your site will be live at `https://<username>.github.io/<repository>/`

### Any Static Host
 

## Usage

1. **Search for topics** using the global search bar on any page
2. **Discover trends** across categories on the dashboard
3. **Open platforms** directly from the Trends page
4. **Generate hooks and titles** on the Hooks page
5. **Optimize content** with the SEO Toolkit
6. **Create YouTube metadata** with the Creator Hub
7. **Plan and track** content with the Planner
8. **Save ideas** as notes and bookmark important searches

## Future API Integration

The data layer is clearly separated in `script.js` and the JSON files under `data/`. To connect real APIs in the future:

1. Replace `data/mock-trends.json` with real API responses
2. Update the `App.loadTrends()` method to fetch from your API
3. Add API keys to a server-side proxy (required for most platforms)

## License

MIT - Free for personal and commercial use.

Built with ❤️ for creators everywhere.
