# Visagh Reji | Cybersecurity & AI Portfolio

Interactive, responsive, and secure personal portfolio website showcasing cybersecurity auditing, full-stack software development, and artificial intelligence engineering capabilities.

Live repository: [https://github.com/Visaghreji/portfolio](https://github.com/Visaghreji/portfolio)

---

## 🚀 Key Features

- **Interactive Canvas Network**: An interactive nodes/particles canvas backdrop representing cybersecurity net structures.
- **Dynamic Typing Terminal**: Emulates terminal-like inputs showcasing specialized career vectors.
- **Safe Custom Cursor trailing**: Sleek pointer interactions with accessibility fallback configurations.
- **Responsive Layout**: Designed to scale flawlessly from ultra-wide screens to mobile devices.
- **Timeline & Counters Journey**: Highlights professional certifications, achievements, and metrics.

---

## 🔒 Security & Quality Controls (SecOps Dev)

This site is hardened with standard frontend security controls to demonstrate safe development principles:

1. **Content Security Policy (CSP)**: Added strict meta-policy restrictions ensuring that only verified scripts, styles, and assets are run in the browser.
2. **Referrer Header Protections**: Configured policy headers to enforce strict cross-origin checks.
3. **Tab-Nabbing Mitigation**: Applied `target="_blank" rel="noopener noreferrer"` parameters across all external outbound links. This protects users against malicious redirections from target browser threads.
4. **XSS Input Sanitization**: Implemented character entity encoding (`&lt;`, `&gt;`, `&quot;`, `&#039;`, `&amp;`) in client-side form submissions to filter dangerous characters.
5. **Boundary Hardening**: Applied strict string buffers and lengths validation limits on the contact form fields.
6. **Graceful Accessibility Degradation**: Designed CSS cursor states to conditionally load *only* if JavaScript successfully executes, ensuring that users with script-blocking controls or screen readers always retain standard hover controls.

---

## 📁 Project Structure

```text
├── .gitignore         # Staging filter for system files and IDE configurations
├── LICENSE            # MIT open-source terms of use
├── README.md          # Project documentation (this file)
├── index.html         # Main semantic structure and layout
├── profile.png        # Profile avatar asset
├── script.js          # Interactive behaviors, custom cursor, particles, and validation
└── style.css          # Styled UI layout variables, glassmorphism, responsive queries
```

---

## 🛠️ Getting Started & Local Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Visaghreji/portfolio.git
   cd portfolio
   ```

2. **Add Your Resume**:
   - Simply save your resume file as `resume.pdf` in the root folder. The portfolio is pre-configured to download this file when the "Download Resume" button is clicked.

3. **Open local page**:
   - Simply double-click `index.html` to run in any browser, or use VS Code's "Live Server" extension for hot reloading.

---

## 🌐 Secure Deployment on GitHub Pages

This portfolio is designed to be hosted serverless on GitHub Pages. To deploy:

1. Push files to the `main` branch:
   ```bash
   git add .
   git commit -m "chore: professional and secure enhancements"
   git push origin main
   ```
2. Navigate to your repository on GitHub: **Settings -> Pages**.
3. Under **Build and deployment**, select **Deploy from a branch** and set the source to `main` (or root path).
4. GitHub Pages will build and serve your site over HTTPS securely with a default SSL configuration.

---

## 📄 License

This project is licensed under the terms of the MIT License. See [LICENSE](LICENSE) for details.
