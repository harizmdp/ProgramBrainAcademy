# Project Structure Guide

## 📁 Folder Organization

```
ProgramBrainAcademy/
├── index.html                 # Main HTML file (entry point)
├── Logo.png                   # Logo image
├── css/
│   └── styles.css            # All styling (centralized)
├── components/
│   ├── header.html           # Navigation header
│   └── footer.html           # Footer component
└── sections/
    ├── hero.html             # Hero banner section
    ├── courses.html          # Featured Programs section
    ├── about.html            # About Us section
    ├── feedback.html         # Student Feedback section
    └── contact.html          # Contact section
```

---

## 🛠️ How to Edit

### **Edit Styles**
- Go to `css/styles.css`
- Modify colors, fonts, layout
- Changes apply instantly to all pages

### **Edit Sections**
- Hero: `sections/hero.html` - Change title, description, banner
- Courses: `sections/courses.html` - Add/remove/edit program cards
- About: `sections/about.html` - Update biography
- Feedback: `sections/feedback.html` - Add/remove testimonials
- Contact: `sections/contact.html` - Update email, phone, social links

### **Edit Header/Footer**
- Header: `components/header.html` - Navigation, logo, branding
- Footer: `components/footer.html` - Copyright info

---

## 🚀 Optional: Use Build Tools

If you want to use separate files without manually copying, consider:

### **Option 1: Node.js Build Script**
Create `build.js` to merge files automatically.

### **Option 2: PHP/Apache (Server-Side Includes)**
Replace in `index.html`:
```html
<!-- Instead of copying, use: -->
<?php include 'components/header.html'; ?>
```

### **Option 3: Static Site Generator**
Use tools like Hugo, Jekyll, or 11ty to manage templating.

---

## ✅ Current Setup

The new `index.html` already contains all content with comments showing file references. This makes it easy to:
- ✓ View the complete website
- ✓ Find which file to edit for each section
- ✓ Understand the structure at a glance

**For easy maintenance:** Edit individual files in their folders, then update the corresponding section in `index.html` when done.

---

Good luck with your editing!
