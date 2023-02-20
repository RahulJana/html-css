# Different components of Emmet

## 1. [DOCTYPE](https://developer.mozilla.org/en-US/docs/Glossary/Doctype)

In HTML, the doctype is the required `<!DOCTYPE html>` preamble found at the top of all documents. Its sole purpose is to prevent a browser from switching into so-called [quirks mode](https://developer.mozilla.org/en-US/docs/Web/HTML/Quirks_Mode_and_Standards_Mode) when rendering a document; that is, the `<!DOCTYPE html>` doctype ensures that the browser makes a best-effort attempt at following the relevant specifications, rather than using a different rendering mode that is incompatible with some specifications.

## 2. [html](https://www.w3schools.com/tags/tag_html.asp#:~:text=The%20tag%20represents%20the,assist%20search%20engines%20and%20browsers.)

The `<html>` tag represents the root of an HTML document. The `<html>` tag is the container for all other HTML elements (except for the `<!DOCTYPE>` tag).

## 3. [charset](https://www.w3schools.com/tags/att_meta_charset.asp)

The `charset` attribute specifies the character encoding for the HTML document. The HTML5 specification encourages web developers to use the `UTF-8` character set, which covers almost all of the characters and symbols in the world.

## 4. [http-equiv](https://www.w3schools.com/tags/att_meta_http_equiv.asp)

The `http-equiv` attribute provides an HTTP header for the information/value of the content attribute. The `http-equiv` attribute can be used to simulate an HTTP response header.

## 5. [X-UA-Compatible](<https://www.thoughtco.com/xua-compatible-meta-tag-3469059#:~:text=X%2DUA%2DCompatible%20is%20a,IE%208%20(standards%20view).>)

`X-UA-Compatible` is a document mode meta tag that allows web authors to choose what version of Internet Explorer the page should be rendered as. It is used by Internet Explorer 8 to specify whether a page should be rendered as IE 7 (compatibility view) or IE 8 (standards view).
Current value of IE we use in modern scripts is `IE=edge`.

## 6. [viewport](https://www.w3schools.com/css/css_rwd_viewport.asp)

-   The viewport is the user's visible area of a web page. The viewport varies with the device, and will be smaller on a mobile phone than on a computer screen.

-   Before tablets and mobile phones, web pages were designed only for computer screens, and it was common for web pages to have a static design and a fixed size. Then, when we started surfing the internet using tablets and mobile phones, fixed size web pages were too large to fit the viewport. To fix this, browsers on those devices scaled down the entire web page to fit the screen.

-   The `width=device-width` part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).
-   The `initial-scale=1.0` part sets the initial zoom level when the page is first loaded by the browser.

## 7. [content](https://html.com/attributes/meta-content/)

The `content` attribute of the `meta` element contains its values. This is used with the name attribute to specify metadata about the page.
