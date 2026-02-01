# My Favorite Airplanes

## Overview
A simple static HTML website showcasing favorite airplanes from military and civilian aviation.

## Project Structure
- `index.html` - Main HTML page
- `server.py` - Python HTTP server for serving static files
- `images/` - Directory for airplane images

## How to Run
The project uses a Python HTTP server on port 5000. The workflow "Web Server" runs `python server.py`.

## Deployment
This is a static website that can be deployed using the "static" deployment type with `public_dir` set to the root directory.

## Notes
- Images referenced in the HTML need to be added to the `images/` folder
- The server includes cache control headers to prevent caching issues
