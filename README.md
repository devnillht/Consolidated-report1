# 📊 Teacher Report Builder (Gemini Edition)
**Developed by Devnil Chatterjee | Sunbeam School, Lahartara**

AI-powered teacher performance report generator — powered by **Google Gemini (FREE)**.

---

## 🔑 Get Your FREE Gemini API Key (2 minutes, no card needed)

1. Go to **https://aistudio.google.com/app/apikey**
2. Sign in with any Google account
3. Click **"Create API Key"**
4. Copy it — looks like `AIzaSy...`

**Free limits:** 1,500 requests/day — handles 80+ files/day easily ✅

---

## 🚀 Deploy on Vercel (Free, Recommended)

### Step 1 — Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR_USERNAME/teacher-report-builder.git
git push -u origin main
```

### Step 2 — Deploy on Vercel
1. Go to **vercel.com** → Sign in with GitHub
2. Click **Add New Project** → Import your repo
3. Add **Environment Variable:**
   ```
   GEMINI_API_KEY = AIzaSy-YOUR_KEY_HERE
   ```
4. Click **Deploy** ✅

Live at: `https://your-app.vercel.app`

---

## 💻 Run Locally

```bash
npm install
cp .env.example .env
# Edit .env — paste your Gemini key

npm run build
npm start
```
Open http://localhost:3000

---

## 📊 Capacity at Your Volume (80 files/day)

| Metric | Value |
|---|---|
| API calls per file | ~3 calls |
| 80 files/day | ~240 calls/day |
| Free daily limit | 1,500 calls/day |
| Headroom | 6x buffer ✅ |
| Cost | $0 forever |

---

## 📁 Supported Files
- PDF (`.pdf`) — native Gemini support ✅
- Word Document (`.docx`, `.doc`) — via Mammoth ✅
