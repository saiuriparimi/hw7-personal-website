# Saiuri Parimi – Personal Website

A simple static personal website for **Saiuri Parimi**, built with HTML and CSS only. It is designed to work with **GitHub Pages** for free hosting.

## What This Project Is

- **Static site**: Plain HTML and CSS, no JavaScript frameworks or build tools.
- **Content**: Home/header, About, Interests, Projects (three example cards), and Contact sections, plus a footer with a copyright notice.
- **Design**: Centered layout, top navigation bar, card-style project section, navy and neutral color palette, and a responsive layout that works well on laptop and smaller screens.

## Project Structure

```
hw7-personal-website/
├── index.html    # Homepage and all page content
├── style.css     # All styling (layout, colors, typography, responsive rules)
└── README.md     # This file
```

## How to Deploy Using GitHub Pages

1. **Push this project to a GitHub repository**  
   - Create a new repository on GitHub (e.g. `hw7-personal-website` or `username.github.io`).  
   - Initialize git in this folder, add all files, commit, and push (see “Git and GitHub steps” below).

2. **Turn on GitHub Pages**  
   - In the repo: **Settings** → **Pages**.  
   - Under **Source**, choose **Deploy from a branch**.  
   - Under **Branch**, select **main** (or **master**) and the **/ (root)** folder.  
   - Save. GitHub will build and deploy the site.

3. **View your site**  
   - After a minute or two, the site will be available at:  
     - **`https://<your-username>.github.io/<repo-name>/`**  
     - If the repo is named **`<username>.github.io`**, then: **`https://<your-username>.github.io/`**

No extra configuration is needed; `index.html` at the root is used as the homepage.

## Running Locally

Open `index.html` in a browser, or use a simple local server (e.g. VS Code “Live Server” or `python -m http.server` in the project folder) to avoid path issues when clicking links.

## License

Content and design are for academic/portfolio use as noted in the assignment.
