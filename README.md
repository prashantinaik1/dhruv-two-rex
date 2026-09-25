# Dhruv Two-Rex RSVP

Guest page: index.html
Host dashboard: admin.html

The guest page is connected to the Supabase project using its browser-safe publishable key. RLS prevents anonymous visitors from reading RSVP rows.

Before using admin.html, create one host user in Supabase Authentication > Users. The dashboard signs in with that account and reads RSVPs as an authenticated user.

Deploy the folder contents to Vercel. The public invitation is `/`; the private host page is `/admin.html`.
