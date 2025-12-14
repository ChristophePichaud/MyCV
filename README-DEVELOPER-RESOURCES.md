# Developer Resources Page

This is a professional developer resources page inspired by the Microsoft Developer portal design.

## Features

- **Technology-based Navigation Tabs**: Browse missions by technology area (Cloud & Azure, .NET & C#, C/C++, Web Development, Security & Audit, or All Missions)
- **Clickable Resource Cards**: Each mission is displayed as an interactive card with hover effects
- **Mission Data**: All data is extracted from the CV file (Christophe Pichaud's detailed CV)
- **Statistics Dashboard**: Shows total missions (40), technologies (157), years of experience (25+), and technology areas (6)
- **Skills Section**: Displays all technical skills extracted from the CV
- **Responsive Design**: Works on desktop and mobile devices
- **Microsoft-inspired Styling**: Clean, professional design matching Microsoft Developer portal aesthetics

## How to View

Simply open `developer-resources.html` in any modern web browser.

Alternatively, you can serve it with a local web server:

```bash
# Using Python
python3 -m http.server 8000

# Then open http://localhost:8000/developer-resources.html
```

## Data Source

All missions and skills are automatically extracted from:
- `Docs/CV Decembre 2025 Détaillé - Christophe Pichaud.docx`

## Technology Stack

- Pure HTML5, CSS3, and JavaScript
- No external dependencies
- Responsive grid layout
- Smooth animations and transitions
- Microsoft Fluent Design inspiration

## Navigation Tabs

1. **All Missions** - Shows all 40 professional missions
2. **Cloud & Azure** - 7 cloud-focused missions
3. **.NET & C#** - 20 .NET development missions
4. **C/C++** - 20 C/C++ missions
5. **Web Development** - 8 web development missions
6. **Security & Audit** - 6 security and audit missions

## Card Information

Each mission card displays:
- Project title
- Period/Duration
- Company name
- Project description
- Role
- Key technologies (as tags)
