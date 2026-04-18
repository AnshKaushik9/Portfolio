# 🚀 Ansh Kaushik — Portfolio Website

Clean, minimal portfolio website with project showcase. GitHub Pages pe host karna super easy hai!

---

## 📁 Files

```
portfolio/
├── index.html       ← Main website
├── projects.js      ← Sirf yahi edit karo naye project add karne ke liye!
└── README.md        ← Ye file
```

---

## ➕ Naya Project Kaise Add Karein

Sirf `projects.js` kholo aur ek naya object add karo:

```js
{
  id: 3,                          // next number
  title: "Project Name",
  emoji: "🚀",
  shortDesc: "Ek line mein kya hai.",
  techStack: ["React", "Node.js"],
  longDesc: "Poori detail yahan likho.",
  features: [
    "Feature 1",
    "Feature 2",
  ],
  githubLink: "https://github.com/AnshKaushik9/your-repo",
  status: "Completed",            // ya "In Progress"
},
```

Bas! Website automatically update ho jayegi.

---

## 🌐 GitHub Pages Pe Host Karna

### Step 1 — Repo banao
1. GitHub pe jao → **New Repository**
2. Naam do: `AnshKaushik9.github.io` (exactly aisa — apna username + `.github.io`)
3. Public rakho ✅
4. Create Repository

### Step 2 — Files upload karo
1. Repo mein jao → **Add file → Upload files**
2. `index.html` aur `projects.js` dono upload karo
3. Commit changes

### Step 3 — GitHub Pages enable karo
1. Repo → **Settings** → Left sidebar mein **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` → Folder: `/ (root)` → **Save**

### Step 4 — Live!
Kuch minutes baad teri website live hogi at:
```
https://AnshKaushik9.github.io
```

---

## ✏️ Future Updates

Jab bhi naya project banao:
1. `projects.js` kholo
2. Naya object add karo
3. GitHub pe file update karo (upload → commit)
4. Done! 🎉