# HeavenStays 🏨✨

HeavenStays is a full-stack web application inspired by Airbnb that allows users to list, explore, and book unique accommodations around the world. Designed with a clean, premium aesthetic, it offers a seamless experience for both hosts and travelers.

## 🚀 Features
* **User Authentication:** Secure signup and login functionality.
* **Property Listings (CRUD):** Users can create, view, update, and delete their own listings.
* **Image Uploads:** Cloud-based image storage for property photos.
* **Reviews & Ratings:** Interactive feedback system for listings.
* **Interactive Mapping:** Visualizes property locations on a dynamic map.

## 🛠️ Tech Stack
* **Frontend:** EJS (Embedded JavaScript), HTML5, CSS3, Bootstrap 5
* **Backend:** Node.js, Express.js
* **Database:** MongoDB (via Mongoose)
* **Storage & APIs:** Cloudinary (Images), Mapbox (Maps)

## 🔧 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd HeavenStays
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add:
   ```env
   CLOUD_NAME=your_cloudinary_name
   CLOUD_API_KEY=your_cloudinary_key
   CLOUD_API_SECRET=your_cloudinary_secret
   MAP_TOKEN=your_mapbox_token
   ATLASDB_URL=your_mongodb_atlas_url_if_production
   SECRET=your_session_secret
   ```

4. **Run the application:**
   ```bash
   node app.js
   ```
   Open `http://localhost:8080` in your browser.
