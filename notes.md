# NOTE

## Overview

### Entry

- *meta info of app*
- *config of the app*
- *specified by dev*

The **manifest** file

- offer important info and meta data of app
- json format
- sample
  ```json
  {
    "name": "My Extension",
    "version": "2.1",
    "description": "Gets information from Google.",
    "icons": { "128": "icon_128.png" },
    "background": {
      "persistent": false,
      "scripts": ["bg.js"]
    },
    "permissions": ["http://*.google.com/", "https://*.google.com/"],
    "browser_action": {
      "default_title": "",
      "default_icon": "icon_19.png",
      "default_popup": "popup.html"
    }
  }
  ```

### UI

- *extension icon in the menubar*
- *browser-wide/page-wide actions*
- *popup.html when user clicked its icon*

### Behavior/Functionality

- *enhance user loaded web page*
- *dom access*

Content Script

### Config/Options

- *can be tweaked by user*
- *config of the user*

The options page

### Chrome.* APIs
