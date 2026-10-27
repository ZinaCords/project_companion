# Arduino Project Design Companion

Assessment 2 · Arduino Project Portfolio · Stages 1–3 planning companion

A standalone website for students to plan their Arduino assessment portfolio. It uses HTML, CSS and JavaScript, with no build step, server, API keys or external libraries required.

## Publish with GitHub Pages

1. Create a GitHub repository, for example `arduino-project-design-companion`. A public repository is the simplest option for GitHub Pages on GitHub Free.
2. Unzip this package on your computer.
3. In your repository, choose **Add file → Upload files**. Upload the extracted files, not the ZIP. Put `index.html`, `style.css` and `app.js` directly at the top level of the repository, not inside another folder. Include README.md and .nojekyll if your file picker shows it; .nojekyll is optional for this simple site.
4. Commit the uploaded files to the `main` branch.
5. Open **Settings → Pages** in the repository.
6. Under **Build and deployment**, choose **Deploy from a branch**. Select **main** and **/(root)**, then **Save**.
7. Wait for deployment to complete. GitHub will show the live website link in **Settings → Pages**. Use this website link when sharing with students.

Official instructions:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

No GitHub or ChatGPT account is needed for students to visit the published public website.

## Files

- index.html — website shell, title and navigation
- style.css — colours, layout and responsive styling
- app.js — stage content, form fields, saving, image uploads, JSON backups, Word exports and PowerPoint text copying
- .nojekyll — tells GitHub Pages to serve the static files directly
- README.md — this guide

## Student work and moving to the new address

Student responses and uploaded images are saved in the browser on the device being used. They are not stored in GitHub or submitted to the teacher. Download JSON backups regularly.

Browser saves belong to a website address. Work saved at the original ChatGPT-hosted site will not automatically appear at the GitHub Pages address. Before moving, students should download a JSON backup from the original site, then import it on the new site. Word files cannot restore editable project fields.

The package contains the website code only. It contains no student responses, uploaded concept images, account credentials or private hosting settings.

## Updating the site

Edit the relevant files in the repository and commit your changes. GitHub Pages will publish the updated version. Students may need to refresh their browser to see it.
