---
id: update-store-listing
title: Update the store listing of your app
sidebar_label: Update store listing
---

After your app is published on the Overwolf Appstore, you may update your store listing.  
In this article, we'll go over the process of updating your app store listing using the Overwolf developers console.

Note that the process described in this article is only available for apps already published on the Overwolf app store.

:::important Save your work
Once done, don't forget to click the **save** button on the bottom of the screen. Navigation to another tab or page, will cause the loss of any unsaved data.  
Changes submitted will take up to ~30min to process and go live.
:::

## Login to the developers console

After logging to the [Overwolf developers console](#https://console.overwolf.com/), navigate to Store Listing:

![login](../assets/dev-console/update-store/login.png)

## Update store listing

The Store Listing tab lets you update the app details properties displayed in the Overwolf Appstore, including the app's description, screenshots, and more.
Several fields are read-only properties like name, author, and app visibility. Other than that, you can control all your store app's info through this page.

#### Notes
1. A few properties are read-only, and cannot be edited. These are: App name, author, and app visibility. 
2. The app's assets like screenshots, description text and more can be found in the **store** folder of your app. For more details follow this guide on how to [submit your app to the app store for the first time](https://overwolf.github.io/docs/start/submit-your-app-to-the-store#the-store-folder-should-contain).

### Name and Author

Read-only properties: The app's UID.

![name-author](../assets/dev-console/update-store/name-author.png)

### App visibility

When an app is set to **hidden** it becomes "invisible" to users. Only users with a direct download link will be able to access your one-app page in the Overwolf app store and download the app. This setting is usually used during the pre-launch period for final tests.

This property is read-only, if you wish to change your app status to **hidden** please contact the Overwolf team.

![visibility](../assets/dev-console/update-store/hidden.png)

### Short description

Add or edit a short description of your app, with a limit of 180 characters. In this field use plain text only (no HTML or Markdown).

![short-desc](../assets/dev-console/update-store/short-desc.png)

### Full description

Add or edit a full description of your app, used when a user clicks on your app's store tile.  
This field support both plain text, markdown, or HTML format (except H1 and H2 tags).

#### Note
You can also use the text found [description.html file from the "store" folde](../start/submit-your-app-to-the-store#4-descriptionhtml) that you used for uploading your app to the store for the first time.

![full-desc](../assets/dev-console/update-store/full-desc.png)

### Tile

Upload or edit an asset that will be used as an Appstore tile for your app.  
* Should be a JPG format image sized 258X198 at 72PPI.
* Same as the [tile file](../start/submit-your-app-to-the-store#1-tilejpg) from the "store" folder.

![tile](../assets/dev-console/update-store/tile.png)

### Icon 

Upload or edit an asset that wil be used as the app's icon in the Overwolf appstore.  
* Please make sure your chosen icon looks good on both dark and bright backgrounds.
* Should be a PNG format image sized 55X55.
* Same as the [icon file](../start/submit-your-app-to-the-store#2-iconpng) from the "store" folder.

![icon](../assets/dev-console/update-store/icon.png)

### Screenshots 

Include at least one screenshot of your app. These screenshots will be displayed on the app’s page. 
* Should be a JPG format image sized 656x410.
* We automatically compress and optimize your images.  
* Using attractive screenshots of your app will increase its chances of getting noticed and winning hearts, so try including more than one.
* You may add up to 5 screenshots per app. 
* We recommend choosing screenshots that showcase the app's features in a clear way. 
* Same as the [ScreenshotX section](../start/submit-your-app-to-the-store#3-screenshotxjpg) from the "store" folder.

![screenshots](../assets/dev-console/update-store/screenshots.png)
