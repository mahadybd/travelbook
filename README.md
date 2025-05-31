# Travelbook App

Travelbook is a React-based web application that allows you to create your personal collection of places you would like to visit or have visited. Easily browse beautiful destinations, add them to your wishlist, and manage your own travel bucket list.

## Features

- Browse a curated list of amazing places from around the world
- Add places to your personal collection with a single click
- Remove places from your collection with confirmation
- All data is persisted via a simple backend API
- Responsive and modern UI

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/)

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/mahadybd/travelbook.git
   cd travelbook
   ```

2. **Install frontend dependencies:**

   ```sh
   npm install
   ```

3. **Install backend dependencies:**
   ```sh
   cd backend
   npm install
   cd ..
   ```

### Running the App

1. **Start the backend server:**

   ```sh
   cd backend
   node app.js
   ```

2. **Start the frontend development server:**

   ```sh
   npm run dev
   ```

3. Open [http://localhost:5173](http://localhost:5173) in your browser.

## Project Structure

- `src/` - React frontend source code
- `backend/` - Node.js/Express backend API and data files
- `public/` - Static assets

## Customization

- Add or modify places in `backend/data/places.json`
- User selections are stored in `backend/data/user-places.json`
- Place images are stored in `backend/images/`

## GitHub Repository

[https://github.com/mahadybd/travelbook](https://github.com/mahadybd/travelbook)

## License

This project is for learning and demonstration purposes.

---

Enjoy building your travel wishlist with Travelbook!
