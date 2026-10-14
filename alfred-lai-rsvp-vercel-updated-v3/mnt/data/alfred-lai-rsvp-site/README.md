# Alfred Lai · Memorial & RSVP Website

This is a static HTML website, ready to deploy to Vercel. No npm, React, database, or server is required.

## Deploy (Vercel Drop)
1. Open https://vercel.com/drop and sign in.
2. Drag the unzipped **alfred-lai-rsvp-site** folder onto the page.
3. Deploy the project. Vercel will provide a vercel.app URL.
4. To use a domain, open Project → Settings → Domains and follow the shown DNS instructions.

## Files
- `index.html`: all page content, styling, and embedded Google Form.
- `images/`: exact originals copied from the supplied Drive folder and invitation. No edits, redrawing, AI enhancement or destructive crops were applied to the files. The browser crops images visually using CSS `object-fit: cover`.
- `images/original-invitation.png`: original invitation kept for reference.

## Important checks before publishing
- Preview the page on mobile and desktop.
- Ensure Google Form is published and accepts responses from guests without requiring your organisation sign-in.
- Submit a test RSVP, then remove the test response from Google Forms if appropriate.
- Verify the service/celebration addresses, times, and wording, as transcribed from the invitation.
- Replace the livestream notice with the actual link when ready.
- The embedded Google Form retains Google's own styling and may include an internal scrollbar.

To change text, edit `index.html`. To change a photo, replace the corresponding file in `images/` with the same filename.
