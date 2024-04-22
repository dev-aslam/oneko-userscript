# Oneko.js Tampermonkey

This Tampermonkey script adds an interactive cat animation that follows your mouse cursor on webpages, inspired by the [oneko.js](https://github.com/adryd325/oneko.js) project originally created by [adryd325](https://github.com/adryd325).

## Installation

### Install Tampermonkey

If you haven't already, install Tampermonkey for your browser from [tampermonkey.net](https://www.tampermonkey.net/).

### Install the User Script

Click [here](https://github.com/dev-aslam/oneko-userscript/raw/main/oneko.user.js) to install the Oneko.js Tampermonkey userscript.

### Activate the Script

Once installed, visit any webpage. The script should automatically add an interactive cat animation that follows your mouse cursor.

### Customizing Script Execution

#### Showing the Cat on Specific Sites

If you want the cat animation to appear only on specific websites, you can use the `@match` directive in the script metadata. Modify the `@match` directive to specify the URLs of the websites where you want the cat animation to be active.

Example `@match` directive:

```javascript
// @match        https://example.com/*
// @match        https://subdomain.example.com/*
// @match        https://*.example.com/*
// @match        https://example.com/page1
// @match        https://example.com/page2
// @match        http://localhost:3000/*
```

Modify the above examples to match the URLs of the specific websites where you want the cat animation to show. This will limit the script's execution to those specific websites.

#### Excluding the Cat on Specific Sites

Conversely, if you want to prevent the cat animation from appearing on certain websites, you can use the @exclude directive. Add @exclude directives to specify URLs or patterns where the script should not run.

Example `@exclude` directive:

```javascript
// @exclude      https://example.com/*
// @exclude      https://subdomain.example.com/*
// @exclude      https://anotherwebsite.com/*
```

Add `@exclude` directives to prevent the script from running on specific websites or URL patterns. This will exclude those websites from the script's execution.

## Disabling the Script

To disable the userscript temporarily or permanently:

1. Click on the Tampermonkey icon in your browser's toolbar.
2. Go to the Tampermonkey Dashboard.
3. Locate the "Oneko.js Tampermonkey" script in the list of installed scripts.
4. Toggle the script's status to disable or enable it as needed.

## Notes

- This script is inspired by the `oneko.js` project and recreates a similar interactive experience with a cat animation.

## Disclaimer

This userscript modifies the appearance and behavior of webpages. Use it responsibly and be aware that changes made by this script may affect your browsing experience.

```

```
