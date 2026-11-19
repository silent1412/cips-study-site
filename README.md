# CIPS Exam Preparation Kit (personal study site)

Static site: `index.html` + `viva-cases.js`. No build step on the host.

## Update content
1. Edit sources in `CIPS book build/` and run the build scripts
   (`build.py` -> `build_front.py` -> `build_dash.py`; `viva/build.py` for viva cases).
2. Copy the resulting `index.html` and `viva-cases.js` into this repo.
3. `git add -A && git commit -m "Update content" && git push`
4. The host redeploys automatically in about a minute.

Progress is saved in the browser (localStorage) on each device.
Use Dashboard -> Backup to copy progress between devices.

`robots.txt` and `_headers` keep search engines from indexing the site.
