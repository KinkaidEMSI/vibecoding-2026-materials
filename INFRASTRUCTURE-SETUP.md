# VibeCoding EMSI 2026 — Infrastructure Setup Checklist

**Last updated:** June 7, 2026  
**For:** KinkaidEMSI GitHub Organization

---

## 1️⃣ GitHub Organization Settings

### Codespaces Configuration
1. Go to: `https://github.com/organizations/KinkaidEMSI/settings/codespaces`
2. **Enable Codespaces** for all members
3. Set **machine type limit** to `2-core`
4. Set **idle timeout** to `30 minutes`
5. Click **Save**

---

## 2️⃣ Template Repository Setup

### Create Template Repo
```bash
cd ~/vibecoding-2026-materials
gh repo create KinkaidEMSI/vibecoding-template --public --source=. --remote=template
git remote add template https://github.com/KinkaidEMSI/vibecoding-template
git push template main
```

### Enable GitHub Pages
1. Go to: `https://github.com/KinkaidEMSI/vibecoding-template/settings/pages`
2. Under **Source**: Select `Deploy from a branch`
3. Select **main** branch, **/ (root)** folder
4. Click **Save**
5. Wait ~1 min, then verify at: `https://kinkaidemsi.github.io/vibecoding-template/`

### Mark as Template Repository
1. Go to: `https://github.com/KinkaidEMSI/vibecoding-template/settings`
2. Scroll to **Template repository** section
3. Check ✅ **Template repository**
4. Click **Save**

---

## 3️⃣ GitHub Classroom Setup

### Create Classroom
1. Go to: `https://classroom.github.com/classrooms/new`
2. Select organization: **KinkaidEMSI**
3. Name: `VibeCoding EMSI 2026`
4. Click **Create classroom**

### Create Assignment 1 (Project 1)
1. In classroom, click **New assignment**
2. **Title:** `Project 1 - Personal Portfolio`
3. **Prefix:** `project1-`
4. **Template repository:** Select `KinkaidEMSI/vibecoding-template`
5. **Admin access:** Enable (so you can view student repos)
6. Click **Create assignment**
7. **Copy invitation link** → Save for Google Classroom

### Create Assignment 2 (Project 2)
1. Repeat above steps with:
   - **Title:** `Project 2 - Interactive App`
   - **Prefix:** `project2-`
   - Template: Same as Project 1
2. **Copy invitation link** → Save for Google Classroom

---

## 4️⃣ Google Classroom Setup

### Create Class
1. Go to: `https://classroom.google.com/`
2. Click **+** → **Create class**
3. **Class name:** `VibeCoding EMSI 2026`
4. **Section:** `Spring 2026`
5. **Room:** (Your room number)
6. Click **Create**

### Create Topics
1. In class, click **Classwork** tab
2. Click **Create** → **Topic**
3. Create topics:
   - `Week 1: Setup & AI Fundamentals`
   - `Week 2: HTML & CSS Basics`
   - `Week 3: JavaScript Fundamentals`
   - `Week 4: Project 1 - Portfolio`
   - `Week 5: Advanced JavaScript`
   - `Week 6: APIs & Data`
   - `Week 7: Project 2 - Interactive App`
   - `Week 8: Final Presentations`

### Create Assignments (9 total)

#### Assignment 1: Day 1 Onboarding
- **Topic:** Week 1
- **Title:** Day 1 - Setup & Onboarding
- **Instructions:**
  ```
  Complete your development environment setup and AI tools onboarding.
  
  📋 Checklist:
  - [ ] Join GitHub Classroom
  - [ ] Complete Codespace setup
  - [ ] Review AI Cheat Sheet
  - [ ] Submit "Hello World" screenshot
  
  🔗 Resources:
  - Setup Guide: https://kinkaidemsi.github.io/vibecoding-2026-materials/day1-onboarding.html
  - AI Cheat Sheet: https://kinkaidemsi.github.io/vibecoding-2026-materials/ai-cheatsheet.html
  ```
- **Attachments:** Upload `day1-onboarding.html` and `ai-cheatsheet.html` (download from repo first)
- **Points:** 10
- **Due date:** (Set as needed)

#### Assignment 2: Day 2 Debug Exercise
- **Topic:** Week 1
- **Title:** Day 2 - Debug Challenge
- **Instructions:**
  ```
  Practice debugging skills with GitHub Copilot.
  
  Complete the debugging exercises and submit your fixed code.
  
  🔗 Exercise: https://kinkaidemsi.github.io/vibecoding-2026-materials/day2-debug-exercise.html
  ```
- **Points:** 15

