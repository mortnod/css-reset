<div align="center">
  <br><br>
  <img src="extras/css-reset.svg" width="200" height="200">
  <h1>CSS Reset</h1>
  <p>
    <b>An opinionated reset for modern times</b>
  </p>
  <br><br><br>
</div>

## Getting started

The repo only has one useful file: [reset.css](https://github.com/mortnod/css-reset/blob/main/reset.css). That's it! Copy it in its entirety, or pick the parts you like. You do you.

Almost all parts of the file has some explanation, as well as a link if you want to know more. The following is an example:

```css
@media (prefers-reduced-motion: no-preference) {
  html {
    /* Allow animating using keywords, such as 0 → auto */
    /* https://www.joshwcomeau.com/css/custom-css-reset/#three-enable-keyword-animations-4 */
    interpolate-size: allow-keywords;
  }
}
```

## But...why?

Do you need CSS reset in the year of our lord 2025? Not really. These days the most egregious differences between browsers has been fixed, and most people can get by slapping `* { box-sizing: border-box}` into their CSS and call it a day.

This CSS reset isn't really mean to patch cross-browser quirks. Instead, it aims to solve common annoyances that happen when starting a new project. Annoyances like...

* "Why is the image wider than it's container?"
* "Why is there space beneath the image?! It doesn't have any margin or padding!"
* "Why doesn't my accordion animate properly when opening?"