
# Photo Location Viewer

A web-based tool that allows users to upload photos and view their location on a map using EXIF metadata. This application combines image preview, metadata extraction, and location visualization using OpenStreetMap.

## Features

- 📷 Image preview for uploaded photos
- 🗺️ Location display using OpenStreetMap
- 📍 Interactive marker showing photo location
- 📝 Detailed EXIF metadata display including:
  - GPS coordinates
  - Camera make and model
  - Date taken
  - Exposure settings
  - F-stop
  - ISO

## Demo

Upload any photo with GPS data to see:
- A preview of your image
- The location where it was taken on an interactive map
- Detailed camera and exposure settings

## Technologies Used

- HTML5 File API for photo uploads
- [Leaflet.js](https://leafletjs.com/) for map display
- [OpenStreetMap](https://www.openstreetmap.org/) for map tiles
- [Exif.js](https://github.com/exif-js/exif-js) for metadata extraction

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/photo-location-viewer.git
```

2. Navigate to the project directory:
```bash
cd photo-location-viewer
```

3. Open `index.html` in your web browser

No build process or server setup required! The application runs entirely in the browser.

## Usage

1. Open the application in your web browser
2. Click the file input button to select a photo
3. Your photo will be displayed along with its location on the map (if GPS data is available)
4. View additional metadata below the map

## Privacy Notice

- All processing is done locally in your browser
- No photos or metadata are uploaded to any server
- Map display requires an internet connection to load OpenStreetMap tiles

## Browser Support

Works in all modern browsers that support:
- File API
- JavaScript ES6+
- HTML5

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- OpenStreetMap contributors for map data
- Leaflet.js team for the mapping library
- Exif.js team for the EXIF extraction library