# add-css-js-from-root-web

This SPFx Extension is to provide CSS and JS file on a modern site for custom code, from root website i.e. `https://{tenant}.sharepoint.com`, for all sites/webs to use the same JS/CSS

## More Info

more info at [SPXF-EX-assJsCss](https://github.com/bresleveloper/SPXF-EX-assJsCss/)

## Set your site
Change paths in:

steps:
* add to app catalog (create if needed, add to the "distribute to SharePoint"), dont click the checkbox
* add the app (site content -> new -> app)
* create DocumentLibrary named `rootCustomFiles` (can be changed in the .ts file)
* add jss/css files there, names must be `rootCustomSiteScript.js`, `rootCustomSiteScript.css`


### commands
once - `gulp trust-dev-cert`


`gulp serve`


`gulp build`
`gulp bundle --ship`
`gulp package-solution --ship`


`document.querySelector("#workbenchPageContent").style.maxWidth='1200px'`



`git add .`
`git commit -m "comment"`
`git push -u origin master`




