# Grade 9B Work Website

This project is a simple web application for **Class 9B students** to upload, view, and share their work.  
It provides a clean interface with subject‑based organization, theme switching, and dynamic content loading.

---

## ✨ Features
- **Subject Sidebar**: Browse work by subject (AI, Science, Mathematics, etc.).
- **Dynamic Content**: Files and metadata are loaded from `ContentData.json`.
- **Theme Switcher**: Toggle between System, Dark, and White themes.
- **File Cards**: Each uploaded file shows metadata (Author, Date, Subject, Type).
- **Actions**: Stylish buttons to **Open** or **Download** files.
- **Download Warning**: Prevents accidental duplicate downloads within 5 seconds.
- **Update Log**: `Update.txt` tracks all changes and versions.
- **Responsive Design**: Works across desktop and mobile.

---

## 📂 Project Structure
- `index.html` → Landing page with navigation, theme slider, version info, and update log button.
- `Content.html` → Displays uploaded work by subject, with fetch integration.
- `Upload.html` → Page for students to upload their own work.
- `ContentData.json` → Stores metadata for uploaded files.
- `Update.txt` → Changelog documenting progress from v0.1 to current.

---

## 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Grade-9-Work.git
