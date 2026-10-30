OMAR DONGA PORTFOLIO STARTER

Upload all files in this folder to the same directory on your web host.
Public site: index.html
Admin dashboard: admin.html

The dashboard signs in using Supabase Auth and verifies the user in public.site_admins.
Add Vimeo videos through the dashboard; the site reads published rows from public.works.
Thumbnails upload to the portfolio-images Storage bucket.

Security: config.js contains only the Supabase publishable key. Never put a secret or
service_role key in browser code. Keep the supplied RLS policies enabled.

Before launch: test login, thumbnail upload, publish/hide, and Vimeo embed permissions.
Replace the public contact link/email with the client's approved contact details.
