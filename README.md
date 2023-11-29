# Recommendations

Provides recommendations for users on what links to visit in a website.
An add-on to pranitshah.cyou's website. Check out [my website](www.pranitshah.cyou) Feel free to fork it and try it out on your website.

- Currently, a programmatic solution is used to avoid recommending the current webpage. This is because google sites prevents cookies, local storage, and other means of storage from persisting across iframes in the site. To bypass this, use google takeout to get your website's html and embed from there with parent urls or embeds with access to the parent url.
- If using the former (which is safer):
  - When calling, use format `thelink?parentUrl=theencodedurl``.
  - For example, https://pranitsh.github.io/recommendations/?parentUrl=https%3A%2F%2Fwww.pranitshah.cyou%2Fwebgpt
  - Use https://www.urlencoder.org/ for encoding and https://www.urldecoder.org/ for decoding.
