🧬 OncoCare — Plateforme de Télémédecine en Oncologie

Plateforme web de télémédecine dédiée à l’oncologie permettant aux patients et aux médecins de communiquer, suivre les traitements et gérer les dossiers médicaux à distance.

🚀 Fonctionnalités principales
👨‍⚕️ Côté Médecin
Consultation des dossiers patients
Gestion des rendez-vous
Téléconsultation (vidéo / chat)
Suivi des traitements oncologiques
Prescription et notes médicales
🧑‍💻 Côté Patient
Création et gestion du profil médical
Prise de rendez-vous en ligne
Accès aux consultations (vidéo / chat)
Historique des traitements
Notifications et rappels
🛠️ Fonctionnalités Générales
Authentification sécurisée (JWT)
Gestion des rôles (Admin / Médecin / Patient)
Stockage sécurisé des données médicales
Dashboard interactif
API RESTful
🏗️ Architecture du projet
oncocare/
│
├── backend/        # Node.js + Express
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   └── config/
│
├── frontend/       # React.js
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── hooks/
│
├── database/       # MongoDB
└── README.md
⚙️ Technologies utilisées
Backend
Node.js
Express.js
MongoDB (Mongoose)
JWT (authentification)
Socket.io (temps réel)
Frontend
React.js
Axios
React Router
Tailwind CSS / Material UI
Autres
WebRTC (téléconsultation vidéo)
Cloud Storage (images, documents médicaux)
🔐 Sécurité
Chiffrement des mots de passe (bcrypt)
Authentification JWT
Protection des routes
Validation des données
Respect des bonnes pratiques (HIPAA-like)
📦 Installation
1️⃣ Cloner le projet
git clone https://github.com/benaboud-roqia/plateforme-telemedecine-oncologie.git
cd oncocare
2️⃣ Backend
cd backend
npm install
npm run dev
3️⃣ Frontend
cd frontend
npm install
npm start
🔧 Variables d’environnement

Créer un fichier .env dans le dossier backend :

PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
📡 API Endpoints (exemples)
Auth
POST /api/auth/register
POST /api/auth/login
Patients
GET /api/patients
POST /api/patients
Rendez-vous
POST /api/appointments
GET /api/appointments
📸 Aperçu (optionnel)
Dashboard médecin
Interface patient
Page de téléconsultation
🎯 Objectif du projet

Améliorer l’accès aux soins en oncologie en permettant :

un suivi à distance des patients
une communication rapide médecin-patient
une gestion centralisée des données médicales
🧠 Améliorations futures
Intelligence artificielle pour aide au diagnostic
Analyse des IRM / scanner
Application mobile (React Native)
Intégration avec dispositifs IoT médicaux
🤝 Contribution

Les contributions sont les bienvenues !

fork → commit → pull request
📄 Licence

Ce projet est sous licence MIT.

👨‍💻 Auteur
BENABOUD ROQIA — Développeur Full Stack & AI
