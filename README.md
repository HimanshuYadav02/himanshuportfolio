# 🌟 Himanshu Yadav - Personal Portfolio Website

A modern, responsive, Apple-inspired glassmorphic portfolio website crafted with pure **HTML5, CSS3, and JavaScript**.

---

## 📁 Project Structure

```
HimanshuPortfoliyo/
│
├── index.html                   # Main single-page portfolio structure
├── style.css                    # Glassmorphism, dark/light themes, animations & responsive design
├── script.js                    # Interactive features (glow, typewriter, theme toggle, filters, modal)
├── README.md                    # Setup, customization & GitHub deployment guide
│
└── assets/                      # Media and graphic assets
    ├── logo.svg                 # "HY" Monogram logo
    ├── avatar-placeholder.svg   # Sleek developer avatar placeholder (fallback)
    ├── profile.jpg              # 👈 Upload your own photo here in VS Code!
    ├── Himanshu_Yadav_Resume.pdf # 👈 (Optional) Place your resume PDF here
    ├── himanshu-cert-isro.svg           # IIRS (ISRO) Geodata Processing Certificate
    ├── himanshu-cert-cisco.svg          # Cisco Networking Academy Cybersecurity Certificate
    ├── himanshu-cert-edureka.svg        # Edureka Full Stack Development Certificate
    ├── himanshu-cert-greatlearning.svg  # Great Learning Computer Architecture Certificate
    └── himanshu-cert-leetcode.svg       # LeetCode Knight Badge (200+ Solved) Certificate
```

---

## 📸 1. How to Upload Your Photo in VS Code

1. In VS Code, navigate to the `assets` folder:
   ```
   HimanshuPortfoliyo/assets/
   ```
2. Copy or drag-and-drop your profile picture into the `assets` folder.
3. Name the image file **`profile.jpg`** (or `profile.png`).
4. If you use a `.png` or `.jpeg` file with a different name, open `index.html` and search for:
   ```html
   <img src="assets/profile.jpg" onerror="this.onerror=null; this.src='assets/avatar-placeholder.svg';" alt="Himanshu Yadav" ...>
   ```
   Update `assets/profile.jpg` with your image filename (e.g., `assets/my-photo.png`).
5. Refresh your browser — your photo will appear instantly in the About section and Modal!

---

## 📄 2. How to Add Your Resume PDF

1. Put your PDF resume file in the `assets/` folder.
2. Name it **`Himanshu_Yadav_Resume.pdf`**.
3. Now clicking the **"Download Resume"** button on the website will automatically open/download your PDF resume!

---

## 🔗 3. Updating Your Profile Links (GitHub, LinkedIn, LeetCode)

In `index.html`, update the placeholder URLs with your personal handles:

- **GitHub:** Replace `https://github.com/` with `https://github.com/your-username`
- **LinkedIn:** Replace `https://linkedin.com/` with `https://linkedin.com/in/your-profile`
- **LeetCode:** Replace `https://leetcode.com/` with `https://leetcode.com/your-handle`
- **Google Drive Link:** In the Certifications section, update the `https://drive.google.com/` link with your Google Drive folder link containing all certificates.

---

## 🚀 4. How to Deploy on GitHub Pages (Separate Repository)

Since you want your portfolio to be separate and live on GitHub:

1. **Create a New Repository on GitHub:**
   - Go to [github.com/new](https://github.com/new)
   - Name the repository: `himanshu-portfolio` (or `portfolio`)
   - Keep it **Public** and click **Create repository**.

2. **Push the Code from VS Code Terminal:**
   Open a terminal in the `himanshu-portfolio` folder and run:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of Himanshu Yadav Portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-github-username>/himanshu-portfolio.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your GitHub repository -> **Settings** -> **Pages** (under Code and automation).
   - Under **Build and deployment > Branch**, select `main` and `/ (root)`, then click **Save**.
   - Within 1–2 minutes, your website will be live at:
     ```
     https://<your-github-username>.github.io/himanshu-portfolio/
     ```

---

## ✨ Features Included

- **Dark & Light Mode Switch:** Remembers your preference in `localStorage`.
- **Cosmic Glow & Apple Glassmorphism:** Mouse-tracking radiant cursor glow and sticky frosted glass navbar.
- **Dynamic Typewriter:** Smoothly cycles through your key roles and achievements.
- **Interactive Certificate Filtering:** Filter by `Data & AI`, `Software Dev`, `Cybersecurity`, and `System Architecture`.
- **Certificate & Profile Modal:** Click any certificate or your profile photo to view an enlarged lightbox popup.
- **Interactive Contact Form & One-Click Copy:** Easily copy your email or initiate direct communication.
- **100% Mobile Responsive:** Clean hamburger drawer and responsive layout for all screen sizes.
