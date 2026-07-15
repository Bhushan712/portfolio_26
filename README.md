# Call Center Executive – Theory Quiz (H5P on GitHub Pages)

This folder makes your H5P quiz available at a public link via GitHub Pages,
using the h5p-standalone player (no server / no H5P account needed to VIEW it).

## One-time setup (you only need to do steps 1-4 once)

1. Go to https://h5p.com and sign up for the free trial (or use your existing account).
2. Create a new content item -> choose "Question Set".
3. Add your 38 questions as "Multiple Choice" sub-questions inside the Question Set.
   (Use the Call_Center_Executive_Theory_Test.docx question bank I gave you earlier —
   just copy each question, its 4 options, and mark the correct answer.)
4. Save, then use the "..." menu on the content -> Export -> Download as .h5p file.
   This gives you a file like "call-center-quiz.h5p".

## Adding it to this site

5. A `.h5p` file is just a ZIP file. Rename `call-center-quiz.h5p` to
   `call-center-quiz.zip` and unzip it.
6. Copy EVERYTHING that comes out of that zip (h5p.json, the `content` folder,
   and all the `H5P.XXX-x.y` library folders) directly into:
       h5p-content/call-center-quiz/
   (replacing the placeholder file that's there now)
7. Commit and push this whole `h5p-quiz` folder into your existing repo:
       github.com/Bhushan712/portfolio_26
   (e.g. as a subfolder like `portfolio_26/quiz/`)
8. Make sure GitHub Pages is enabled for that repo (Settings -> Pages -> Deploy from branch).
9. Your students can then open:
       https://bhushan712.github.io/portfolio_26/quiz/
   (adjust the path to wherever you placed this folder in the repo)

That's it — no login required for students, it just plays in the browser.
