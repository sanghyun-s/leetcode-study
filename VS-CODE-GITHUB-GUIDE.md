# 📱 VS CODE - How to Push to GitHub (Complete Guide)

## STEP 1: Set Up GitHub Repository

### Create Repo on GitHub
1. Go to https://github.com/new
2. Create repo named: `leetcode-study`
3. Choose **Public** (to showcase on portfolio)
4. ✅ Check **Add a README file**
5. Click **Create repository**
6. Copy the HTTPS URL (looks like `https://github.com/YOUR_USERNAME/leetcode-study.git`)

---

## STEP 2: Open VS CODE

1. Open VS CODE
2. Click **File** → **Open Folder**
3. Navigate to your **Train - LeetCode** folder on Desktop
4. Click **Select Folder**

---

## STEP 3: Initialize Git in VS CODE

### Method A: Using VS CODE Terminal (Easiest)

1. Click **Terminal** → **New Terminal** (or press Ctrl + `)
2. You'll see terminal at bottom of VS CODE

**Run these commands in order:**

```bash
# Initialize git
git init

# Add GitHub remote (paste YOUR repo URL)
git remote add origin https://github.com/YOUR_USERNAME/leetcode-study.git

# Check if it worked
git remote -v
```

You should see output showing your GitHub URL ✅

---

## STEP 4: Add All Problem Files

In the same terminal:

```bash
# Stage all files
git add .

# Check what's being added
git status
```

You should see your 11 .md files listed in green ✅

---

## STEP 5: Make Your First Commit

```bash
# Create commit with message
git commit -m "W1-Day1 | Add 11 problems (7 Easy, 4 Medium) | Arrays, Hash Maps, Two Pointers, Binary Search, Backtracking"
```

---

## STEP 6: Push to GitHub

```bash
# Set main branch and push everything
git branch -M main
git push -u origin main
```

**First time only**, it might ask for login. Follow GitHub's authentication:
- If popup appears → Click **Sign in with GitHub**
- Or paste token if asked

Wait for completion... ✅

---

## STEP 7: Verify on GitHub

1. Go to https://github.com/YOUR_USERNAME/leetcode-study
2. You should see all your files! 🎉

---

## 📝 Daily Workflow (After Day 1)

Whenever you add new problems:

### In VS CODE Terminal:

```bash
# Stage changes
git add .

# Commit with clear message
git commit -m "W1-Day2 | Add [Problem Names] | Easy/Medium | [Patterns]"

# Push to GitHub
git push origin main
```

**That's it!** Your changes appear on GitHub instantly.

---

## 🔄 Commit Message Template

```
W[Week]-Day[Day] | Add [Problem Title 1], [Problem Title 2] | [Difficulty] | [Pattern1], [Pattern2]
```

**Examples:**
```
W1-Day1 | Add Two Sum, Longest Common Prefix, Remove Duplicates | Easy | Hash Map, Two Pointers
W2-Day1 | Add Three Sum, Container with Most Water | Medium | Two Pointers, Greedy
W2-Day2 | Add Combination Sum, Permutations | Medium | Backtracking
```

---

## ⚙️ VS CODE Git Features (Optional)

### Easy Commit Without Terminal

1. Click **Source Control** icon (left sidebar) or press Ctrl + Shift + G
2. You'll see your files ready to commit
3. Click **+** next to each file to stage (or click **+** in header to stage all)
4. Type commit message in the box
5. Press Ctrl + Enter or click ✅ checkmark to commit
6. Click **↑ Push** button to push

---

## ❌ If Push Fails

### Error: "Authentication failed"

```bash
# GitHub changed authentication in 2021
# You need a Personal Access Token

# In terminal:
git config --global credential.helper store
git push origin main
```

Then paste your GitHub Personal Access Token (from GitHub Settings)

### Error: "Refused to connect to ... (permission denied)"

Make sure:
1. HTTPS URL is correct (copy-paste from GitHub)
2. You have push permission
3. Try: `git remote -v` to verify URL

### Error: "Your branch is ahead of origin/main"

```bash
# Just force push (only for first push)
git push -u origin main --force
```

---

## 📊 What Your GitHub Looks Like

Your repo will have:

```
leetcode-study/
├── README.md
├── problems/
│   ├── easy/
│   │   ├── 0001-two-sum.md
│   │   ├── 0014-longest-common-prefix.md
│   │   ├── 0026-remove-duplicates-sorted-array.md
│   │   ├── 0027-remove-element.md
│   │   ├── 0035-search-insert-position.md
│   │   ├── 0066-plus-one.md
│   │   └── 0088-merge-sorted-array.md
│   └── medium/
│       ├── 0011-container-with-most-water.md
│       ├── 0015-three-sum.md
│       ├── 0039-combination-sum.md
│       └── 0046-permutations.md
└── notes/
    └── patterns.md
```

---

## 🎯 Quick Checklist

- [ ] Created repo on GitHub
- [ ] Opened folder in VS CODE
- [ ] Ran `git init`
- [ ] Added remote with `git remote add origin [URL]`
- [ ] Staged files with `git add .`
- [ ] Committed with message
- [ ] Pushed with `git push -u origin main`
- [ ] Verified files on GitHub.com ✅

---

## 💡 Pro Tips

1. **Commit frequently** (after solving each problem)
2. **Use clear messages** (helps track progress)
3. **Push daily** (keeps portfolio updated)
4. **Pull before starting** (if working on multiple machines):
   ```bash
   git pull origin main
   ```
5. **Check status anytime**:
   ```bash
   git status
   ```

---

**You're all set!** Your LeetCode study is now tracked and visible to mentors & recruiters on GitHub 🚀
