# Rev. Dr. Emmanuel Kwabena Ansah — website

Static export of the Webflow site, prepared for Vercel.

- Pages: Home, About, Ministry, Books, Gallery, Contact (`vercel.json` enables clean URLs, e.g. `/about`).
- Books are baked into `books.html` (not CMS). Cover images load from the Webflow CDN.
- Contact form posts to FormSubmit (`https://formsubmit.co/parrybernard007@gmail.com`). The first submission sends an activation email to that address — click it to start receiving messages.

## Deploy
Import this repo at https://vercel.com/new (Framework preset: **Other**, no build command, output directory: `.`).
