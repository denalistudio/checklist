# Twitter Cards

*With Twitter Cards, you can attach rich photos, videos and media experiences to Tweets, helping to drive traffic to your website. Simply add a few lines of markup to your webpage, and users who Tweet links to your content will have a “Card” added to the Tweet that’s visible to their followers.* from [Twitter Developer Platform](https://developer.twitter.com/en/docs/twitter-for-websites/cards/overview/abouts-cards)

## [Documentation](https://developer.twitter.com/en/docs/twitter-for-websites/cards/guides/getting-started)
## Implement

Below is a snippet of code to add Twitter Cards to your website. Note that Twitter supports multiple card types, but we’re using the “summary_large_image” card type. To learn more, check their [documentation](https://developer.twitter.com/en/docs/twitter-for-websites/cards/guides/getting-started).


```html
<meta name="twitter:card" content="summary_large_image">
<meta property="twitter:domain" content="example.com">
<meta property="twitter:url" content="https://www.example.com/">
<meta name="twitter:title" content="Example Twitter Card Title">
<meta name="twitter:description" content="Example Twitter Card Description">
<meta name="twitter:image" content="https://www.exaple.com/path/to/image.png">
```

## Test

[Twitter Card Validator](https://cards-dev.twitter.com/validator)