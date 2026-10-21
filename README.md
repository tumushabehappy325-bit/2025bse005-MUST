# MUST Online Application Portal - front-end pages

HTML and CSS only (no JavaScript, no backend). Styled after the look of applications.must.ac.ug: lavender background, crest above the university name, "Online Application Portal" pill, white rounded card.

## Files
| File | Page |
|---|---|
| `login.html` | Welcome Back / Sign In |
| `signup.html` | Create Account (details to receive a temporary password) |
| `how-to-apply.html` | Short application steps |
| `application.html` | Application form (6 sections) |
| `style.css` | Shared styles |

## Page flow
`login` -> Create Account -> `signup` -> Create Account -> `login` -> Sign In -> `application` -> Sign out -> `login`
`login` -> How to Apply -> `how-to-apply`. All links are plain hyperlinks; nothing is saved or checked.

## Image slots (placeholders included)
Replace each file with your own image, keeping the **same file name**; no code changes needed.
| File | Used for | Suggested size |
|---|---|---|
| `logo.png` | University crest in a white circle at the top of every page | Square, 400x400 px or larger, PNG |
| `images/background.jpg` | Page background behind the cards | 1920x1080 px or larger, JPG |

To remove the background photo and use the plain lavender gradient, set `--page-bg-image: none;` in `style.css`.

## Run it
Keep all files in one folder and open `login.html` in a browser. Fonts (Inter) load from Google Fonts and need internet; otherwise system fonts are used.

## Notes
- Colours and fonts are variables at the top of `style.css`.
- The programme drop-downs list only four engineering degrees; extend them in `application.html`.
- The form uses standard HTML `required` and input types, so browsers give basic checks on submit.
