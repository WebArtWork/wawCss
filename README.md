<p align="center">
  <a href="https://github.com/WebArtWork/wawCss">
    <img src="https://avatars3.githubusercontent.com/u/16809893?s=200&v=4" alt="waw-logo" width="72" height="72">
  </a>
</p>
<h3 align="center">Web Art Work</h3>
<p align="center">
  Functional, interactive and easy-to-use front-end framework for fast and quality web development.
  <br>
  <a href="https://github.com/WebArtWork/wawCss"><strong>Explore waw-docs »</strong></a>
  <br>
  <br>
  <a href="https://github.com/WebArtWork/wawCss">Report bug</a>
  ·
  <a href="https://github.com/WebArtWork/wawCss/issues/new?template=feature.md&labels=feature">Request feature</a>
  ·
  <a href="https://github.com/WebArtWork/wawCss">Themes</a>
  ·
  <a href="https://github.com/WebArtWork/wawCss">Blog</a>
</p>
## Table of contents
- [Start](#start)
- [Status](#status)
- [What's included](#whats-included)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Community](#community)
- [Versioning](#versioning)
- [Copyright and license](#copyright-and-license)
## What's included
What's in it
As part of the download you will find directories and files, compiled and minimized options. Starting maps are available for use with developer tools in different browsers.
```text
WebArtWork/wawCss
└── atoms/
    │   ├── README.md
    │   ├── _background.scss
    │   ├── _beside.scss
    │   ├── _color.scss
    │   ├── _float.scss
    │   ├── _font.scss
    │   ├── _margin.scss
    │   ├── _padding.scss
    │   ├── _size.scss
    │   ├── _visibility.scss
└── demo/
        ├── index.html
└── elements/
        └── complex/
            ├── _scrollbar.scss
        ├── README.md
        ├── _buttons.scss
        ├── _checkradio.scss
        ├── _heading.scss
        ├── _img.scss
        ├── _inputs.scss
        ├── _link.scss
        ├── _list.scss
        ├── _textpart.scss
└── layouts/
        ├── README.md
        ├── _base.scss
└── pages/
        ├── README.md
└── utils/
        ├── README.md
        ├── _font.scss
        ├── _func.scss
        ├── _media.scss
        ├── _mixin.scss
        ├── _print.scss
        ├── _var.scss
        ├── _z-index.scss
└── vendor/
        ├── README.md
        ├── _animate.scss
        ├── _normalize.scss
    ├── README.md
    ├── index.css
    ├── index.scss
```
## Bugs and feature requests
Found an error? First, read the instructions for solving your problem.
## Documentation
Documentation, included in this repo in the root directory, publicly hosted on GitHub Pages at <https://webart.work/>. The docs may also be run locally.
Documentation search is powered by [Algolia's DocSearch](https://community.algolia.com/docsearch/). Working on our search? Be sure to set `debug: true` in `site/assets/js/src/search.js` file.
### Running documentation locally
1. Run `npm install` to install the Node.js dependencies, including Hugo (the site builder).
2. Run `npm run test` (or a specific npm script) to rebuild distributed CSS and JavaScript files, as well as our docs assets.
3. From the root `/bootstrap` directory, run `npm run docs-serve` in the command line.
4. Open `http://localhost:9001/` in your browser, and voilà.
Learn more about using Hugo by reading its [documentation](https://gohugo.io/documentation/).
### Documentation for previous releases
You can find all our previous releases docs on <https://github.com/WebArtWork>.
[Previous releases](https://github.com/twbs/bootstrap/releases) and their documentation are also available for download.
## Contributing
Please read the operating principles, coding and development standards immediately.
Moreover, if your pull request contains JavaScript patches or features, you must include [relevant unit tests](https://github.com/twbs/bootstrap/tree/master/js/tests). All HTML and CSS should conform to the [Code Guide](https://github.com/mdo/code-guide).
Editor preferences are available in the [editor config](https://github.com/WebArtWork/wawCss) for easy use in common text editors. Read more and download plugins at <https://editorconfig.org/>.
## Community
- Join [the official Slack room](/https://crackeraki.slack.com/).
## Versioning
For transparency into our release cycle and in striving to maintain backward compatibility under [the Semantic Versioning guidelines](https://semver.org/).
See [the Releases section of our GitHub project](https://github.com/WebArtWork/wawCss) for changelogs for each release version of Bootstrap. Release announcement posts on [the official Bootstrap blog](https://blog.getbootstrap.com/) contain summaries of the most noteworthy changes made in each release.
## Backers
Thank you to all our backers! :pray: [[Become a backer](https://opencollective.com/bootstrap#backer)]
[![Backers](https://opencollective.com/bootstrap/backers.svg?width=890)](https://opencollective.com/bootstrap#backers)
## Copyright and license
Code released under the [MIT License](https://github.com/WebArtWork).