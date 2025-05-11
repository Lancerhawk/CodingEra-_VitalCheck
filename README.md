# Project Dependencies

This document lists all the npm dependencies required for both the **frontend**, **backend**, and **AI** parts of the project, along with installation instructions.

---

## 🎨 Frontend Dependencies

### 📦 Regular Dependencies

These are required for the frontend application to run in production:

- `@botpress/webchat@^2.6.2`
- `@emotion/react@^11.14.0`
- `@emotion/styled@^11.14.0`
- `@mui/icons-material@^7.1.0`
- `@mui/material@^7.1.0`
- `axios@1.6.2`
- `jspdf@^2.5.2`
- `react@^19.1.0`
- `react-calendar@^5.1.0`
- `react-dom@^19.1.0`
- `react-icons@^5.5.0`
- `react-router-dom@^7.5.3`
- `react-toastify@^11.0.5`

#### ✅ Install Command:
```bash
npm install @botpress/webchat@^2.6.2 \
  @emotion/react@^11.14.0 \
  @emotion/styled@^11.14.0 \
  @mui/icons-material@^7.1.0 \
  @mui/material@^7.1.0 \
  axios@1.6.2 \
  jspdf@^2.5.2 \
  react@^19.1.0 \
  react-calendar@^5.1.0 \
  react-dom@^19.1.0 \
  react-icons@^5.5.0 \
  react-router-dom@^7.5.3 \
  react-toastify@^11.0.5
```

### 🛠 Dev Dependencies

These are needed for development and tooling:

- `@eslint/js@^9.25.0`
- `@types/react@^19.1.2`
- `@types/react-dom@^19.1.2`
- `@vitejs/plugin-react@^4.4.1`
- `eslint@^9.25.0`
- `eslint-plugin-react-hooks@^5.2.0`
- `eslint-plugin-react-refresh@^0.4.19`
- `globals@^16.0.0`
- `vite@^6.3.5`

#### ✅ Install Command:
```bash
npm install -D @eslint/js@^9.25.0 \
  @types/react@^19.1.2 \
  @types/react-dom@^19.1.2 \
  @vitejs/plugin-react@^4.4.1 \
  eslint@^9.25.0 \
  eslint-plugin-react-hooks@^5.2.0 \
  eslint-plugin-react-refresh@^0.4.19 \
  globals@^16.0.0 \
  vite@^6.3.5
```

## 🧠 Backend Dependencies

These are needed to run the Express server and handle authentication, mailing, and database communication.

### 📦 Dependencies

- `bcrypt@^5.1.1` – For password hashing
- `cors@^2.8.5` – Enable CORS for cross-origin requests
- `crypto@^1.0.1` – Node.js crypto library wrapper
- `express@^5.1.0` – Web framework
- `jsonwebtoken@^9.0.2` – For creating and verifying JWTs
- `mongoose@^8.14.2` – MongoDB object modeling
- `nodemailer@^7.0.3` – For sending emails

### ✅ Install Command:
```bash
npm install bcrypt@^5.1.1 \
  cors@^2.8.5 \
  crypto@^1.0.1 \
  express@^5.1.0 \
  jsonwebtoken@^9.0.2 \
  mongoose@^8.14.2 \
  nodemailer@^7.0.3
```

## 🤖 AI Dependencies

These are Python dependencies required to run the AI model and expose endpoints with Flask.

### 📦 Python Dependencies

- `tensorflow>=2.0.0` – For deep learning and model training
- `numpy>=1.19.2` – Numerical operations
- `Pillow>=8.0.0` – Image handling
- `flask>=2.0.0` – Web framework for serving the model
- `scikit-learn>=0.24.0` – Machine learning utilities and evaluation

### ✅ Install Command (AI environment):
```bash
pip install tensorflow>=2.0.0 \
  numpy>=1.19.2 \
  Pillow>=8.0.0 \
  flask>=2.0.0 \
  scikit-learn>=0.24.0
```

---
> ℹ️ Make sure to run the install commands in the appropriate directories:
> - `frontend/` folder for frontend dependencies
> - `backend/` folder for backend dependencies
> - `AI/` folder for AI dependencies
