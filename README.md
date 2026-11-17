# Vanisha — Personal Portfolio Website

A four-page responsive portfolio built with semantic HTML5 and CSS.

## Files and folders

```text
vanisha-portfolio/
├── index.html
├── education.html
├── projects.html
├── contact.html
├── css/
│   └── style.css
├── images/
│   └── profile-placeholder.svg
└── README.md
```

## Open the website in Visual Studio Code

1. Download and unzip `vanisha-portfolio.zip`.
2. Open Visual Studio Code.
3. Select **File → Open Folder** and choose the `vanisha-portfolio` folder.
4. Open `index.html`.
5. To preview it, open `index.html` in a browser. You can also install the **Live Server** extension in VS Code, right-click `index.html`, and choose **Open with Live Server**.
6. Use the navigation bar to test all four pages.

## Add your own photograph

1. Choose a suitable profile photo.
2. Copy it into the `images` folder.
3. Rename it `profile.jpg`.
4. In `index.html`, find this line:

   ```html
   <img class="profile-photo" src="images/profile-placeholder.svg" alt="...">
   ```

5. Change the image source to `images/profile.jpg`.
6. Update the `alt` text to describe your photograph.

Use a clear image that you are comfortable making public.

## Publish with GitHub Pages

1. Sign in to GitHub and create a **new public repository**, for example `vanisha-portfolio`.
2. In the repository page, choose **Add file → Upload files**.
3. Upload the contents of the unzipped `vanisha-portfolio` folder. Make sure `index.html` is at the top level of the repository, not inside another nested folder.
4. Add a commit message such as `Add personal portfolio website`, then commit the files.
5. Open the repository's **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select the `main` branch and `/ (root)` folder, then save.
8. Wait for GitHub Pages to publish. The site address will usually look like:

   `https://YOUR-GITHUB-USERNAME.github.io/vanisha-portfolio/`

9. Revisit **Settings → Pages** if you need to find the published website link.

## Personalise before publishing

- Confirm the exact official name of each college/programme and whether both listed programmes are current.
- Confirm the education dates and update any details that change.
- On `projects.html`, edit the suggested tools/methods so they accurately reflect what you used for each assignment.
- Check that your YouTube channel link is added if you want visitors to see it. No channel URL was provided, so it has not been invented.
- Check that the email and LinkedIn profile are the public contact details you want to display.

## Semantic HTML used

The pages use `header`, `nav`, `main`, `section`, `article`, `aside`, `figure`, `figcaption`, `address`, `time`, `table`, and `footer`. Each page has one main content area and a clear heading structure.

Helpful MDN reading:
- https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Structuring_documents
- https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements
