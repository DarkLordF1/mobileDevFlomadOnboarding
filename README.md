# Mobile Dev Onboarding 🚀

![MIT License](https://img.shields.io/badge/license-MIT-green.svg) ![AOS.js](https://img.shields.io/badge/AOS-2.3.1-blue.svg)

A lightweight, scroll‑driven checklist to help new mobile developers get comfortable with Flomad Labs’ Flutter & Firebase setup.

---

## 🔎 Contents

- [Why This Tool?](#-why-this-tool)
- [Highlights](#-highlights)
- [Tech & Tools](#-tech--tools)
- [Quick Start](#-quick-start)
- [How It Works](#-how-it-works)
- [Customize Your Steps](#-customize-your-steps)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🤔 Why This Tool?

Onboarding developers can be repetitive: installing SDKs, configuring Firebase, remembering project structure. This simple web page puts all the “first steps” in one place, so new teammates can: 

1. See the entire setup at a glance.  
2. Check off each task as they go.  
3. Toggle between light and dark mode if they prefer.

---

## ✨ Highlights

- **Checklist-First**: Interactive checkboxes keep you on track.  
- **Responsive**: Works great on desktop, tablet or phone.  
- **Theme Switch**: Light/dark toggle is built in.  
- **AOS Animations**: Smooth fade and slide effects for each step.

---

## 🛠 Tech & Tools

- **HTML5 & CSS3**: Semantic markup, modern styling.  
- **Vanilla JavaScript**: No frameworks — just minimal, readable code.  
- **AOS.js**: https://michalsnik.github.io/aos/ for scroll-triggered animations.  
- **Google Fonts** (Montserrat) for clean typography.

---

## 🚀 Quick Start

1. **Clone the repo**
   ```bash
   git clone https://github.com/DarkLordF1/mobileDevFlomadOnboarding.git
   cd mobileDevFlomadOnboarding
   ```
2. **Serve locally**
   - Python 3: `python3 -m http.server 8000`  
   - Node.js: `npx http-server`  

3. **Open** [http://localhost:8000](http://localhost:8000) in your browser.

---

## ⚙️ How It Works

- Each onboarding step is a `<li>` with a checkbox.  
- Checking a box marks that item as done (with CSS styling).  
- Light/dark mode uses a simple JS toggle saved in `localStorage`.  
- AOS attributes on elements (`data-aos="fade-up"`, etc.) control animations.

---

## 🎨 Customize Your Steps

- **Edit Steps**: Open `index.html` and add/remove `<li>` items under the `<ul class="checklist">`.
- **Styles**: Tweak `styles.css` to change colors, fonts or spacing.  
- **Animations**: Modify `data-aos` attributes on any step to use different AOS effects.

---

## 🤝 Contributing

1. Fork this repository.  
2. Create a branch for your feature: `git checkout -b feature/my-step`.  
3. Make your changes and commit: `git commit -m "Add new onboarding step"`.  
4. Push and open a pull request.

We welcome ideas for extra features such as saving progress remotely or adding sub‑tasks!
