# Alaska Community Foundation CSuite

This project is a holding space for HTML and CSS that can be copy/pasted to the CSuite site for Alaska Community Foundation. Make sure all changes are added to this GitHub repository before updating in CSuite sandbox or live. Changes made to the sandbox can be overwritten at any time by syncing Csuite live to sandbox. That's why it's very important to have a backup here.

## Deployment Notes

This project is deployed to the marketing@alaskacf.org Netlify account. The CSS files are referenced in the various head, banner, and footer files. To allow those changes to display on the CSuite site, simply push changes to the `main` branch, and they will be automatically published via acfcsuite.netlify.app.

Non-technical folks can make changes to files directly in GitHub. Go to the file you want to edit, and click the pencil button in the top right. When you're done making changes, click the "Commit changes..." button, and add a message explaining the edits you made. Choose the option to "Commit directly to the main branch" if you only have one file to change. Otherwise, you will want to create a new branch and make a pull request. This should allow you to add more than one file to your new branch. Once all of your changes have been made to your branch, go to the "Pull requests" tab and merge your changes from the "Conversation" tab of the pull request. It's best to review all of your changes in the "Files changed" tab before merging your branch into the `main` branch. Once you have merged your branch into the `main` branch, the changes will be automatically published via acfcsuite.netlify.app.

## Development Notes

The `public/pages` directory can be used to test CSS styles locally to avoid a ton of copy/paste into CSuite. Feel free to copy new HTML by viewing the page source and replacing what is in the files. You will need to change the CSS references to refer to files on the local path. Swap out the Netlify URL with "../".

## CSuite

The HTML files in the base of the `public/` directory can be used to copy/paste into CSuite under Communication > Styles, and are named to correspond with the various content items in CSuite.

### CSuite Colors

There are three sets of colors that are used in the CSuite site:

1. acf_colors
    - Button Primary: `#51A07B`
    - Button Primary Hover: `#A778AA`
    - Button Secondary: `#723883`
    - Button Secondary Hover: `#707070`
    - White for all other values: `#FFFFFF`
2. affiliate_colors
    - Button Primary: `#723883`
    - Button Primary Hover: `#B494BA`
    - Button Secondary: `#585858`
    - Button Secondary Hover: `#A9A9A9`
    - White for all other values: `#FFFFFF`
3. portal_colors
    - Button Primary: `#51A07B`
    - Button Primary Hover: `#A778AA`
    - Button Secondary: `#51A07B`
    - Button Secondary Hover: `#A778AA`
    - White for all other values: `#FFFFFF`

### Key Testing Pages

The following includes pages that are used to test the CSuite site:

- **Giving Hub / Donation**
    - All Funds: [https://alaskacf.fcsuite.com/erp/donate](https://alaskacf.fcsuite.com/erp/donate)
    - Fund List: [https://alaskacf.fcsuite.com/erp/donate/list?showlist=1](https://alaskacf.fcsuite.com/erp/donate/list?showlist=1)
    - Single Fund:
        - Ketchikan Affiliate Fund: [https://alaskacf.fcsuite.com/erp/donate/create/fund?funit_id=1382](https://alaskacf.fcsuite.com/erp/donate/create/fund?funit_id=1382)
        - The Alaska Fund: [https://alaskacf.fcsuite.com/erp/donate/create/fund?funit_id=1067](https://alaskacf.fcsuite.com/erp/donate/create/fund?funit_id=1067)
- **Affiliate / Organization**
    - Chilkat Valley Community Foundation: [https://alaskacf.fcsuite.com/erp/donate?sorg_id=1000](https://alaskacf.fcsuite.com/erp/donate?sorg_id=1000)
- **Fund Manager**
    - How to log into the Fund Portal
        
        The Mostly Serious devops@mostlyserious.io user must be granted access to one or more funds. This may need to happen every time the live site is synced back to sandbox.
        
    - **Portal Login**: [https://alaskacf.fcsuite.com/erp/portal/](https://alaskacf.fcsuite.com/erp/portal/)
    - **Portal Home**: [https://alaskacf.fcsuite.com/erp/portal/fundadvisor?profile_id=85730](https://alaskacf.fcsuite.com/erp/portal/fundadvisor?profile_id=85730)
    - **Grant Request Process**: [https://alaskacf.fcsuite.com/erp/portal/fundadvisor/grant_request?funit_id=1067&profile_id=85730](https://alaskacf.fcsuite.com/erp/portal/fundadvisor/grant_request?funit_id=1067&profile_id=85730)

