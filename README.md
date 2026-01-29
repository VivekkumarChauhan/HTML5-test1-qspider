# TRAVELLAND - Travel & Tourism Website

## Project Overview
TRAVELLAND is a responsive HTML5 and CSS-based travel and tourism website. It provides users with an intuitive interface to explore travel packages, discover destinations, browse services, and learn about the company.

## Features
- **Responsive Design**: Mobile-friendly layout using flexbox
- **Multiple Pages**: Home, About Us, Destinations, Services, and Tours
- **Navigation Menu**: Easy-to-use navigation with dropdown indicators
- **Search Functionality**: Destination and traveler search bar on the home page
- **Authentication**: Login and Signup buttons for user accounts
- **Modern Styling**: Green and orange color scheme with Font Awesome icons
- **Footer Navigation**: Quick links to company information and social media

## Project Structure
```
TRAVELLAND/
│
├── index.html                 # Home page - Main landing page
├── About.html                 # About Us page - Company information
├── Destinations.html          # Destinations page - Travel destinations showcase
├── Services.html              # Services page - Available travel services
├── tours.html                 # Tours page - Tour packages (currently empty)
├── style.css                  # Global styles
├── Readme.md                  # Project documentation
│
└── asset/
    └── images/
        ├── logo.png          # Website logo
        ├── icon.png          # Favicon
        ├── Home-About.jpg    # Background image (commented out)
        └── Home-Tour.jpg     # Background image for search section
```

## Pages Description

### 1. **index.html** (Home Page)
The main landing page with:
- Header with logo and authentication buttons (Login/Signup)
- Navigation menu with 5 main sections: Home, Tours, Destinations, Services, About Us
- Large hero search section with background image
- Search bar for destination, date, and traveler count
- Features section with placeholder boxes
- Comprehensive footer with company links and social media

### 2. **About.html**
Dedicated about page featuring:
- Hero section with background overlay
- Company story and information
- Custom styling with blue color scheme
- Responsive design for all devices

### 3. **Destinations.html**
Showcase of travel destinations with:
- Grid layout for destination cards
- Destination cards with shadow effects
- Clean and organized display
- Responsive grid template

### 4. **Services.html**
Service offerings page including:
- Professional header and navigation
- Green-themed styling (#2E7D32)
- Service listings with Font Awesome icons
- Call-to-action buttons
- Sticky navigation header

### 5. **tours.html**
Tours page (Currently empty - available for expansion)

## Styling & CSS Features
The website uses `style.css` with:
- **Global Reset**: Box-sizing and margin/padding reset
- **Color Scheme**: 
  - Primary green: #afe96d, #bede95, #A5D6A7
  - Accent orange: orangered
  - Backgrounds: #f5f9ff, #F1F8E9
- **Responsive Elements**: Flexbox layouts with flex-wrap
- **Visual Effects**: Background images, gradients, shadows, and border-radius
- **Interactive Elements**: Hover-enabled buttons and links

## Key Components

### Header Section
```html
<header class="header">
    - Logo image
    - Login and Signup buttons
</header>
```

### Navigation Bar
```html
<nav>
    - Home, Tours, Destinations, Services, About Us
    - Dropdown indicators using Font Awesome
</nav>
```

### Search Section
```html
<div class="serch-bar">
    - Destination input
    - Date picker
    - Traveler count input
    - Search button
</div>
```

## External Dependencies
- **Font Awesome 7.0.1**: Icon library via CDN
  - Used for dropdown carets and navigation icons
- **Google Fonts**: Segoe UI and Arial for typography

## Color Palette
| Color Name | Hex Code | Usage |
|-----------|----------|-------|
| Light Green | #afe96d | Header background |
| Medium Green | #bede95 | Navigation bar |
| Accent Green | #A5D6A7 | Secondary elements |
| Orange | orangered | Call-to-action buttons |
| Light Background | #f5f9ff | Page backgrounds |
| Dark Text | #263238, #1e3a5f | Body text |

## Browser Support
The website is built with standard HTML5 and CSS3, supporting all modern browsers:
- Chrome
- Firefox
- Safari
- Edge
- Mobile browsers

## Development Notes
- Responsive design implemented using Flexbox
- Search functionality structure in place (backend needed for actual functionality)
- Image assets required in `asset/images/` folder
- Some sections have commented-out code for future development
- Tours page is ready for content addition

## Future Enhancements
1. Add JavaScript functionality for interactive features
2. Implement backend for search and booking functionality
3. Complete the tours.html page
4. Add more destination and service cards
5. Implement responsive design for mobile devices
6. Add animation and transitions
7. Integrate with a backend API for bookings and user authentication

## Credits
Created as part of a travel & tourism web development project using HTML5 and CSS3.
