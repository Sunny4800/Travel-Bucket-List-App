# TripVault Premium

Static travel destination tracker ready for Netlify.

Fields:
- Destination
- Location (29 options: 28 Indian states + Delhi)
- Status (Visited / Yet to Visit)
- Tags

Features:
- Premium responsive UI
- Home dashboard
- Left-side filters for Location, Status and Tags
- Search
- Dark mode
- Add/edit/delete destinations
- Visited / Yet-to-Visit counts and progress
- LocalStorage persistence

Deploy:
1. Upload `index.html` to GitHub.
2. Import the repo into Netlify.
3. Leave build command empty.
4. Publish directory: `/`.

Note: destination data is stored in browser LocalStorage. For cross-device sync, replace LocalStorage with Supabase/Firebase later.
