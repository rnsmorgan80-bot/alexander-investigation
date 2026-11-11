# Publish the Alexander investigation for free

## Part A — Host the activity on GitHub Pages

1. Sign in to https://github.com (a free GitHub account is sufficient).
2. Select **New repository**. Use a simple name such as `alexander-investigation` and make it **Public**; public visibility is required for GitHub Pages on GitHub Free.
3. Open the repository and select **Add file → Upload files**. Upload the website files **from inside** the extracted ZIP so that `index.html` is at the repository root. You can select `index.html`, `.nojekyll` (optional), `assets` and README. If your operating system hides dotfiles or cannot upload the `assets` folder, `index.html` by itself is sufficient for the interactive game.
4. Commit the files to the default branch (normally `main`).
5. Open **Settings → Pages**. Under **Build and deployment**, set **Source = Deploy from a branch**, **Branch = main**, **Folder = /(root)** and click **Save**.
6. GitHub will provide a public address resembling `https://YOUR-USERNAME.github.io/alexander-investigation/`. Open it to confirm the mystery, translations and sliders work before publicising it. The username and exact URL depend on your own GitHub account. This is not a live URL until GitHub Pages has actually published it.

GitHub Pages official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Part B — Create the WordPress.com article (Free plan)

1. In your WordPress dashboard, go to **Posts → Add New** (recommended for a new long-form article) or Pages → Add New (for a permanent landing page).
2. Use the title `Who Killed Alexander the Great? The Mystery at Babylon`.
3. Copy the article from `WORDPRESS_ARTICLE.md` into Paragraph and Heading blocks, or paste the plain HTML text from `WORDPRESS_ARTICLE.html` into a Custom HTML block. Delete the sentence marked `[INSERT WORDPRESS BUTTON HERE...]` or the instruction paragraph before publication.
4. Add `assets/preview.png` as a featured image or inline Image block if you wish.
5. Add a **Buttons block** with text `Explore the Alexander Investigation`. Set the link to your actual published GitHub Pages URL from Part A, with **Open in new tab** enabled if you prefer.
6. Preview on desktop and mobile, test the link, and publish only when satisfied.
7. Optionally add the published WordPress post to your site's navigation as `Interactive Investigations`.

WordPress buttons guide: https://wordpress.com/support/wordpress-editor/blocks/buttons-block/
WordPress Free code restrictions: https://wordpress.com/support/code/

## Suggested SEO / post settings

- Category: Ancient Greece
- Tags: Alexander the Great, Babylon, Diadochi, Hellenistic history, Ancient Greek, Primary sources, Murder mystery
- Excerpt: `In 323 BCE Alexander the Great died at Babylon. Investigate six conflicting sources, read ancient Greek and Latin evidence, and reshape the power struggle that followed.`
- Suggested slug: `who-killed-alexander-the-great`

## Read this before publishing

- GitHub Pages on a Free account needs a **public repository**. Do not include personal information, private classroom documents, pupils' work or licensed images.
- This package has not been pushed to your GitHub account or published to WordPress.com. Your site remains unchanged until you take the steps above.
- The source excerpts and translations are short; original works are linked on the Witnesses tab.
- You can use the activity itself offline by opening `index.html` from the extracted folder.