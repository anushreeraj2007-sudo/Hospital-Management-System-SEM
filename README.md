# Hospital Management System (Express + MongoDB)

## Run in VS Code
1. Install Node.js 18+ and MongoDB Community Server (or use a free MongoDB Atlas URI).
2. Open this folder in VS Code, then open the terminal (Ctrl+`).
3. `npm install`
4. Check `.env` (set MONGO_URI if you use Atlas).
5. `npm run seed`   (creates demo users and sample data - run once)
6. `npm start`      (or `npm run dev` for auto-reload)
7. Open http://localhost:5000

## Demo logins
| Role | Username | Password |
|---|---|---|
| Administrator | admin | admin123 |
| Doctor | doctor | doctor123 |
| Receptionist | reception | reception123 |
| Patient | patient | patient123 |

Patients can also self-register from the login page.
For new doctor/patient logins created by an admin, paste the Doctor/Patient record `_id` into "Linked record ID".
