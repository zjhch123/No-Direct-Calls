# No Direct Calls

This is the source of this [website](https://zjhch123.github.io/No-Direct-Calls/).

## Build

There is a Github Action in place to deploy any changes to `index.md` to the `index.html` site when pushing to main branch.

To generate the HTML file from Markdown manually, pandoc is used:

```sh
pandoc --standalone --metadata pagetitle="No Direct Calls" --css "assets/css/pandoc.css" --output=index.html index.md
```

## Acknowledgements

This website was inspired by [https://github.com/sbmueller/nohello](https://github.com/sbmueller/nohello). Acknowledgements go to Sebastian Müller.

I often have my thoughts interrupted by inexplicable calls at work, so I've expanded the `Call Etiquette` part of the [original](https://sbmueller.github.io/nohello/) and made it a separate page.

[Stylesheet](https://gist.github.com/forivall/7d5a304a8c3c809f0ba96884a7cf9d7e#file-gh-pandoc-css) licensed under MIT license, Copyright (c) 2016-2017 Emily M Klassen.
