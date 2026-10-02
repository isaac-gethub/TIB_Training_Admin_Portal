TIB Training Administration Portal v2.0 — Vercel Ready

DEPLOYMENT
1. Open your existing Vercel project for tibtrainingadminportal.vercel.app.
2. Replace the existing project files with the contents of this folder (or upload this ZIP if your workflow supports ZIP deployment).
3. Redeploy to Production.
4. Verify https://tibtrainingadminportal.vercel.app/

V2 FEATURES
- Invite, Enroll & Email
- Save Course Access & Email
- Send Enrollment Email
- Password reset
- Deactivate all Training Assistant courses
- Branded enrollment email with active courses, start/expiry dates, trainee login email, and Mobile App URL
- Enrollment email logging occurs in Supabase backend

BACKEND
This front end calls the existing Supabase Edge Function: training-assistant-admin.
No Supabase service-role key is included in this package.
