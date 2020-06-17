![](https://repository-images.githubusercontent.com/272579351/bf04cd80-af57-11ea-8580-9aef169d78ab)

> No tooling starter because simplicity is the ultimate sophistication.

A simple front-end skeleton without any tooling. Just start and add tooling as needed.

You can use all the latest JavaScript features, like `async`/`await` and ESM modules in all evergreen browsers.


## Tooling

>**OBS**: You probably don't need tooling in the beginning!

In case you need TypeScript/Babel/SCSS/Whatever, add a `src` folder and have the tools output to `public`.

Another option is to copy/paste snippets or use [unpkg](http://unpkg.com). 


## Fast Google Fonts

If you use Google Fonts use the following snippet in the `head` to load fonts
fast. Replace `[url]` with the actual font url. Read [The Fastest Google Fonts](https://csswizardry.com/2020/05/the-fastest-google-fonts/) for further explanation.

```html
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link rel="preload" as="style" href="[URL]&display=swap" />
<link rel="stylesheet" href="[URL]&display=swap" media="print" onload="this.media='all'" />
<noscript><link rel="stylesheet" href="[URL]&display=swap" /></noscript>
```


# License

MIT © [Terkel Gjervig](https://terkel.com)
