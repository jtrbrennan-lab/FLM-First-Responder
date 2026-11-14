MEDIC 1 STUDY DECK - PHONE APP
==============================

This folder is a complete installable web app. Once it's online, trainees
add it to their home screen and it behaves like a regular app: its own
Medic 1 icon, full screen, and it works with no signal after the first open.


1. PUT IT ONLINE (once, by whoever manages it)
----------------------------------------------
The app has to be served from an https:// web address. Opening
index.html straight from a file won't give you the icon or offline mode.

Upload EVERYTHING in this folder (keep the "icons" folder next to
index.html) to any free static web host. For example, GitHub Pages:

  a. Sign in at github.com and create a new public repository
     (for example "medic1").
  b. Click "uploading an existing file", drag in all the files and the
     icons folder from this folder, and commit.
  c. Go to Settings > Pages. Under "Build and deployment", set Source to
     "Deploy from a branch", choose the "main" branch and "/ (root)",
     and save.
  d. After a minute or two, the page shows your link, something like
     https://YOUR-NAME.github.io/medic1/

Other static hosts (Netlify, Cloudflare Pages, etc.) work the same way:
upload the folder and share the https link they give you.


2. SHARE THE LINK WITH TRAINEES


3. INSTALL ON A PHONE (each trainee, once)
------------------------------------------
iPhone / iPad: open the link in Safari, tap the Share button, then
               "Add to Home Screen" > Add.
Android:       open the link in Chrome, tap "Install app" when it
               appears (or the menu > "Add to Home screen" /
               "Install app").

The app also shows these instructions until it's installed.


GOOD TO KNOW
------------
- Each trainee's class date and progress are saved on their own phone.
  Nothing is sent anywhere, and no account is needed.
- Deleting the app from the home screen also deletes its saved progress.
- To update the cards later: replace the files on the host, then open
  sw.js and change VERSION (for example "medic1-v1" to "medic1-v2") so
  installed phones download the new version the next time they open the
  app with a connection.
- Cards are based on the FLM TCCC / Combat Lifesaver Supplement v2.0
  (August 2023). Every card cites its page.
