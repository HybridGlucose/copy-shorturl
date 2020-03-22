# Copy ShortURL Add-on
by Fred Wenzel ``<code@wenzel.io>``

![](./copy-shorturl.png)

Copy ShortURL is a Firefox add-on. It allows you to copy a short URL for the page you are currently visiting to your clipboard at the click of a button.

## Installing
Copy ShortURL is available on the [Mozilla Add-ons website](https://addons.mozilla.org/addon/copy-shorturl/). You can install it with Firefox by simply pressing the Install button there.

## Contributing
Copy ShortURL is open source. If you'd like to contribute, feel free to open or comment on an [Issue on Github](https://github.com/fwenzel/copy-shorturl/issues).

Pull requests welcome!

A special thank-you to all current and previous [contributors](https://github.com/fwenzel/copy-shorturl/graphs/contributors) to this extension. You're awesome.

## Building

We use webpack (to assemble the modules). To develop, run `npm run watch` (to build and automatically re-build the code), and then in a second console, something like `web-ext run` to test in Firefox.

When done, `npm run build` will create a .xpi file for release.

## License
This is free software, &copy; 2010-today Fred Wenzel and licensed under an Apache 2.0 license. For more information, read the file [`LICENSE`](./LICENSE).
