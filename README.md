# YouTube: Hide "Members Only" Videos

A lightweight [Tampermonkey](https://www.tampermonkey.net/) userscript that automatically hides any YouTube video tiles marked as **Members only** — keeping your feeds, searches, and recommendations clean.

---

## ✨ Features
- Automatically removes all videos containing the “Members only” badge  
- Works on **home**, **subscriptions**, **channel pages**, and **search results**  
- Handles **dynamic content** (YouTube SPA navigation & infinite scrolling)  
- Simple and efficient — no external dependencies  

---

## 🧩 Installation

1. **Install [Tampermonkey](https://www.tampermonkey.net/)** for your browser (available for Chrome, Edge, Firefox, Safari, etc.)  
2. Click the **Tampermonkey icon → Create a new script**  
3. Delete the template code and **paste in the contents** of [`hide_members_only.user.js`](./hide_members_only.user.js)  
4. Save (`Ctrl+S`)  
5. Visit [YouTube](https://www.youtube.com) — members-only videos will automatically disappear 🎉

---

## ⚙️ Configuration
You can edit the script to include other badge languages or variations:

```js
const BADGE_TEXTS = [
  "Members only",
  "Miembros solamente",   // Spanish
  "Nur für Mitglieder",   // German
];
