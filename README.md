# EntechAssistant Report System

A web-based application for generating interactive energy management reports and sales presentations for Entech energy systems.

## Features

- **Management Company Dashboard** - Browse and search management companies
- **Individual Direct Links** - Generate shareable links for specific management companies
- **Interactive Reports** - Slideshow presentations showing:
  - Energy cost comparisons (before/after Entech)
  - Current and lifetime savings
  - System downtime analysis and costs
  - Service upgrade recommendations
- **Multiple Navigation Options** - Arrow keys, dropdown menus, page indicators
- **Responsive Design** - Works on desktop, tablet, and mobile devices

## Usage

### Local Development
1. Open `index.html` in any modern web browser
2. No server or build process required

### Direct Management Links
- Click "Show Individual Links" to display shareable URLs
- Each link takes users directly to a specific management company's report
- Format: `?management=CompanyName`

### Navigation
- Use arrow keys or on-screen buttons to navigate presentations
- Dropdown menu available for portfolios with many buildings
- Page dots shown for smaller portfolios

## Data Structure

The system processes building data including:
- Energy costs before/after Entech installation
- Current and lifetime savings
- System downtime tracking
- Pricing for different service tiers

## Technical Details

- **Frontend**: React 18, Tailwind CSS
- **Data**: Static JavaScript array (1,788+ building records)
- **Deployment**: Static hosting compatible (GitHub Pages, Netlify, etc.)

## Deployment

This application is designed for static hosting and can be deployed to:
- GitHub Pages
- Netlify
- Vercel
- Any web server

Simply upload all files to your hosting provider's root directory.