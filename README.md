# Emmanuel Ojeah Webiste

[Emmanuel Ojeah's Website](<https://emmanuelojeah.xyz>)

## To start development

### Prerequisites

- Node (with npm installed)

- gulp installed globally

>- npm install gulp -g

### Modifying the template

You need to install the packages used for the project

>- npm install

You would then need to run the gulp watch on the files (this is now an npm script `start`)

>- npm run start

Navigate to `http://localhost:3000`

Make changes, watch your changes

## To deploy changes online

This website is deployed *Using a manual build/deployment process and deploying to firebase*

- Login firebase with `firebase login` (You need to have firebase installed globally with `npm install firebase-tools -g`)

- Build everything

>- gulp build

- Deploy to firebase

>- firebase deploy
