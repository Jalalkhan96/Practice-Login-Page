# Practice Login Page

A practice copy of the sliding sign-in / sign-up page design — same layout, kept as a learning snapshot.

## What it is

This repo is a practice rebuild of the animated dual-form login page: a **Create Account** form and a **Sign-in** form inside one card, with sliding "Welcome Back" / "Hello! Friends" toggle panels and social-login icons (Google, Facebook, GitHub, LinkedIn via Ionicons) on the sign-in form. It is a snapshot of the design mid-practice, and it shows: in this copy the container `div` has no `id="container"`, the toggle wrapper's class is spelled `toggle-cntainer`, the sign-up form's social-icon anchors are empty, and `script.js` references an undefined `loginBtnBtn` — so as committed, the slide toggle does not actually run. The finished, working version of this design lives in the Login-Just-Copy repo.

## Files

- `index.html` — the page markup: both forms and the toggle panels.
- `style.css` — the card layout and slide-transition styling for the design.
- `script.js` — the intended toggle logic (adds/removes the `active` class), with the typos noted above.
- `Link` — text file recording the GitHub Pages URL this page was deployed to.
- `README.md` — this file.

## Run it

Open `index.html` in a browser to see the static layout. An internet connection is needed for the Ionicons CDN icons. Note the panel slide does not work in this copy — see "What it is" above.

## Tech

HTML, CSS, JavaScript, Ionicons (via CDN)

## License

MIT — see [LICENSE](LICENSE).
