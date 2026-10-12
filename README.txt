HaulLog offline app - R&G Excavation  (version 17)
==================================================

This is the full HaulLog app as a web app that works with NO signal after the
first visit. PDF, Excel and ZIP exports are built in; nothing is downloaded
while you use it.

PUT IT ON GITHUB PAGES (one time, free)
---------------------------------------
1. Sign in at github.com. Click + (top right) > New repository.
   Name: haullog     Visibility: Public     then Create repository.
2. On the empty repository page click "uploading an existing file".
3. Unzip this zip. Open the folder and select EVERYTHING INSIDE it
   (index.html, manifest.webmanifest, sw.js, .nojekyll, README.txt and the
   icons folder) and drag it all onto the GitHub page.
   Important: index.html must be at the top level, not inside another folder.
   (If .nojekyll is hidden on your computer, skip it. The app still works.)
4. Click Commit changes.
5. Open the repository's Settings tab (not your account settings) > Pages.
   Under "Build and deployment" set Source = Deploy from a branch,
   Branch = main, Folder = / (root), then Save.
6. After 1-2 minutes the Pages screen shows your link:
   https://YOURNAME.github.io/haullog/

INSTALL ON EACH IPHONE
----------------------
1. Open the link in Safari while you have signal.
2. Share (square with up arrow) > Add to Home Screen > Add.
3. Open HaulLog from the new icon and let it finish loading.
4. Allow Location and Camera when asked.
5. Test: turn on Airplane Mode and open the icon. It should open normally.

ALREADY INSTALLED THE OLD VERSION?
----------------------------------
Upload these files to the same repository (Add file > Upload files; GitHub
replaces the old ones), wait about 10 minutes, then open the app twice with
signal. The first open downloads the update in the background and the second
open shows it. Your saved records are kept. If it still looks old, export
your days first, delete the icon, and add it to the Home Screen again.

ACCESS KEY
----------
The first time the app is opened on a phone it asks for the access key. Paste it once and
tap Unlock; the phone remembers it. It asks again only if the app is deleted and installed
again (or the phone's saved website data is cleared). The same key is needed to delete a Trip
Record (Documents > Trip Records > Delete). The key is NOT stored in this app, only one-way
fingerprints of it. Keep the key private.

LOAD TICKET PHOTOS
------------------
At the loading site, before Depart with load, the Today screen has a Load ticket card.
Tap Take ticket photo (rear camera) as many times as needed. The photos stay with that
load and show in the events list. They are added to the timesheet PDF as extra pages
(2 tickets per page, as many pages as needed) and are also in Export (ZIP) as a Tickets
folder of the original photos. They are stored on the phone and removed when the Trip
Record is deleted.

ERASE ALL APP DATA
------------------
Documents > Erase all app data. It needs the ADMIN key (different from the driver's access
key). It deletes EVERYTHING on that phone: Trip Records, ticket photos, fitness checklists,
projects, vehicles, trailers, clients, locations and settings, and it removes permission to
use HaulLog, so the app asks for the access key again. It cannot be undone. Export anything
you need first. The admin key is NOT stored in this app, only a one-way hash.

MAP (SWIPE RIGHT)
-----------------
Swipe right anywhere on the Today, Projects or Documents screens (or tap the small tab on the
left edge) and Google Maps slides in. It opens on the loading site after you leave the yard and
on the unloading site once you are loaded. Buttons: Me (your GPS position), Load: <site>,
Drop: <site>, a search box, and Open in Maps (hands off to the Google Maps app). It ignores
swipes that start on a signature pad, a typing box, or the very edge of the screen. Back (or a
swipe left on the map's top bar) closes it. The map needs signal; without it the panel says so.
Your location is only used to centre the map, and is not saved.

GOOD TO KNOW
------------
- Always open the app from the Home Screen icon (the Safari tab keeps separate
  records). Deleting the icon deletes that phone's records, so export first.
- Records live on each phone only. Use "Export day" (ZIP) to send a day to the
  office; offline, it sends once the phone has a connection.
- GPS coordinates are saved with each action and appear only in the Excel file.
- To update later: upload the new files, then change VERSION in sw.js
  (for example "haullog-v3") so phones replace their saved copy.
