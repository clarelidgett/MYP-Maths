# MYP Maths Practice: Unit 2 Algebra (v1)

Single-file practice app for MYP 4 (Grade 9) Standard mathematics, Unit 2 Algebra.
Sections: Where am I? (diagnostic), Learn, Practise, Assess, Progress, Review.

## Hosting on GitHub Pages
1. Create a repository (public), e.g. `MYP-Maths`.
2. Upload `index.html`, `u2-algebra.json` and this README to the root.
3. Settings → Pages → Source: Deploy from a branch → Branch: main, folder: / (root) → Save.
4. The app is live at `https://<username>.github.io/MYP-Maths/` within a minute or two. Share that link.

## Privacy
No accounts, no names, nothing sent to a server. Progress is stored in the user's own browser (localStorage) under the key `myp-u2-algebra-v1`.
To move progress between devices: Progress tab → Show export code → paste into Import on the other device.

## Updating questions
The question bank is authored in `MYP_Maths_Question_Bank_U2_Algebra.xlsx` and exported to `u2-algebra.json` (repository root).
`index.html` embeds a copy of that JSON (so it works from a local file as well as a server). After changing the bank, regenerate `index.html` from the template with the new JSON.

## Mastery rule
A subtopic band is mastered after 3 correct answers at that band on at least 2 different days.

## Diagnostic
Each subtopic starts at Level 3-4; correct moves up a band, wrong moves down (once). Level = highest band answered correctly.
Ready = 5-6 or above. Revise = 3-4. Gap = 1-2 or Not yet.
