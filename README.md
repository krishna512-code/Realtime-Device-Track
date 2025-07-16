# Real-Time Tracking App

A Node.js, Express, and Socket.io application for real-time location tracking and visualization on a map using Leaflet.js.

## Features
- Real-time location sharing and tracking
- Interactive map with user markers
- Automatic marker removal on disconnect
- Responsive design

## Technologies Used
- Node.js
- Express.js
- Socket.io
- EJS (templating)
- Leaflet.js (map)

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or higher recommended)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```
2. Install dependencies:
   ```sh
   npm install
   ```

### Running Locally
1. Start the server:
   ```sh
   npm start
   ```
2. Open your browser and go to [http://localhost:3000](http://localhost:3000)

## Deployment
- Make sure your `app.js` uses the environment port:
  ```js
  const PORT = process.env.PORT || 3000;
  server.listen(PORT);
  ```
- Deploy to platforms like Render, Railway, or Heroku for free hosting.

## Project Structure
```
Direction/
├── app.js
├── package.json
├── public/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── favicon.ico
├── view/
│   └── index.ejs
```

## License
MIT 