# 🇳🇱 Dutch Irregular Verbs Flashcards

A simple offline-friendly web app to **learn Dutch irregular verbs** through flashcards.  
Made with only HTML, CSS, and JavaScript — no dependencies, no server needed.

---

## 🎯 Features
- 120+ irregular verbs with **English meanings**
- **Click-to-flip** or use keyboard (Space / Enter)
- Mark verbs as **Known ✓** or **Again ↺** (Learning)
- Auto-save progress in your browser
- **Category filter** by vowel pattern (ij, ie, ui, etc.)
- **Search**, **shuffle**, and **auto-flip** modes
- **Add your own verbs** with meaning and example
- **Import/Export** your progress as a JSON file
- Works completely **offline**

---

## 🧠 How It Works
| Action | Result |
|--------|---------|
| `Flip` or click the card | Show Past Tense, Past Participle, and Meaning |
| `Known ✓` | Mark verb as known |
| `Again ↺` | Keep it in learning set |
| `Reset` | Clear all progress |
| `Export / Import` | Backup or share your progress |

Progress is stored locally in your browser (via `localStorage`).

---

## 🧩 Keyboard Shortcuts
| Key | Action |
|-----|---------|
| `←` / `→` | Previous / Next card |
| `Space` / `Enter` | Flip card |
| `G` | Mark as Known |
| `A` | Mark as Learning |

---

## 🌐 Hosting via GitHub Pages
This site is fully static — just one `index.html` file.

1. Go to **Settings → Pages** in your repository.  
2. Under **Source**, choose `main` branch and `/ (root)` folder.  
3. Click **Save** and wait about a minute.  
4. GitHub will publish it at  
   **https://your-username.github.io/dutch-irregular-verbs/**

---

## 💾 Sharing Progress
Your progress and custom verbs stay on your browser only.  
To share with friends:
1. Click **Export** → get `nl-irregular-verbs-progress.json`
2. Send it to them.
3. They can click **Import** in their copy of the app.

---

## 📂 Project Structure
