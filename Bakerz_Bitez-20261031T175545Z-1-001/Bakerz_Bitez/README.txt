BAKERZ & BITEZ
README
==============================

Tagline: Where smiles are served daily.

1. PROJECT OVERVIEW
-------------------
Bakerz & Bitez is a responsive, multi-page bakery and cafe website.
This project is intended as a front-end website using HTML, CSS,
JavaScript, Bootstrap and jQuery.

The basic website does not require a custom backend or database.
Some features that need shared customer data or secure processing
will require a backend or a suitable third-party service.

2. TECHNOLOGIES
---------------
- HTML5: website page structure and content
- CSS3: styling, layout and responsive appearance
- JavaScript: interactive website behaviour
- Bootstrap: responsive grid and UI components
- jQuery: DOM manipulation, events and effects

Bootstrap and jQuery may require an internet connection if they
are included through a CDN.

3. PROJECT STRUCTURE
--------------------
Bakerz_Bitez/
|
|-- index.html             Main home page
|-- html/                  Additional HTML pages
|   |-- about.html         About the bakery
|   |-- contact.html       Contact and feedback
|   |-- deals.html         Deals and combo offers
|   |-- menu.html          Food and cafe menu
|
|-- css/                   Stylesheets
|-- js/                    JavaScript files
|-- assets/                Images and other static assets
|   |-- images/            Food, drinks, deals and site images
|
|-- README.txt             This file
|-- Developer_Guide.docx   Detailed developer documentation

NOTE:
The exact filenames may differ in the supplied source archive.
Keep the existing folder names and update relative paths if you
move or rename any files.

4. HOW TO RUN THE WEBSITE
-------------------------
1. Extract the project archive to a folder on your computer.
2. Open the extracted project folder in Visual Studio Code or
   another code editor.
3. Make sure index.html and the html, css, js and assets folders
   are present.
4. Open index.html in a modern web browser.
5. For local development, you can use the VS Code Live Server
   extension or another static local server.
6. Test all pages, navigation links, images and interactive
   features.

No build process is normally required for this front-end project.

5. PAGE DESCRIPTION
-------------------
- index.html: Main landing page and featured sections.
- html/menu.html: Menu and cafe items.
- html/deals.html: Deals, combos and seasonal promotions.
- html/contact.html: Contact information, feedback and outlet links.
- html/about.html: About the Bakerz & Bitez brand.

6. ADDING OR CHANGING CONTENT
-----------------------------
- Edit the relevant HTML page to change text and page content.
- Update the matching CSS file to change appearance.
- Update the matching JavaScript file to change interactions.
- Store new images inside assets/images/.
- Use descriptive image filenames.
- Add meaningful alt text to images.
- Compress large images to improve loading speed.
- Check image paths carefully after moving files.

Example image path:
- From index.html: assets/images/cake.jpg
- From a page inside html/: ../assets/images/cake.jpg

7. RESPONSIVE DESIGN
--------------------
Use Bootstrap responsive grid classes and utilities when adding
new sections or cards. Use img-fluid for responsive images.
Test the website on mobile, tablet and desktop screen sizes.
Avoid fixed widths that cause horizontal scrolling.

8. IMPORTANT FEATURE NOTES
--------------------------
WHATSAPP ORDERING:
A WhatsApp link can open a prepared order message. The customer
must review and send the message in WhatsApp. A front-end-only
website cannot silently send a WhatsApp message on the customer's
behalf.

FEEDBACK:
Feedback saved in browser localStorage is stored only in that
browser and device. It is not automatically shared with customers
using other devices. Shared feedback needs a backend or a suitable
third-party service.

THEME:
A theme preference stored in browser storage is local to the
browser profile. Each page must load the same theme logic for a
consistent appearance.

OUTLET MAPS:
Google Maps links can open outlet locations. Some Google Maps API
features require an API key and may require billing and domain
configuration.

RESERVATIONS AND ONLINE ORDERS:
A front-end-only site cannot securely store reservations, process
payments or manage inventory. These features need a backend or a
trusted third-party service.

9. TROUBLESHOOTING
------------------
Images are missing:
- Check the image filename, extension and capitalization.
- Check the relative path from the current HTML page.

CSS is not applying:
- Check the stylesheet link path.
- Refresh the browser or perform a hard refresh.

JavaScript is not working:
- Open browser Developer Tools (usually F12).
- Check the Console for errors.
- Confirm scripts load in the correct order, including jQuery
  before scripts that depend on it.

Page layout breaks on mobile:
- Check Bootstrap column classes.
- Use responsive widths and img-fluid.
- Test at different screen sizes.

Links do not work:
- Check the href path and the location of the target page.
- Remember that pages inside html/ are in a subfolder.

10. DEVELOPMENT CHECKLIST
-------------------------
[ ] All pages open correctly.
[ ] Navigation links work.
[ ] Images load correctly.
[ ] Layout works on mobile, tablet and desktop.
[ ] Menu and deal details are accurate.
[ ] Forms show useful validation messages.
[ ] WhatsApp links use the correct business number.
[ ] Outlet map links point to the correct locations.
[ ] No private API keys or passwords are exposed.
[ ] A backup of the completed project is saved.

11. SUPPORTING DOCUMENTATION
-----------------------------
See Developer_Guide.docx for more detailed information about
the project structure, technologies, setup, maintenance,
troubleshooting and future improvements.

12. PROJECT MAINTENANCE
-----------------------
Before making major changes, create a backup of the complete
project folder. Change one feature at a time and test the site
after every update. Keep filenames, folder names and relative
paths consistent.

End of README
