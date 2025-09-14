# ✨ DailyGlow – Platformă pentru sănătate & obiceiuri zilnice

**DailyGlow** este o platformă web modernă pentru monitorizarea sănătății și a obiceiurilor zilnice, cu accent pe cei 4 piloni esențiali: 
- 💤 Somn
- 💧 Hidratare,
- 🍎 Nutriție
- 🏃‍♂️ Activitate fizică.

---

## 📁 Structură proiect

- **frontend/** – Interfață utilizator (HTML, CSS, JS)
  - Pagini: Dashboard, Profil, Despre, Contact, Termeni, Confidențialitate, Formulare autentificare/înregistrare
  - Stiluri personalizate, Bootstrap & FontAwesome
  - Chart.js pentru grafice interactive
- **backend/** – Server Node.js + Express
  - Autentificare JWT, gestionare utilizatori, upload imagine profil
  - MongoDB pentru stocarea datelor
- **bootstrap/**, **fontsAwesome/**, **chart/** – Biblioteci externe

---

## 🚀 Funcționalități principale

- 🔐 Autentificare & înregistrare cu token JWT
- 📊 Dashboard cu introducere date zilnice (somn, apă, calorii, pași) și scor sănătate
- 🤖 Recomandări personalizate pe baza datelor introduse
- 👤 Profil utilizator cu editare date & upload/reset imagine
- 🔄 Schimbare parolă din profil
- 📱 Design responsive & interfață modernă

---

## ⚠️ Limitări & dezvoltări viitoare

- ✉️ Newsletter-ul și formularul de contact sunt momentan statice (nu trimit date către backend)
- 📈 Istoric activități & grafice – urmează implementarea salvării și vizualizării istoricului datelor introduse (chart history)
- 🛠️ Alte îmbunătățiri și funcționalități vor apărea pe parcurs

---

## 🛠️ Instalare & rulare locală

1. Clonează proiectul:
   ```sh
   git clone https://github.com/username/DailyGlow.git
   cd DailyGlow
   ```

2. Instalează dependențele backend-ului:
   ```sh
   cd backend
   npm install
   ```

3. Configurează variabilele de mediu în `backend/.env` (ex: JWT_SECRET, MONGO_URI)

4. Pornește serverul backend:
   ```sh
   npm start
   ```

5. Deschide fișierele HTML din `frontend/html/` în browser (ideal cu o extensie de live server sau server local)

---

> 🧑‍💻 Proiectul nu este finalizat în totalitate! Pot urma update-uri
