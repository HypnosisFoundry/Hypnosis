# Hypnosis Foundry — Landing Pages

## Adding Your Profile Photo

1. Add your headshot photo to this folder, named exactly: `munjal.jpg`
2. In each HTML file, find the `about-photo-placeholder` div
3. Replace the entire div with: `<img src="/munjal.jpg" alt="Munjal Shah" class="about-photo">`
4. Commit and push — Vercel will redeploy automatically

## Activating Meta Pixel

In each HTML file, find `YOUR_PIXEL_ID` and replace with your actual Pixel ID.
Then remove the `//` comment marks from all pixel lines.

## Activating Email Notifications (Formspree)

1. Go to formspree.io and create a free form
2. Copy your form ID (looks like: xyzabc12)
3. In each HTML file, add to the form tag:
   `action="https://formspree.io/f/YOUR_FORM_ID" method="POST"`

## Pages
- `/anxiety` → anxiety.html
- `/sports-performance` → sports.html  
- `/autoimmune` → autoimmune.html
