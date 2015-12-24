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

  /* Button Design Pattern */
  @extend %badge-inline;

  /* Customize your button */
  @mixin badge-solid green, white, 5px;

  /* or roll your own */

  /* add something custom in here */
}
```

## Patterns
Placeholder selectors that contain common styles for structure and basic behavior.

#### `@extend %badge-inline;`
Renders an inline element with standard padding and margin.

## Styles
Customizable presets that give your pattern a specific style-set.

### badge-solid
Draws a solid background ontop of a badge with white text for contrast.

##### Options

* `$color-passive: #333` Controls the color of the badge background
* `$color-text: #fff` Controls the color of the badge text
* `$radius-size: 50px` Controls how much the badge is rounded off on it’s corners
* `$border: none` Optional argument lets you specify a border style around your badge
* `$shadow: none` Optional argument that lets you specify a shadow around your badge

##### Example
```css
/* A solid green badge with white text, 5 pixels border-radius, with an orange border and a small dark shadow. */
@mixin badge-solid green, white, 5px, 1px solid orange, 0 1px 5px rgba(0, 0, 0, .5);
```

### badge-hollow
Draws a bordered element with dark text for contrast.

##### Options

* `$color-passive: #333` Controls the color of the badge border
* `$color-text: #333` Controls the color of the badge text
* `$color-background: transparent` Optional argument for changing the background color
* `$radius-size: 50px` Controls how much the badge is rounded off on it’s corners
* `$border-width: 1px` Controls the thickness of the badge border
* `$shadow: none` Optional argument that lets you specify a shadow around your badge

##### Example
```css
/* A bordered badge with dark text, no background, rounded corners, 1px border and no shadow. */
@mixin badge-hollow #333, #333, transparent, 50px, 1px, none;
```

