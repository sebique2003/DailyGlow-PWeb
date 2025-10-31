# ✨ DailyGlow – Health & Daily Habits Platform

**DailyGlow** is a modern web platform for monitoring health and daily habits, focusing on the 4 essential pillars: 
- 💤 Sleep
- 💧 Hydration
- 🍎 Nutrition
- 🏃‍♂️ Physical Activity.

---

## 📁 Project Structure

- **frontend/** – User Interface (HTML, CSS, JS)
  - Pages: Dashboard, Profile, About, Contact, Terms, Privacy, Login/Signup Forms
  - Custom styles, Bootstrap & FontAwesome
  - Chart.js for interactive charts
- **backend/** – Node.js + Express Server
  - JWT authentication, user management, profile image upload
  - MongoDB for data storage
- **bootstrap/**, **fontsAwesome/**, **chart/** – External libraries

---

## 🚀 Main Features

- 🔐 Login & registration with JWT token
- 📊 Dashboard for daily data input (sleep, water, calories, steps) and health score
- 🤖 Personalized recommendations based on entered data
- 👤 User profile with data editing & image upload/reset
- 🔄 Change password from profile
- 📱 Responsive design & modern interface

---

## ⚠️ Limitations & Future Developments

- ✉️ The newsletter and contact form are currently static (do not send data to the backend)
- 📈 Activity history & charts – implementation of saving and viewing data history (chart history) is upcoming
- 🛠️ Other improvements and features will be added over time

---

## 🛠️ Installation & Local Setup

1. Clone the project:
   ```sh
   git clone https://github.com/username/DailyGlow.git
   cd DailyGlow
   ```

2. Install backend dependencies:
   ```sh
   cd backend
   npm install
   ```

3. Configure environment variables in `backend/.env` (e.g., JWT_SECRET, MONGO_URI)

4. Start the backend server:
   ```sh
   npm start
   ```

5. Open the HTML files from `frontend/html/` in a browser (ideally with a live server extension or local server)

---

> 🧑‍💻 The project is not fully completed! Updates may follow
