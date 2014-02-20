*This repository is a mirror of the [component](http://component.io) module [yyolk/random-palette-color](http://github.com/yyolk/random-palette-color). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yyolk-random-palette-color`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# random-palette-color

  Return a random [palette](https://github.com/enricomarino/palette) color

## Installation

    $ component install yyolk/random-palette-color

## Usage
```js
var RandomPaletteColor = require("random-palette-color");
function changeBodyColor(){
  document.getElementById("body").style.backgroundColor = RandomPaletteColor();
}
changeBodyColor();
```

## License

  MIT
