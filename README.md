# Gravit Designer

Gravit, the versatile Design Tool - A powerful vector graphics editor built with modern web technologies.

## Prerequisites

- Node.js >= 14.0.0
- npm >= 6.0.0
- Bower (install globally with `npm install -g bower`)

## Installation

1. **Install Node.js dependencies:**
   ```bash
   npm install --legacy-peer-deps
   ```

2. **Install Bower dependencies:**
   ```bash
   bower install
   ```

## Running the Project

### Development Mode

Start the development server:
```bash
npm start
# or
grunt serve
```

This will:
- Start a local development server on `http://localhost:8999`
- Watch for file changes and automatically reload
- Compile SCSS to CSS
- Open the application in your default browser

### Build for Production

Build the project for production:
```bash
npm run build
# or
grunt build
```

### Run Tests

Run the test suite:
```bash
npm test
# or
grunt test
```

### Create Desktop Application

Build the desktop application using NW.js:
```bash
npm run dist
# or
grunt dist
```

## Project Structure

- `src/` - Main application source code
- `assets/` - Static assets (images, fonts, icons)
- `style/` - SCSS stylesheets
- `shell/` - Platform-specific shells (Chrome, System)
- `test/` - Test files

## Available Grunt Tasks

- `grunt serve` - Start development server
- `grunt build` - Build for production
- `grunt test` - Run tests
- `grunt dist` - Build desktop application
- `grunt clean` - Clean build directories

## Dependencies

### Runtime Dependencies
- **NW.js** - Desktop application framework

### Development Dependencies
- **Grunt** - Build tool
- **Grunt plugins** - Various build tasks (compass, uglify, concat, etc.)
- **Bower** - Frontend package manager

### Frontend Dependencies (via Bower)
- **jQuery** - DOM manipulation
- **Mousetrap** - Keyboard shortcuts
- **Font Awesome** - Icons
- **jqTree** - Tree component
- **OpenType.js** - Font parsing
- **Pako** - Compression
- **Rangy** - Text selection
- **Color Thief** - Color extraction
- **URI.js** - URL manipulation
- **Blob.js** - Blob polyfill
- **Canvas-toBlob.js** - Canvas to Blob conversion

## Browser Support

The application supports modern browsers and can also run as a desktop application using NW.js.

## License

This project is licensed under the terms specified in the LICENSE file.