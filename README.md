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
  @extend badge-solid;
  --badge-color: blue;

  /* or roll your own */

  /* add something custom in here */
}
```

## Patterns
Placeholder selectors that contain common styles for structure and basic behavior.

#### `@extend %badge-inline;`
Renders an inline element with standard padding and margin.

##### Options

```css
--badge-display: inline-block;
--badge-font-size: 12px;
--badge-padding: 3px 8px;
--badge-position: relative;
--badge-line-height: 1;
--badge-margin: 0 1% 1% 0;
--badge-max-width: 100%;
--badge-min-width: 22px;
--badge-outline: 0;
--badge-text-align: center;
--badge-text-decoration: none;
--badge-vertical-align: middle;
--badge-white-space: nowrap;
```

## Styles
Customizable presets that give your pattern a specific style-set.

### `@extend %badge-solid;`
Draws a solid background ontop of a badge with white text for contrast.

##### Options

```css
--badge-color: #333; // background
--badge-border: none;
--badge-radius: 50px;
--badge-shadow: none;
--badge-text-color: #fff;
```

### `@extend %badge-hollow;`
Draws a bordered element with dark text for contrast.

##### Options

```css
--badge-color: #333; // background and text color
--badge-background: transparent;
--badge-border-size: 1px;
--badge-radius-size: 50px;
--badge-shadow: none;
```

