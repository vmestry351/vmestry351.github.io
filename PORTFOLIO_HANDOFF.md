# Portfolio Website: Handoff Notes (v4)

To continue in a new Claude chat: upload this file, `index.html` and your resume, then say
"Continue my portfolio website using these notes. Here is the current index.html."

## Owner
Vinayak Sunil Mestry, Mumbai, India. Aspiring Data Analyst (B.Tech AI & Data Science, DJSCE).
Email: vmestry351@gmail.com
LinkedIn: https://www.linkedin.com/in/vinayak-sunil-mestry-953568386/
GitHub: https://github.com/vmestry351

## Current state (v4)
- Single self-contained `index.html` (photo embedded as base64). Published (private until shared): https://claude.ai/artifact/TkBdN41hFQB4AEyaQ46tQx
- v4 redesign: calmer professional look (rounded cards, pill chips and tags, no grid background, Manrope headings + Source Sans 3 body, Contact button in nav, dark mode follows device setting)
- Hero: typing formula bar, name headline with "Aspiring Data Analyst" line, circular photo with caption, stats strip (6 projects, 4 certifications, 4 core tools)
- Projects (6, filter chips SQL / Python / Excel / Power BI / Documentation): Credit Risk dashboard, Stack Overflow Survey, ATELIER capstone (from resume, with real metrics), plus last-mile delivery, Titanic, Excel portfolio (from GitHub)
- Daily knowledge: Instagram-style tiles + popup viewer. Posts are in the `POSTS` array in the script, newest first. Owner tool previews a post and copies a snippet to paste at the top of `POSTS`
- Skills table, Education and certifications, About, Contact (email, LinkedIn, GitHub), scroll animations, light/dark mode, reduced-motion support

## How to add a daily post
Tell Claude the topic and text and share index.html, or paste the snippet from the on-page owner tool into `POSTS`.

## To do
- [ ] Add screenshots of the Power BI dashboards and charts to the project cards
- [ ] Add GitHub links for the Stack Overflow project and the ATELIER capstone if public
- [ ] Add a Resume download button (needs hosting, e.g. GitHub Pages)
- [ ] Add B.Tech and diploma years to Education (not in the resume)
- [ ] Update the IBM certificate when completed
- [ ] Host on GitHub Pages: create public repo `vmestry351.github.io`, upload `index.html`, Settings > Pages > Deploy from branch main / root. Then add the URL to LinkedIn and GitHub

## Constraints
Single self-contained HTML; no remote images/scripts except Google Fonts; do not invent metrics; keep the CSS variable design tokens.
