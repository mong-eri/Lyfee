### 1. [render.com](https://dashboard.render.com)
   1. Create an account https://dashboard.render.com/register?next=/
   2. Click New, select PostgreSQL, Enter Name and click Create Database
   3. Copy External Database URL

      <img src="https://i.imgur.com/arOjTDr.jpeg" width="350" height="240">

### 2. [supabase.com](https://app.supabase.com/projects)
   1. Create an account and Verify it. [signUp](https://app.supabase.com/sign-up)
   2. Click new Project, Enter Name and Password (note this password)
   3. Open the Project, Open settings, open Database, Cope "Connection string" and replace [YOUR-PASSWORD] with password from step 3
   4. Change "Pool Mode" to Session. This replaced Connection string can use as DATABASE_URL

#####
 The copied URL is DATABASEURL. That You have enter as DATABASE_URL while [deploy](https://levanter-qr.vercel.app/koyeb)ing...
<!---
### 2. [railway.app](https://railway.app/dashboard)
1. Create an account https://railway.app/
2. Click New Project as PostgreSQL Project
3. Open Connect tab, Copy Postgres Connection URL
##### You can follow render or railway upto YOU
---!>