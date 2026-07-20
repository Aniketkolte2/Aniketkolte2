# Setup Guide: Publishing Your Dynamic Profile to GitHub

Follow these steps to activate your custom GitHub Profile README on your GitHub account (`@Aniketkolte2`).

---

### Step 1: Create Your Special GitHub Repository
1. Log in to [GitHub](https://github.com).
2. Create a new repository named **`Aniketkolte2`** (matching your exact username).
3. Set the repository visibility to **Public**.
4. Check **"Initialize this repository with a README.md"**.

---

### Step 2: Upload Your Profile Files
You can upload the files using Git command line or directly on GitHub web:

#### Option A: Using Git Command Line
```bash
# Navigate to your project directory
cd Aniketkolte2-profile

# Initialize Git repository
git init
git branch -M main

# Add GitHub remote
git remote add origin https://github.com/Aniketkolte2/Aniketkolte2.git

# Stage files, commit, and push
git add .
git commit -m "feat: Add dynamic LLM & PyTorch GitHub profile README"
git push -u origin main --force
```

#### Option B: Upload via GitHub Web UI
1. Open your repository `https://github.com/Aniketkolte2/Aniketkolte2`.
2. Click **Add file** -> **Upload files**.
3. Drag & drop `README.md` and the `.github` directory into the repository.
4. Click **Commit changes**.

---

### Step 3: Verify & Customize
1. Visit your profile at `https://github.com/Aniketkolte2`.
2. Verify that the dynamic header, SVG typing text, shields badges, and stats cards load smoothly.
3. Update the LinkedIn / Email links in `README.md` with your exact handle/address.

---

### Step 4: Previewing Locally
To view your profile rendered in GitHub dark mode locally before pushing:
Open `preview.html` in your web browser.
