# Nova Fixed Bars
![styleci](https://github.styleci.io/repos/179893173/shield?branch=master&style=flat-square)
![downloads](https://img.shields.io/packagist/dt/stephenlake/nova-fixed-bars.svg?style=flat-square)
![release](https://img.shields.io/github/release/stephenlake/nova-fixed-bars.svg?style=flat-square)
![license](https://img.shields.io/badge/license-DBADPL-blue.svg?style=flat-square)

A Laravel Nova package to set the sidebar and/or header bar to a fixed position on the Nova UI.

<h6 align="center">
  <img src="https://i.imgur.com/VlfiVB0.gif" width="650">
  <br>
  Want this theme? Check out <a href="https://github.com/stephenlake/nova-snowball">Nova Snowball</a>.
</h6>

Made with ❤️ by [Stephen Lake](http://github.com/stephenlake)

# Installation

**Note:** If you do not want the responsive sidebar and header, stick to `v1.0.*`.

Require package:
```bash
composer require stephenlake/nova-fixed-bars
```

Publish and edit configuration file (**Optional**)
```bash
php artisan vendor:publish --provider="NovaFixedBars\NovaFixedBarsServiceProvider" --tag="config"
```

# License
This library is licensed under the DON'T BE A DICK PUBLIC LICENSE - see the [LICENSE.md](LICENSE.md) file for details.
