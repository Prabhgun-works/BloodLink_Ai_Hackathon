Slide – Tech Stack (Definitive)

# Frontend
	•	React 18 + Vite
	•	React Router, Axios
	•	Tailwind CSS
	•	Mapbox GL JS (maps & geocoding)
	•	Turf.js (distance & geo filters)

# Backend
	•	Node.js 20 + Express 4
	•	Helmet, CORS, express-rate-limit
	•	Zod (request schema validation)
	•	Multer (file uploads: images/docs)
	•	Socket.IO (real-time feed & alerts)
	•	Winston + Morgan (structured logging)

# Data & Storage
	•	MongoDB Atlas + Mongoose (2dsphere index for location queries)
	•	Amazon S3 (patient images & medical documents)

# AI Layer
	•	OpenAI API (spam/fraud screening, urgency classification)
	•	Tesseract.js (OCR on uploaded medical docs)

# Notifications
	•	Twilio (SMS to nearby donors)
	•	SendGrid (email confirmations)
	•	Web Push (browser notifications)

# Security
	•	JWT auth + bcrypt password hashing
	•	Input sanitization & audit logs

# DevOps & Quality
	•	GitHub Actions (CI/CD)
	•	Jest + Supertest (API tests)
	•	Sentry (error monitoring)
	•	Docker (backend container)

Why this stack?
It gives us real-time matching (Socket.IO), precise proximity search (MongoDB geospatial + Turf), robust AI screening (OpenAI + OCR), and a deployable, secure pipeline (S3, JWT, CI/CD) that judges can run and test quickly.
