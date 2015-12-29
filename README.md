# stylep-badge
<img src=https://avatars1.githubusercontent.com/u/16121328?v=3&s=200 title=stylep-badge align=right height=95>

Tools to build simple badges in your next project.

## Install
You can install using the [spm](https://github.com/stylep/stylep) command or install using npm and the project title.

``` shell
spm install badge
```

## Usage
``` css
/* badge.css */

@import “stylep-badge”;

.badge {

  /* Badge Design Pattern */
  @mixin badge-inline;

  /* Customize your badge */
  @mixin badge-solid blue;

  /* or roll your own */

  /* add something custom in here */
}
```

## Patterns
Placeholder selectors that contain common styles for structure and basic behavior.

#### `badge-inline`
Renders an inline element with standard padding and margin.

##### Options

* `$badge-font-size: 12px` How large the text is inside the badge
* `$badge-padding: 3px 8px` Space inside the badge
* `$badge-margin: 0 1% 1% 0` Space around the badge

## Styles
Customizable presets that give your pattern a specific style-set.

### `badge-solid`
Draws a solid background ontop of a badge with white text for contrast.

##### Options

* `$badge-color: #555` Color of the badge
* `$badge-text-color: #fff` Color of the text inside the badge
* `$badge-radius: 50px` Roundness of the badge

### `badge-hollow`
Draws a bordered element with dark text for contrast.

##### Options

* `$badge-color: #555` Color of the outline and text of the badge
* `$badge-radius: 50px` Roundness of the badge
* `$badge-border-style: solid` Style of the border around the badge
* `$badge-border-width: 1px` Thickness of the border around the badge

## License
This project is licensed under the MIT [license](LICENSE).

