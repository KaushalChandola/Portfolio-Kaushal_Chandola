# Kaushal Chandola — Portfolio Website

This project is a single-page personal portfolio (portfolio.html) with a separate resume page (resume.html). It supports two visual themes (dark & light) and an in-browser __Admin Mode__ that lets you edit content directly on the live site without touching the code.
🔗 Check out my [Live Portfolio](https://portfoliokaushalchandola.vercel.app/)

## 1. Dark Theme (Default Mode)

When the site first loads, it opens in Dark Mode — a deep black/navy background with glowing accent colors, animated star/orbit particles, and a "grain" texture overlay for a premium, modern feel.

### Sections included on the page (in order):

#### Hero Section (hero): 
Displays your name, title, tagline, profile photo, key metrics, and call-to-action buttons.
#### About Section (about): 
Displays a brief personal biography and introductory statement.
#### Skills Section (skills): 
Displays interactive cards categorised by technical skills, software tools, and core technologies.
#### Projects Section (projects): 
Displays project details using description cards, technology tags, external links, and image galleries.
#### Experience Section (experience): 
Displays a chronological timeline detailing your professional work history and completed internships.
#### Certifications Section (certs): 
Displays credential records featuring document previews and instant download options.
#### Achievements Section (achievements): 
Displays notable individual accomplishments, professional awards, or key career milestones.
#### Contact Section (contact): 
Displays direct communication channels and active social links to get in touch.

Dark mode is the default appearance every time someone visits the site (unless they've previously switched to light mode, since the choice is remembered).
<img width="2834" height="1256" alt="image" src="https://github.com/user-attachments/assets/be8622fd-8019-4e37-90d5-ac486292d623" />
<img width="2792" height="1226" alt="image" src="https://github.com/user-attachments/assets/48e379d8-e95f-40df-911f-722e0a20c563" />
<img width="2808" height="1252" alt="image" src="https://github.com/user-attachments/assets/fe4a7101-3f93-4723-96c6-1f2e0d1dba50" />

## 2. Light Theme

Clicking the theme toggle switch (top-right, next to the nav) instantly switches the site to Light Mode — a bright, clean background with adjusted card colors, text contrast, and toned-down animations (the glowing dots/orbit effects are hidden in light mode for a calmer look).

### Sections included on the page (in order):

#### Hero Section (hero): 
Displays your name, title, tagline, profile photo, key metrics, and call-to-action buttons.
#### About Section (about): 
Displays a brief personal biography and introductory statement.
#### Skills Section (skills): 
Displays interactive cards categorised by technical skills, software tools, and core technologies.
#### Projects Section (projects): 
Displays project details using description cards, technology tags, external links, and image galleries.
#### Experience Section (experience): 
Displays a chronological timeline detailing your professional work history and completed internships.
#### Certifications Section (certs): 
Displays credential records featuring document previews and instant download options.
#### Achievements Section (achievements): 
Displays notable individual accomplishments, professional awards, or key career milestones.
#### Contact Section (contact): 
Displays direct communication channels and active social links to get in touch.

Only the color palette, backgrounds, and some decorative effects change — the content, layout, and navigation stay identical. Your theme choice is saved in the browser (localStorage), so the site remembers whether you prefer dark or light the next time you visit.
<img width="2846" height="1246" alt="image" src="https://github.com/user-attachments/assets/5b30cc72-0a2a-4f5b-a26b-7df3bde2d932" />
<img width="2846" height="1250" alt="image" src="https://github.com/user-attachments/assets/7369e8b2-0052-40b6-98be-7bc806f4150d" />
<img width="2828" height="1236" alt="image" src="https://github.com/user-attachments/assets/17a15086-dc53-406d-aa1b-d4e054aa14d6" />

## 3. Admin Mode

Admin Mode is a hidden content-management layer built into the website itself — it lets the site owner (you) update text, images, projects, certificates, and the resume directly from the live browser, without editing any code.

### How to enter Admin Mode

1. Click the "Admin" button in the navigation bar.
2. Enter the admin password in the login popup.
3. Once logged in, an "✏️ Edit mode" control appears — the site is now in Admin Mode (this stays active for your session).

### What Admin Mode lets you do


#### Edit page text inline — 
click directly on headings, bios, or descriptions and edit them like a text document.
#### Upload/replace the profile photo shown in the Hero section
#### Manage Projects — 
add, edit, or remove project cards, including uploading project screenshots/gallery images.
#### Manage Certifications — 
upload certificate files/images that visitors can preview and download.
#### Manage Skills, Experience & Achievements — 
add or edit entries in these sections.
#### Update the Resume (on resume.html) — 
upload a new PDF file and a new preview image separately (uploading a PDF does not auto-generate its preview image; both must be uploaded individually).
#### Log out of Admin Mode — 
exits editing and hides the admin controls again.

### Where the data is stored

All admin edits (text, photos, project images, certificates, resume PDF/preview) are saved in the browser's localStorage, so changes persist across page reloads on the same browser/device. There is no external server or database — this is a fully client-side (browser-only) editing system.
### Note:
Because storage is local to the browser, edits made on one device/browser won't automatically appear on another device unless the underlying HTML file itself is updated and redeployed.

### File Structure
portfolio.html   → Main site (Hero, About, Skills, Projects, Experience, Certs, Achievements, Contact)
resume.html      → Dedicated resume page (opens from the "Resume" nav link, has a "Back to Dashboard" link)
Keep both files in the same folder so the navigation links between them work correctly.

<img width="2834" height="1256" alt="image" src="https://github.com/user-attachments/assets/c1c16b39-674a-49ae-8519-609832b6ef14" />
<img width="2818" height="1256" alt="image" src="https://github.com/user-attachments/assets/83fb4d90-917c-4808-a413-66e9e85e7eb7" />
<img width="2830" height="1246" alt="image" src="https://github.com/user-attachments/assets/14b39987-6d2d-4b03-a52e-b3794021a981" />
