# CPG Pocket (static site)

`index.html` is the whole app in one file (built with `node dev/build-preview.js index.html --release` from the cpg-pocket source). No server, no database, no patient data leaves the browser.

Deploy on Vercel: import this repo, Framework Preset = "Other", no build command, output directory = root. Every push redeploys.

Content is a draft that a clinician has not yet signed off.
