# Lederrosen theme override

`lederrosen-theme.css` contains the existing Lederrosen storefront styles. The Google Fonts `@import` is placed first, as required by CSS syntax.

To load the stylesheet in the Shopware theme settings shown in the screenshot:

1. Set **CSS-Datei laden** to **ja**.
2. Paste the public HTTPS URL of `lederrosen-theme.css` into **CSS-Datei**. The field displays `https://` separately, so paste the remainder if it does not accept a complete URL.
3. Leave **JavaScript-Datei laden** as **nein**; this override has no JavaScript.

`google-site-verification.html` contains the supplied Google Search Console meta tag. Add that tag to the site's HTML `<head>` through the theme or header integration. A CSS file cannot add an HTML meta tag.
