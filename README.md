# Ironwise website

The Help, Privacy Policy and Terms of Use pages the app and the App Store link to (docs/decisions.md §30).
Plain HTML, no build step. Contact address on every page: ahmetomertelli@icloud.com.

Published with GitHub Pages from the public repository `omer19telli-blip/ironwise` (only these files; the app's
code stays private):
- https://omer19telli-blip.github.io/ironwise/ (Help / support URL)
- https://omer19telli-blip.github.io/ironwise/privacy/
- https://omer19telli-blip.github.io/ironwise/terms/

Links between the pages are relative, so they work in that subfolder. To update: change the files here, copy them
into a clone of that repository, commit and push; GitHub Pages republishes in about a minute. If the address
changes, update the three URLs in `App/Core/AppInfo.swift`.
