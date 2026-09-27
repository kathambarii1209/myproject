# E-Progress Card — Vercel + Railway

## Vercel
Framework: Other
Build Command: blank
Output Directory: blank
Root Directory: .

## Required Production Environment Variables
DB_HOST=Railway public TCP host (example: shinkansen.proxy.rlwy.net)
DB_PORT=Railway public TCP port (example: 22653)
DB_NAME=Railway MYSQLDATABASE
DB_USER=Railway MYSQLUSER
DB_PASSWORD=Railway MYSQLPASSWORD
SECRET_KEY=a-long-random-secret

Do not use mysql.railway.internal from Vercel.

After changing environment variables, create a NEW deployment/redeploy.
