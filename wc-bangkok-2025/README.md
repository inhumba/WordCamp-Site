# WordCamp Bangkok 2025 - Website Styles

This repository contains the SASS styles for the WordCamp Bangkok 2025 website.

## Setup

### Prerequisites
- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

### Development

#### Watch mode (for development)
```bash
npm run watch
```
This will compile SASS to CSS with expanded formatting and watch for changes.

#### Watch mode with compressed output
```bash
npm run watch:compressed
```
This will compile SASS to CSS with compressed formatting and watch for changes.

### Production Build

#### Compressed build (for production)
```bash
npm run build
```
This will compile SASS to CSS with compressed formatting and source maps.

#### Development build (expanded)
```bash
npm run build:dev
```
This will compile SASS to CSS with expanded formatting and source maps.

### Clean
```bash
npm run clean
```
This will remove the compiled CSS files and source maps.

## Project Structure

```
wc-bangkok-2025/
├── css/
│   └── wcbkk-2025.css          # Compiled CSS (generated)
├── sass/
│   ├── stylesheet.scss         # Main SASS file
│   ├── _colors.scss           # Color variables
│   ├── _typography.scss       # Typography styles
│   ├── _header.scss           # Header styles
│   ├── _navigation.scss       # Navigation styles
│   ├── _content.scss          # Content styles
│   ├── _footer.scss           # Footer styles
│   ├── _tickets.scss          # Ticket styles
│   ├── _organizers.scss       # Organizer styles
│   ├── _attendees.scss        # Attendee styles
│   ├── _sponsors.scss         # Sponsor styles
│   ├── _speakers.scss         # Speaker styles
│   ├── _sessions.scss         # Session styles
│   └── _misc.scss             # Miscellaneous styles
├── package.json               # Node.js dependencies and scripts
├── .gitignore                 # Git ignore rules
├── guide.md                   # WordPress setup guide
└── README.md                  # This file
```

## Usage

The compiled CSS file (`css/wcbkk-2025.css`) can be used in WordPress by:

1. **Additional CSS**: Copy the CSS content and paste it in `Appearance -> Customize -> Additional CSS`
2. **Remote CSS**: Upload the CSS file to your server and reference it in `Appearance -> Customize -> Remote CSS`

## Fonts

This theme uses the following fonts:
- **Display fonts**: "Luktao" and "Optic"
- **Body font**: "Noto Sans Thai Looped"

Make sure these fonts are loaded in your WordPress theme or via Google Fonts.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+

## Contributing

1. Make your changes in the SASS files
2. Test your changes by running `npm run watch`
3. Build for production with `npm run build`
4. Commit your changes

## License

GPL-2.0-or-later
