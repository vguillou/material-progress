# material-progress

[![GitHub version](https://badge.fury.io/gh/vguillou%2Fmaterial-progress.svg)](https://badge.fury.io/gh/vguillou%2Fmaterial-progress)

_A Material design multi-progress bar collection, inspired by Google Fit and made with Polymer._

<img src="https://github.com/vguillou/material-progress/blob/master/res/material-progress-bars.png" alt="material-progress-bars screenshot" width="436">
<img src="https://github.com/vguillou/material-progress/blob/master/res/material-progress-histo.png" alt="material-progress-histo screenshot" width="436">

## Use it in your project :

Element dependencies are managed via [Bower](http://bower.io/). To install this element,
use this command

    bower install --save material-progress


## Documentation and demo

Please refer to the <a href="https://vguillou.github.io/webcomponents/material-progress">component page</a> for more informations.

Demos available <a href="https://vguillou.github.io/webcomponents/material-progress/demo">here</a>.


## License

[MIT License](https://github.com/vguillou/material-progress/blob/master/LICENSE.md)


## Changelog

The update to v1.0.0 will bring a gazillion breaking changes.
- Complete rewrite, with SVG based progress bars
- Much better performance
- Breaking: `material-progress-bars` renamed to `material-progress-stacked-bars`
- Breaking: `material-progress-histo` renamed to `material-progress-bars`
- Breaking: Using a new `data` property instead of defining the bars yourself programmatically
- Breaking: Properties renaming :
    - `barHeight` => `barThickness`
    - Custom style properties renaming to match the new element names
- Breaking: The legend has it's own configurable component: `material-progress-legend`
- Brand new `material-progress-circle` to complete the set
