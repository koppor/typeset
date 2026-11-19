# Issue 36 screenshot

`index.html` shows `panel.html` twice: `#master` loads the sources from `master/`, `#fixed` from `fixed/`.
Copy `src/*.js`, `lib/hypher.js` and `lib/en-us.js` into both folders and apply the proposed fix to `fixed/linebreak.js`.
Captured with `chromium --headless --allow-file-access-from-files --virtual-time-budget=3000 --window-size=760,205 --screenshot`.
