# Professional Portfolio Template

A modern, responsive, and professional personal portfolio website built with vanilla HTML5, CSS3, and JavaScript.

## Project Structure

```text
portfolio/
│
├── index.html          # Main HTML structure
├── css/
│   └── style.css       # Custom styling and animations
├── js/
│   └── script.js      # Interactive features and form validation
├── assets/
│   ├── images/         # Place your profile and project images here
│   └── icons/          # Favicon and other icons
├── resume/
│   └── resume.pdf      # Your professional resume
└── README.md           # Project documentation
```

## How to Customize

Open the files in a text editor (like VS Code) and look for comments starting with `EDIT`:

- **Name & Title:** Search for `EDIT NAME` and `EDIT TITLE` in `index.html`.
- **Profile Photo:** Replace the `src` in the `<img>` tag under the `hero-image` div.
- **Skills:** Update the `style="width: XX%"` in the progress bars within the `skills` section.
- **Experience & Education:** Update the text within the `timeline` and `about` sections.
- **Contact Details:** Update the email, location, and social links in the `contact` section.
- **Resume:** Replace `resume/resume.pdf` with your actual PDF file.

## Local Development

### Option 1: Using VS Code (Recommended)
1. Open the `portfolio` folder in Visual Studio Code.
2. Install the **Live Server** extension.
3. Right-click on `index.html` and select **"Open with Live Server"**.

### Option 2: Simple Browser Open
1. Navigate to the `portfolio` folder on your computer.
2. Double-click `index.html` to open it in your default web browser.

## Deployment to Netlify

### Option 1: Drag-and-Drop (Fastest)
1. Create a free account at [Netlify](https://www.netlify.com/).
2. Log in and go to the **Sites** tab.
3. Drag the entire `portfolio` folder into the deployment box.
4. Your site will be live in seconds!

### Option 2: GitHub Integration (Best for Updates)
1. Upload your code to a GitHub repository.
2. On Netlify, click **"Add new site"** > **"Import an existing project"**.
3. Connect your GitHub account and select the repository.
4. Click **"Deploy site"**. Netlify will automatically update your site whenever you push changes to GitHub.

### Custom Domain
1. In your Netlify site settings, go to **"Domain management"**.
2. Click **"Add custom domain"** and follow the instructions to link your own domain (e.g., `www.yourname.com`).
