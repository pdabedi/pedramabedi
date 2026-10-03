# Pedram Abedi — research website

This is a five-page static website for GitHub Pages. No installation or build is needed.

## Put it on GitHub

1. Extract the ZIP on your computer.
2. Open https://github.com/pdabedi/pedramabedi in your browser.
3. Choose Add file > Upload files on the Code tab.
4. Drag the CONTENTS of the extracted folder into the upload area, including the assets folder. index.html must be at the repository's top level, not inside a website folder. README.md can remain as it is.
5. Commit the changes directly to main.
6. In Settings > Pages, keep Deploy from a branch, main, / (root).
7. Visit https://pdabedi.github.io/pedramabedi/ after publishing completes.

All website links are relative, so this works at your repository's subdirectory URL. There are no external fonts, trackers, or JavaScript dependencies.

## Complete the draft

Your supplied portrait and clean lensing image are already included on the home page. Change those later by replacing assets/portrait.jpg or assets/lensing-background.png.

- Personal background: edit about.html. Replace the personal-interests placeholder and check the biographical draft.
- Publication: confirm the manuscript status in publications.html and replace the public-link placeholder with <a href="YOUR_PUBLIC_PAPER_URL">Read the paper</a>. This package excludes the unpublished draft PDF.
- Contact: check pabedi@umich.edu and add any profiles you want to share in contact.html.
- CV: if desired, upload assets/cv.pdf and add <a href="assets/cv.pdf">Download my CV</a> in contact.html.

## Change the text yourself

1. Open your repository on GitHub and click the relevant HTML file.
2. Click the pencil icon to edit.
3. Change the words between the HTML tags. For example, <p>Your new paragraph goes here.</p>. Leave the surrounding tags in place.
4. Click Commit changes and save to main. GitHub Pages republishes the change.

| Page | File to edit |
| --- | --- |
| Home / introduction | index.html |
| About me | about.html |
| Research | research.html |
| Publications / abstract | publications.html |
| Contact information | contact.html |
| Colors, fonts, layout | style.css |

Each HTML tag is on its own line to make the text easier to find. Text editing is through the file editor, rather than a visual drag-and-drop website editor. You can also edit these files on your computer in a plain text editor, preview index.html in a browser, and upload the changed files.

## Content sources

Research text, abstract, and scientific figures were taken from the supplied October 1, 2026 version of SDSSJ1110_Lens_Model.pdf. The abstract retains its scientific content with web-readable math formatting. Home copy and biography are editable drafts. Check the figures and status before publishing. The home page uses the clean lensing field and portrait you supplied. The annotated research figures remain on the research page.

## Edit later

On GitHub, open an HTML file and click the pencil to edit its text, then Commit changes. Every saved change republishes the site. Colors, spacing, and type are in style.css. Navigation appears in each of the five HTML files.
