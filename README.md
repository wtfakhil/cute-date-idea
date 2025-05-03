# Date Proposal Website

This is a simple website designed to playfully ask someone out on a date. It consists of three HTML pages:

* **index.html:** The initial proposal page.
* **yes.html:** A page displayed after the user accepts the proposal, asking for the date location preference.
* **MCD.html:** A page confirming the date at McDonald's (displayed after choosing "McDonalds" on yes.html).

## Files Included

* **index.html**
    * Asks the user "Hey cutie! Do you wanna go out with me?".
    * Includes "Yes" and "No" buttons.
    * The "No" button has JavaScript functionality to move its position randomly on the page when hovered over or clicked, making it difficult to click "No".
    * A "Yes" button redirects to `yes.html`.
    * Displays a cute animated GIF.
    * Includes a link to an Instagram profile.

* **yes.html**
    * Asks the user "Where do you want to go?".
    * Includes "McDonalds" and "Shopping" buttons.
    * The "Shopping" button, similar to the "No" button in `index.html`, moves randomly.
    * The "McDonalds" button redirects to `MCD.html`.
    * Displays the same cute animated GIF as `index.html`.
    * Includes a link to an Instagram profile.

* **MCD.html**
    * Displays a confirmation message "Yeeyy! Finally".
    * Shows an image related to the date.
    * Includes a button with the text "yayy MCD here we Comeeeeeee !".

* **style.css** (Not provided in the file list, but assumed to exist)
    * This file would contain the CSS styling for all the HTML pages, controlling the layout, colors, and fonts.

## How to Use/Run

1.  **Obtain the Files:** Download or copy the HTML files (`index.html`, `yes.html`, `MCD.html`) and the `style.css` file (if available) into the same directory.
2.  **Open `index.html`:** Open the `index.html` file in a web browser.
3.  **Interact:** The user can click the "Yes" button to proceed or try to click the moving "No" button.  The subsequent pages will guide the user through the "date" selection process.

## Customization

* **Text:** You can change the text content on each page by editing the HTML files directly.  For example, change the initial question, the button labels, or the confirmation messages.
* **Images:** Replace the GIF and other images by modifying the `src` attribute of the `<img>` tags in the HTML.  Ensure the image files are in the correct relative path.
* **Styling:** Modify the `style.css` file to change the visual appearance of the pages (colors, fonts, layout, etc.).
* **Links:** Update the Instagram link with the desired profile.
* **Behavior:** The JavaScript functions (`nextPage()`, `moveButton()`) can be altered to change the page navigation or the behavior of the moving button.  For example, you could add more complex animations or redirect to different URLs.
