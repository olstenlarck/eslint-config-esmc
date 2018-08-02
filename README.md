# eslint-config-esmc [![npm version][npmv-img]][npmv-url] [![github release][ghrelease-img]][ghrelease-url] [![License][license-img]][license-url]

<!-- When logo is needed
<p align="center">
  <a href="https://github.com/username/repo">
    <img src="./logo.png">
  </a>
</p>
<br>
-->

> Shareable and the default config for the `esmc` compiler

<div id="thetop"></div>

[![XAXA code style][codestyle-img]][codestyle-url]
[![CircleCI linux build][linuxbuild-img]][linuxbuild-url]
[![CodeCov coverage status][codecoverage-img]][codecoverage-url]
[![DavidDM dependency status][dependencies-img]][dependencies-url]
[![Renovate App Status][renovateapp-img]][renovateapp-url]
[![Make A Pull Request][prs-welcome-img]][prs-welcome-url]
[![Semantically Released][new-release-img]][new-release-url]

If you have any _how-to_ kind of questions, please read the [Contributing Guide](./CONTRIBUTING.md) and [Code of Conduct](./CODE_OF_CONDUCT.md) documents.  
For bugs reports and feature requests, [please create an issue][open-issue-url] or ping [@tunnckoCore](https://twitter.com/tunnckoCore) at Twitter.

[![Conventional Commits][ccommits-img]][ccommits-url]
[![Become a Patron][patreon-img]][patreon-url]
[![Share Love Tweet][shareb]][shareu]
[![NPM Downloads Weekly][downloads-weekly-img]][npmv-url]
[![NPM Downloads Monthly][downloads-monthly-img]][npmv-url]
[![NPM Downloads Total][downloads-total-img]][npmv-url]

Project is [semantically](https://semver.org) & automatically released on [CircleCI][codecoverage-url] with [new-release][] and its [New Release](https://github.com/apps/new-release) GitHub App.

## Table of Contents
- [Install](#install)
- [Usage](#usage)
- [Related Projects](#related-projects)
- [Contributing](#contributing)
- [Contributors](#contributors)
- [Users](#users)
- [License](#license)

## Install
This project requires [**Node.js**](https://nodejs.org) **>=6.9.0**. Install it using [**yarn**](https://yarnpkg.com) or [**npm**](https://npmjs.com).  
_We highly recommend to use Yarn when you think to contribute to this project._

```bash
$ yarn add --dev eslint-config-esmc
```

## Usage

Add it in your ESLint config as follows

```json
{
  "extends": ["esmc"]
}
```

**[back to top](#thetop)**

## Related Projects
Some of these projects are used here or were inspiration for this one, others are just related. So, thanks for your existance!
- [asia](https://www.npmjs.com/package/asia): Blazingly fast, magical and minimalist testing framework, for Today and Tomorrow | [homepage](https://github.com/olstenlarck/asia#readme "Blazingly fast, magical and minimalist testing framework, for Today and Tomorrow")
- [charlike](https://www.npmjs.com/package/charlike): Small, fast, simple and streaming project scaffolder for myself, but not… [more](https://github.com/tunnckoCore/charlike) | [homepage](https://github.com/tunnckoCore/charlike "Small, fast, simple and streaming project scaffolder for myself, but not only. Supports hundreds of template engines through the @JSTransformers API or if you want custom `render` function passed through options")
- [gitcommit](https://www.npmjs.com/package/gitcommit): Lightweight and joyful `git commit` replacement. Conventional Commits compliant. | [homepage](https://github.com/tunnckoCore/gitcommit "Lightweight and joyful `git commit` replacement. Conventional Commits compliant.")
- [new-release](https://www.npmjs.com/package/new-release): A stable alternative to [semantic-release][]. Only handles NPM publishing and nothing… [more](https://github.com/tunnckoCore/new-release#readme) | [homepage](https://github.com/tunnckoCore/new-release#readme "A stable alternative to [semantic-release][]. Only handles NPM publishing and nothing more. For creating GitHub releases use the Semantic Release GitHub App")
- [xaxa](https://www.npmjs.com/package/xaxa): Zero-config linting, powered by few amazing unicorns, AirBnB & Prettier. | [homepage](https://github.com/olstenlarck/xaxa "Zero-config linting, powered by few amazing unicorns, AirBnB & Prettier.")

**[back to top](#thetop)**

## Contributing
Please read the [Contributing Guide](./CONTRIBUTING.md) and [Code of Conduct](./CODE_OF_CONDUCT.md) documents for advices.  
For bugs reports and feature requests, [please create an issue][open-issue-url] or ping [@tunnckoCore](https://twitter.com/tunnckoCore) at Twitter.

## Contributors
Thanks to the hard work of [these wonderful people](./CONTRIBUTORS.md) this project is alive and it also follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification.  
[Pull requests](https://github.com/tunnckoCore/contributing#opening-a-pull-request), stars and all kind of [contributions](https://opensource.guide/how-to-contribute/#what-it-means-to-contribute) are always welcome. :stars:

## Users
You can see who uses `eslint-config-esmc` in the [USERS.md](./USERS.md) file. Please feel free adding this file if it not exists.  
If you or your organization are using this project, consider adding yourself to the list of users.  
**Thank You!** :heart:

## License
Copyright (c) 2018-present, [Charlike Mike Reagent][author-link] `<olsten.larck@gmail.com>`.  
Released under the [Apache-2.0 License][license-url].

---

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.7.0, on August 02, 2018._

<!-- Heading badges -->
[npmv-url]: https://www.npmjs.com/package/eslint-config-esmc
[npmv-img]: https://badgen.net/npm/v/eslint-config-esmc?icon=npm

[ghrelease-url]: https://github.com/olstenlarck/eslint-config-esmc/releases/latest
[ghrelease-img]: https://badgen.net/github/release/olstenlarck/eslint-config-esmc?icon=github

[license-url]: https://github.com/olstenlarck/eslint-config-esmc/blob/master/LICENSE
[license-img]: https://badgen.net/npm/license/eslint-config-esmc

<!-- Front line badges -->

[codestyle-url]: https://github.com/olstenlarck/eslint-config-esmc
[codestyle-img]: https://badgen.net/badge/code%20style/esmc/purple

[linuxbuild-url]: https://circleci.com/gh/olstenlarck/eslint-config-esmc/tree/master
[linuxbuild-img]: https://badgen.net/circleci/github/olstenlarck/eslint-config-esmc/master?label=build&icon=circleci

[codecoverage-url]: https://codecov.io/gh/olstenlarck/eslint-config-esmc
[codecoverage-img]: https://badgen.net/codecov/c/gh/olstenlarck/eslint-config-esmc

[dependencies-url]: https://david-dm.org/olstenlarck/eslint-config-esmc
[dependencies-img]: https://badgen.net/david/dep/olstenlarck/eslint-config-esmc

[ccommits-url]: https://conventionalcommits.org/
[ccommits-img]: https://badgen.net/badge/conventional%20commits/v1.0.0/dfb317

[new-release-url]: https://github.com/tunnckoCore/new-release
[new-release-img]: https://badgen.net/badge/semantically/released/05c5ff

[downloads-weekly-img]: https://badgen.net/npm/dw/eslint-config-esmc
[downloads-monthly-img]: https://badgen.net/npm/dm/eslint-config-esmc
[downloads-total-img]: https://badgen.net/npm/dt/eslint-config-esmc

[renovateapp-url]: https://renovatebot.com
[renovateapp-img]: https://badgen.net/badge/renovate/enabled/green

[prs-welcome-img]: https://badgen.net/badge/PRs/welcome/green
[prs-welcome-url]: http://makeapullrequest.com

[paypal-donate-url]: https://paypal.me/tunnckoCore/10
[paypal-donate-img]: https://badgen.net/badge/$/support/purple

[patreon-url]: https://www.patreon.com/bePatron?u=5579781
[patreon-img]: https://badgen.net/badge/become/a%20patron/F96854?icon=patreon

[shareu]: https://twitter.com/intent/tweet?text=https://github.com/olstenlarck/eslint-config-esmc&via=tunnckoCore
[shareb]: https://badgen.net/badge/twitter/share/1da1f2
[open-issue-url]: https://github.com/olstenlarck/eslint-config-esmc/issues/new
[author-link]: https://tunnckocore.com

[new-release]: https://github.com/tunnckoCore/new-release
[semantic-release]: https://github.com/semantic-release/semantic-release