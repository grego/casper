# casper

![casper screenshot](screenshot.png)

## [Live demo](https://blades-casper.netlify.app/)

casper is a port of the eponymous theme for [Blades](https://github.com/grego/blades),
loosely based on the old version of [Casper theme](https://github.com/TryGhost/Casper) for Ghost.io


## Installation
Clone it into your themes directory:
```bash
$ cd themes
$ git clone https://github.com/grego/casper
```

Or use it as a submodule:
```bash
$ cd themes
$ git submodule add https://github.com/grego/casper 
```

Then, set it as a theme in your `Blades.toml`:
```toml
theme = "casper"
```

## Colors
You can change the main color of this theme by modifying the corresponding variable
at the beginning of `assets/style.css`. 
Then, run `blades colocate`.

## Images
If you want to use the picture gallery provided by this theme, place your thumbnails in the
`img/thumb` and your full images to the `img/full` subdirectories of your output directory
(which defaults to `public`, unless set otherwise in the config).

## License
[MIT](LICENSE)
