# 🚀 SANJAY_OS // GitHub Profile README Setup Guide

Welcome to the deployment guide for your **Cyberpunk / AI Terminal GitHub Profile Repository**. Follow these steps to set up, customize, and deploy your futuristic GitHub profile!

---

## 📋 Table of Contents
1. [Prerequisites](#1-prerequisites)
2. [Step 1: Create the Special Repository](#step-1-create-the-special-repository)
3. [Step 2: Push Repository Code & Assets](#step-2-push-repository-code--assets)
4. [Step 3: Enable GitHub Actions Workflow Permissions](#step-3-enable-github-actions-workflow-permissions)
5. [Step 4: Trigger the Pac-Man / Snake Contribution Graph](#step-4-trigger-the-pac-man--snake-contribution-graph)
6. [Step 5: Customizing Username & Profiles](#step-5-customizing-username--profiles)
7. [Step 6: Color Palette & SVG Customization](#step-6-color-palette--svg-customization)
8. [Troubleshooting & FAQ](#troubleshooting--faq)

---

## 1. Prerequisites

- A GitHub Account (Username: `SanjayGP` or your preferred username).
- Git installed on your local computer.
- An IDE such as VS Code.

---

## Step 1: Create the Special Repository

GitHub provides a special feature: when you create a repository with the **exact same name as your GitHub username**, the `README.md` file in that repository automatically appears on your public GitHub Profile page!

1. Go to [GitHub - New Repository](https://github.com/new).
2. Set **Repository Name** to match your exact GitHub username (e.g. `SanjayGP`).
3. Set Visibility to **Public** 🌐.
4. Check **Add a README file** (or leave unchecked if you plan to push all files directly).
5. Click **Create repository**.

---

## Step 2: Push Repository Code & Assets

In your local project folder (`github-profile-sanjaygp`), initialize Git and push to your new GitHub repository:

```bash
# Navigate into the project folder
cd C:\Users\sanja\.gemini\antigravity\scratch\github-profile-sanjaygp

# Initialize git repository
git init

# Add main branch
git branch -M main

# Link your GitHub repository (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.git

# Stage all files
git add .

# Commit changes
git commit -m "feat: initial commit for SANJAY_OS GitHub profile README"

# Push to GitHub
git push -u origin main
```

---

## Step 3: Enable GitHub Actions Workflow Permissions

To allow `.github/workflows/pacman.yml` to automatically generate and commit your Pac-Man / Snake contribution animation:

1. Navigate to your repository on GitHub.
2. Click on **Settings** ⚙️ at the top right of your repository.
3. In the left sidebar, click **Actions** -> **General**.
4. Scroll down to **Workflow permissions**.
5. Select **Read and write permissions**.
6. Check **Allow GitHub Actions to create and approve pull requests**.
7. Click **Save**.

---

## Step 4: Trigger the Pac-Man / Snake Contribution Graph

Once permissions are set:

1. Click on the **Actions** tab at the top of your repository.
2. Select **Generate Pac-Man & Snake Contribution Graph** from the left workflows list.
3. Click **Run workflow** -> Select `main` branch -> Click **Run workflow**.
4. Wait 1-2 minutes for the green checkmark ✅.
5. The workflow will automatically generate an `output` branch containing `github-contribution-grid-snake-dark.svg`.
6. The `README.md` is already pre-configured to link to `https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-contribution-grid-snake-cyberpunk.svg`.

---

## Step 5: Customizing Username & Profiles

Open `README.md` in your code editor and perform a global search & replace for placeholders:

| Placeholder | Description | Example Replacement |
| :--- | :--- | :--- |
| `SanjayGP` | Your GitHub Username | `SanjayGP` |
| `sanjaygp2004@gmail.com` | Contact Email | `your-email@domain.com` |
| `linkedin.com/in/sanjaygp` | LinkedIn URL | `linkedin.com/in/yourprofile` |
| `leetcode.com/u/sanjaygp` | LeetCode Profile | `leetcode.com/u/yourusername` |
| `codechef.com/users/sanjaygp` | CodeChef Profile | `codechef.com/users/yourusername` |

---

## Step 6: Color Palette & SVG Customization

The design theme uses a curated futuristic cyberpunk palette:

- **Background**: `#0D1117` (GitHub Dark Mode Canvas)
- **Card Background**: `#161B22` / `#0D1626` (Glassmorphism Dark Blue)
- **Primary Glow**: `#00F0FF` (Electric Neon Cyan)
- **Secondary Accent**: `#7000FF` (Neon Violet / Purple)
- **Status Green**: `#00FF66` (System Online Indicator)
- **Text Color**: `#E6EDF3` (Bright White) / `#8B949E` (Muted Metallic Gray)

To edit the SVG banner or avatar:
- Open `assets/banner.svg` or `assets/avatar.svg`.
- You can replace hex colors (`#00F0FF`, `#7000FF`) or text fields directly in any SVG editor or text editor.

---

## Troubleshooting & FAQ

### Q: Why aren't my GitHub Stats showing up?
**A**: Ensure your repository is set to **Public**. If your GitHub account is new or has private commits only, make sure to enable *"Include private contributions"* on your GitHub profile settings.

### Q: The Pac-Man Snake contribution graph shows a 404 image broken link!
**A**: The workflow needs to run at least once to create the `output` branch. Go to your repo's **Actions** tab and trigger the workflow manually as described in [Step 4](#step-4-trigger-the-pac-man--snake-contribution-graph).

### Q: Can I replace the banner with a custom PNG or GIF image?
**A**: Yes! Place your custom banner image inside the `assets/` folder (e.g. `assets/banner.png` or `assets/banner.gif`) and update line 1 of `README.md`:
```html
<img src="assets/banner.gif" width="100%" alt="SANJAY_OS Hero Banner"/>
```

---

*Designed with 💙 for **Sanjay G P***
