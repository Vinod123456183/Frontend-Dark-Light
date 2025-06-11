
# ⚛️ React + Vite Project

## 🔄 Update All Dependencies to Latest

### 🛠 Step 1 – Upgrade All Packages:
```bash
npx npm-check-updates -u
```

### 🧹 Step 2 – Uninstall Tailwind (old version):
```bash
npm uninstall tailwindcss
```

### 🚀 Step 3 – Install Tailwind v3.4.7:
```bash
npm install -D tailwindcss@3.4.7
```

---

# 🌐 Deployment Process on Netlify

### 🧭 Step 1 – Set Base Directory:
📁 **Base directory**:
```bash
Frontend
```
> ⚠️ If your frontend folder is named something else, use that name instead.

---

### 🔧 Step 2 – Set Build Command:
🏗 **Build command**:
```bash
npm run build
```

---

### 📤 Step 3 – Set Publish Directory:
📂 **Publish directory**:
```bash
Frontend/dist
```

---

✅ You're now ready to deploy your Vite + React app to **Netlify** without the white screen issue!  
Happy coding! 🚀
