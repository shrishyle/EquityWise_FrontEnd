Folder Structure

EquityWise/
│
├── frontend/
│   ├── public/
│   │   ├── index.html
│   │   └── ...
│   ├── src/
│   │   ├── assets/
│   │   │   ├── images/
│   │   │   ├── styles/
│   │   │   │   ├── tailwind.css
│   │   │   │   └── ...
│   │   ├── components/
│   │   │   ├── common/
│   │   │   │   ├── Header.js
│   │   │   │   ├── Footer.js
│   │   │   │   └── ...
│   │   │   ├── auth/
│   │   │   │   ├── Login.js
│   │   │   │   ├── Register.js
│   │   │   │   └── ...
│   │   │   ├── dashboard/
│   │   │   │   ├── Dashboard.js
│   │   │   │   ├── Portfolio.js
│   │   │   │   └── ...
│   │   │   └── ...
│   │   ├── pages/
│   │   │   ├── Home.js
│   │   │   ├── About.js
│   │   │   └── ...
│   │   ├── store/
│   │   │   ├── actions/
│   │   │   │   ├── authActions.js
│   │   │   │   ├── portfolioActions.js
│   │   │   │   └── ...
│   │   │   ├── reducers/
│   │   │   │   ├── authReducer.js
│   │   │   │   ├── portfolioReducer.js
│   │   │   │   └── ...
│   │   │   └── store.js
│   │   ├── utils/
│   │   │   ├── api.js (API integration)
│   │   │   ├── auth.js (Authentication utilities)
│   │   │   └── ...
│   │   ├── App.js
│   │   ├── index.js
│   │   └── ...
│   ├── package.json
│   ├── package-lock.json
│   └── ...
│
├── backend/
│   ├── controllers/
│   │   ├── authController.js
│   │   ├── portfolioController.js
│   │   └── ...
│   ├── middleware/
│   │   ├── authMiddleware.js
│   │   └── ...
│   ├── models/
│   │   ├── User.js
│   │   ├── Portfolio.js
│   │   └── ...
│   ├── routes/
│   │   ├── authRoutes.js
│   │   ├── portfolioRoutes.js
│   │   └── ...
│   ├── utils/
│   │   ├── authUtils.js
│   │   └── ...
│   ├── app.js (Express app)
│   ├── server.js (Entry point)
│   ├── package.json
│   ├── package-lock.json
│   └── ...
│
├── .gitignore
├── README.md
├── jest.config.js (Jest configuration)
├── Dockerfile (optional, for containerization)
├── docker-compose.yml (optional, for multi-container setups)
├── .env (environment variables, not included in version control)
└── ...
