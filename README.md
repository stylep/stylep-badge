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
  @mixin badge-solid param, param;

  /* or roll your own */

  /* add something custom in here */
}
```

## Patterns
Placeholder selectors that contain common styles for structure and basic behavior.

#### `@extend %badge-inline;`
Describe what this pattern does.

## Styles
Customizable presets that give your pattern a specific style-set.

### badge-solid
Describe the visual look and feel of this style.

##### Options

* `$param: default-value` Describe what this does

##### Example
```css
/* describe in english what this following statement really means in detail */
@mixin badge-solid default-value;
```