#### Assignment 3: HTML Basics
- **Topic:** Week 2
- **Title:** HTML Fundamentals
- **Instructions:**
  ```
  Create a basic HTML page structure.
  
  Requirements:
  - Use semantic HTML5 tags
  - Include proper head section
  - Add at least 5 different elements
  
  Submit your GitHub repository link.
  ```
- **Points:** 20

#### Assignment 4: CSS Styling
- **Topic:** Week 2
- **Title:** CSS Styling Basics
- **Instructions:**
  ```
  Style your HTML page with CSS.
  
  Requirements:
  - External CSS file
  - Use flexbox or grid
  - Responsive design (mobile-friendly)
  ```
- **Points:** 20

#### Assignment 5: JavaScript Basics
- **Topic:** Week 3
- **Title:** JavaScript Fundamentals
- **Instructions:**
  ```
  Add interactivity with JavaScript.
  
  Requirements:
  - Variables and functions
  - DOM manipulation
  - Event listeners (at least 2)
  ```
- **Points:** 25

#### Assignment 6: Project 1 - Portfolio (GitHub Classroom)
- **Topic:** Week 4
- **Title:** Project 1 - Personal Portfolio Website
- **Instructions:**
  ```
  Build your personal portfolio website using HTML, CSS, and JavaScript.
  
  🎯 Idea Tickets: https://kinkaidemsi.github.io/vibecoding-2026-materials/idea-tickets.html
  
  📝 Accept assignment and start coding:
  [PASTE YOUR PROJECT1 GITHUB CLASSROOM LINK HERE]
  
  Requirements:
  - About section
  - Projects showcase
  - Contact form or links
  - Responsive design
  - Deployed via GitHub Pages
  ```
- **Points:** 100
- **Type:** Assignment (not Material)

#### Assignment 7: APIs & Fetch
- **Topic:** Week 6
- **Title:** Working with APIs
- **Instructions:**
  ```
  Fetch data from a public API and display it on your page.
  
  Suggested APIs:
  - OpenWeather
  - GitHub API
  - JSONPlaceholder
  ```
- **Points:** 30

#### Assignment 8: Project 2 - Interactive App (GitHub Classroom)
- **Topic:** Week 7
- **Title:** Project 2 - Interactive Web Application
- **Instructions:**
  ```
  Build an interactive web application with API integration.
  
  🎯 Idea Tickets: https://kinkaidemsi.github.io/vibecoding-2026-materials/idea-tickets.html
  
  📝 Accept assignment and start coding:
  [PASTE YOUR PROJECT2 GITHUB CLASSROOM LINK HERE]
  
  Requirements:
  - Fetch data from external API
  - User interaction (forms, buttons, etc.)
  - Dynamic content updates
  - Clean, professional design
  - Deployed via GitHub Pages
  ```
- **Points:** 150

#### Assignment 9: Final Presentation
- **Topic:** Week 8
- **Title:** Final Project Presentation
- **Instructions:**
  ```
  Present your Project 2 to the class.
  
  Prepare:
  - 5-minute demo
  - Explain your code choices
  - Share challenges and solutions
  - Submit presentation slides (optional)
  ```
- **Points:** 50

---

## 5️⃣ Verification Checklist

### GitHub
- [ ] Codespaces enabled and configured
- [ ] Template repo created and populated
- [ ] GitHub Pages live on template repo
- [ ] Repo marked as template
- [ ] GitHub Classroom created
- [ ] Assignment 1 (project1-) created with invitation link
- [ ] Assignment 2 (project2-) created with invitation link

### Google Classroom
- [ ] Class created
- [ ] 8 topics created
- [ ] 9 assignments created
- [ ] GitHub Classroom links added to Project 1 & 2
- [ ] Handouts uploaded to relevant assignments
- [ ] All due dates set

---

## 📋 Quick Reference Links

**GitHub Org:** https://github.com/KinkaidEMSI  
**Template Repo:** https://github.com/KinkaidEMSI/vibecoding-template  
**Materials Repo:** https://github.com/KinkaidEMSI/vibecoding-2026-materials  
**GitHub Pages:** https://kinkaidemsi.github.io/vibecoding-2026-materials/  
**GitHub Classroom:** https://classroom.github.com/classrooms/[YOUR-CLASSROOM-ID]  
**Google Classroom:** https://classroom.google.com/c/[YOUR-CLASS-ID]

---

## 🆘 Troubleshooting

### Students can't access Codespaces
- Check org Codespaces settings
- Verify student is org member
- Check machine type limits aren't too restrictive

### GitHub Classroom invitation link doesn't work
- Verify student has GitHub account
- Check org visibility settings
- Ensure assignment is published (not draft)

### Google Classroom link not clickable
- Use full URL (not shortened)
- Test link in incognito mode
- Verify assignment is published to students

---

**Need help?** Contact GitHub Education Support or Google Classroom Help Center.
