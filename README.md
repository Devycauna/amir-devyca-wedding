# amir-devyca-wedding

Wedding invitation website for Ahmad Amirulloh & Devyca Aurel Nabila Kautsar.

## Features
- Rustic vintage landing page
- Countdown to wedding date
- RSVP form
- Guest wishes / messages
- Digital gift wallet for BCA and BSI
- Admin dashboard for managing RSVP and messages
- Supabase-ready integration

## Files
- `index.html` — public wedding page
- `admin.html` — admin login and dashboard
- `schema.sql` — database schema for Supabase

## Setup
1. Create a Supabase project.
2. Run `schema.sql` in the SQL editor.
3. Copy the Project URL and anon key.
4. Replace the placeholder values in `index.html` and `admin.html`:
   - `https://YOUR-PROJECT-ID.supabase.co`
   - `YOUR-ANON-KEY`
5. In Supabase Authentication, create the admin account and disable public signups.
6. Enable Realtime for `guest_wishes`.
7. Upload the folder to Netlify Drop.

## Notes
- Do not put the service role key in the frontend code.
- RSVP should stay restricted to authenticated admin users for reading.
