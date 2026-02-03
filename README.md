# auth_db2
mysql, backend 

backend/
 ├─ package.json
 ├─ .env
 ├─ server.js
 ├─ app.js
 ├─ config/
 │    └─ db.js
 |    └─ mailter.js
 ├─ models/
 │    └─ user.model.js
 ├─ middleware/
 │    ├─ auth.middleware.js
 │    └─ validation.middleware.js
 ├─ controllers/
 │    └─ auth.controller.js
 ├─ routes/
 │    └─ auth.routes.js
 └─ services/
      └─ mailer.service.js