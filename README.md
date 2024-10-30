# Running locally

```sh
$ npm run build
# Either manually open `index.html` in your browser, or:

$ php -S localhost:8000
# Then visit `localhost:8000` in your browser.

# To view on another device on the same network (a phone):
$ php -S $(ipconfig getifaddr en0):8000 # This is macOS-specific.
# Then visit the URL that's written to stdout on that other device.
# Will probably look something like `http://192.168.*.*:8000`
```
