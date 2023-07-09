# apocrypha.css🍷

![GitHub](https://img.shields.io/github/license/ApocryphaCSS/apocrypha.css?color=fd9696&style=flat-square&logo=gnu)

Just want to write HTML? Or maybe you really don't want to touch too much CSS?
Would you rather want a modular framework so you can pick and choose?

Look no further. Try out apocrypha.css! A classless CSS framework with modular
SCSS so you can tweak as you see fit. Sometimes, it's not enough to be
classless and you want to spice things up. That's why we provide utility classes
when you feel the need to be classy.

## Features

Below are a list of features that apocrypha.css provides:

- Classless semantic HTML styling
- Utility classes
- Responsive design

## Preview

Our [website](https://apocrypha.snows.world) is now live!

NOTE: Since apocrypha.css is still in an alpha stage, the website may not
reflect the most recent changes.

You can also view the [sample.html](https://raw.githubusercontent.com/ApocryphaCSS/apocrypha.css/master/sample.html)
from the repository, which contains a small demonstration that can be viewed by
cloning this project locally.

## Try it out

Wanna try out apocrypha.css? No need for using any package manager, you can
link it in your HTML `<head>` block like so:

```html

<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/@apocrypha/core/css/apocrypha.min.css"
/>
```

If you want to use apocrypha.css in your project, it is available to you on the
npm repository. Run the command below to add it to your project:

`npm install -D @apocrypha/core`

## Manual Compilation

apocrypha.css uses the [`sass`](https://www.npmjs.com/package/sass) package to
compile the project's .scss files.

Ensure a recent version of node.js is present (at least LTS), and run `npm
install` in the project root.

After dependencies installed, the following npm scripts may be used:

- `npm run prepare:scss` to build all .scss files and output to `css/`.
- `npm run prepublish:css-minify` to minify the contents of `css/`
- `npm run test:scss` to watch file changes and automatically rebuild
- `npm run build` to build .scss and minify, in one go.

You can also use your preferred package manager if you wish, such as `yarn` or
`pnpm`! However, be warned that commands might differ. Refer to your package
manager's help page if necessary.
