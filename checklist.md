# Checklist

An internal checklist we use to ensure quality for our clients

- [ ] The DOCTYPE is correctly declared as `<!DOCTYPE html>` and is present on all pages.
- [ ] A `<title>` tag is present on all pages.

## head

- [ ] Facebook Open Graph meta tags are present on all pages. [Learn how](resources/open-graph.md)
- [ ] Twitter Cards meta tags are present on all pages. [Learn how](resources/twitter-cards.md)

## optimisation

- [ ] Test your website on PageSpeed Insights and score at least 90 (if possible). [PageSpeed Insights]([https://pagespeed.web.dev)

## accesibility

- [ ] Make sure all images have appropriate alt text. [Learn more](resources/alt-text.md)
- [ ] Pass the WAWE web accessibility test. [WAWE](https://wave.webaim.org)

## CSS

- [ ] Use Stylelint to check for any errors. [Stylelint](https://stylelint.io)
- [ ] Minify all css files and add the `.min` suffix. [Tool](https://github.com/ben-eb/cssnano)

## JavaScript

- [ ] Avoid any inline JavaScript in your HTML document.
- [ ] Don't forget to add the `<noscript>` tag for users that turned off scripting in their browser. [Learn more](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/noscript)
- [ ] Use ESLint to check for any errors. [ESLint](https://eslint.org)
- [ ] Minify all JavaScript files and add the `.min` suffix. [Tool](https://github.com/mishoo/UglifyJS2)
