## Repo for CapRover One Click Apps

The main difference from https://Awes0meHub.github.io/caprover-one-click-apps is the removal of apps that are considered NSFW.

### How to add this repo:

-   Login to your CapRover dashboard
-   Go to **apps** and click on **One-Click Apps/Databases** and scrolldown to the bottom
-   Under **3rd party repositories:** copy `https://easaw.github.io/caprover-apps` and paste it in to the text box
-   Click the **_Connect New Repository_** button

---------

To create your own repository:
- Fork this repository
- Delete all existing apps (to avoid duplicate apps), and add your own apps.
- Run `npm install -g pnpm` or `sudo npm install -g pnpm`
- Run `pnpm i`
- Run `pnpm run validate_apps`
- Run `pnpm run formatter-write`
- Run `pnpm run build` 
- Now you can host the static content placed in `./dist` directory anywhere you want, the official repo uses github pages to publish the content. Make sure to update [CNAME](https://github.com/easaw/caprover-one-click-apps/blob/master/public/CNAME) to your own URL if you decide to do so.
