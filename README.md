# anastasia-english

Static landing page for **anastasia-english** — online English lessons with Anastasia Viktorovna.

## Files

```text
anastasia-english/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    └── images/
        └── ana-mascot.png
```

## How to publish on GitHub Pages

1. Create a GitHub repository named `anastasia-english`.
2. Upload all files and folders from this project to the repository root.
3. Make sure the main file is named exactly `index.html`.
4. Go to **Settings → Pages**.
5. In **Source**, select **Deploy from a branch**.
6. In **Branch**, select `main`.
7. In **Folder**, select `/root`.
8. Click **Save**.

The public link will look like:

```text
https://eamceo.github.io/anastasia-english/
```

## Notes

- The website is fully static and does not require backend, database, npm, React, Next.js or build tools.
- Language switcher works through `script.js` and supports RU / EN / BY without page reload.
- Contact form is static: after submit, it shows a friendly confirmation message.
- Replace placeholder links in `index.html` with real Telegram, WhatsApp, Instagram and Email contacts.
- Replace `assets/images/ana-mascot.png` with the final mascot image if needed, keeping the same file name.
