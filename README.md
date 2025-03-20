# Alaska Community Foundation CSuite

This project is a holding space for HTML and CSS that can be copy/pasted to the CSuite site for Alaska Community Foundation.

## Deployment Notes

This project is deployed to the marketing@alaskacf.org Netlify account. The CSS files are referenced in the various head, banner, and footer files. To allow those changes to display on the CSuite site, simply push changes to the repo and they will be automatically published via acfcsuite.netlify.app.

## CSuite Assets

The HTML files in the base of the public directory can be used to copy/paste into CSuite.

## Development Notes

The `public/pages` directory can be used to test CSS styles locally to avoid a ton of copy/paste into CSuite. Feel free to copy new HTML by viewing the page source and replacing what is in the files. You will need to change the CSS references to refer to files on the local path. Swap out the Netlify URL with "../".
