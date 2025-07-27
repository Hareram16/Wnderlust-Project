# 🗺️ Wanderlust – Travel Listing Web App

Wanderlust is a full-stack dynamic web application inspired by **YelpCamp**, built using **Node.js**, **Express.js**, **MongoDB**, and **EJS** templating engine. It allows users to explore, create, review, and manage campground listings.

---

## 🚀 Features

- 🏕️ Add, edit & delete **campground listings**
- 🌍 Users can **view detailed info** and images of each place
- ✍️ Add **reviews/comments**
- 👤 Full **user authentication** (register/login/logout)
- 🖼️ **Cloud image uploads** using Cloudinary
- 📍 Map location integration with Mapbox
- 💬 Flash messages and validation

---

## 🛠️ Tech Stack

| Layer         | Tech Used                            |
|---------------|--------------------------------------|
| **Frontend**  | HTML, CSS, Bootstrap, EJS            |
| **Backend**   | Node.js, Express.js                  |
| **Database**  | MongoDB + Mongoose ORM               |
| **Auth**      | Passport.js                          |
| **Image Upload** | Cloudinary                        |
| **Map Integration** | Mapbox                         |
| **Other Tools** | dotenv, method-override, express-validator |

---

## 🧠 How It Works

1. Users can register and log in
2. Authenticated users can add/edit campgrounds
3. Other users can comment/review
4. Images are uploaded to Cloudinary
5. Locations mapped via Mapbox API

---

## ⚙️ Setup Instructions (Local)

```bash
# 1. Clone the repository
git clone https://github.com/hareram16/wanderlust.git
cd wanderlust

# 2. Install dependencies
npm install

# 3. Set environment variables
Create a `.env` file in root and add:
  CLOUDINARY_CLOUD_NAME=
  CLOUDINARY_KEY=
  CLOUDINARY_SECRET=
  MAPBOX_TOKEN=
  DB_URL=mongodb://localhost:27017/wanderlust
  SECRET=yourSessionSecret

# 4. Run the app
npm start
