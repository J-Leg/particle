# Particulate Jekyll Theme
A minified fork of [nrandecker/particle](https://github.com/nrandecker/particle).

## Basic Setup

1. [Install Jekyll](http://jekyllrb.com)
2. Clone the particle theme: `git clone git@github.com:J-Leg/particulate.git`
3. Edit `_config.yml` to personalize your site.
  - Minor todo: `json` data is still directly used in `header.html`.

## Site and User Settings

You have to fill some informations on `_config.yml` to customize your site.

**Don't forget to change your url before you deploy your site!**

## Color and Particle Customization
- Color Customization
  - Edit the sass variables
- Particle Customization
  - Edit the json data in particle function in app.js
  - Refer to [Particle.js](https://github.com/VincentGarreau/particles.js/) for help

In order to compile the assets and run Jekyll on local you need to follow those steps:

- Install [NodeJS](https://nodejs.org/)
- Install [Jekyll](https://jekyllrb.com): `sudo gem install bundler jekyll`
- Install [Yarn](https://yarnpkg.com/): `npm install -g yarn`
- Install [Gulp](https://gulpjs.com/): `npm install --global gulp-cli`
- Install dependencies: `yarn`
- Run: `gulp`

## Questions

Having any issues file a [GitHub Issue](https://github.com/nrandecker/particle/issues/new).

## License

This theme is free and open source software, distributed under the The MIT License. So feel free to use this Jekyll theme anyway you want.

## Credits

This theme is a fork of particles (by [Nathan Randecker](https://github.com/nrandecker/particle)).

Other design contributions from:
- [Willian Justen](https://github.com/willianjusten/will-jekyll-template)
- [Vincent Garreau](https://github.com/VincentGarreau/particles.js/)
