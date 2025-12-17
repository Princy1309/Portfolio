# Princy Nayagi M – Portfolio

Modern, responsive personal portfolio website for **Princy Nayagi M**, **Java Full Stack Developer (Fresher)**.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Design**: Custom modern UI, light/dark mode, responsive, mobile-first  
- **Hosting**: Static site – ready for **Vercel** or **Netlify**

## Project Structure

- `index.html` – Main portfolio page with all sections (Hero, About, Skills, Projects, Internship & Certifications, Strengths, Contact)
- `styles.css` – Global styles, layouts, theme (light/dark), and responsive design
- `script.js` – Theme toggle, mobile navigation, footer year
- `assets/Princy-Nayagi-M-Resume.pdf` – Optional resume file (add your latest resume here)

## Running Locally

1. Open the project folder:
   ```bash
   cd D:\Portfolio
   ```
2. Open `index.html` directly in your browser (double-click or drag into a browser), or use a simple static server (for example, VS Code Live Server extension).

## Deploying to Vercel

1. Push this folder to a GitHub repository.
2. Go to Vercel and **Import Project** from GitHub.
3. Set:
   - **Framework Preset**: `Other`
   - **Root Directory**: project root (where `index.html` is)
4. Deploy – Vercel will serve `index.html` as a static site.

## Deploying to Netlify

1. Push this folder to a GitHub repository.
2. On Netlify, choose **Add new site → Import an existing project**.
3. Select your repository and set:
   - **Build command**: _empty_ (no build needed)
   - **Publish directory**: project root
4. Deploy the site.

## Customization

- Update meta tags in `index.html` for:
  - `og:url`
  - `canonical` URL
- Replace the resume placeholder with your real file in `assets/` and ensure the filename matches the link in the Hero section.
- Adjust skills, projects, and content directly in `index.html` as your experience grows.


