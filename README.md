# ICMT flat static website with real logo

This version fixes the most likely cause of department/course 404 errors.

- All 192 HTML pages are placed in the repository root.
- Department pages use names like `department-cardiology.html`.
- Course pages use names like `course-ecg-interpretation-from-basics-to-advanced.html`.
- All links were rewritten to the new flat filenames.
- The uploaded ICMT logo is integrated as `icmt-logo.png`.
- CSS and JavaScript remain self-contained inside each HTML file.
- No Vercel build command is required.

## Future edits
Once this is committed to the GitHub repo already connected to Vercel, you never need to reconnect Vercel.
Change only the file(s) you want, commit, and Vercel automatically redeploys.
