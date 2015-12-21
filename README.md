# stylep-template

Everything you need to get started making a new style pattern.

## Install
You can install using the [spm](https://github.com/stylep/stylep) command or install using npm and the project name.

``` shell
spm install template
```

## Usage
``` css
/* name.css */

@import “stylep-name”;

.class {

  /* Button Design Pattern */
  @extend %name;

  /* Customize your button */
  @mixin name param, param;

  /* or roll your own */

  /* add something custom in here */
}
```

## Patterns
Placeholder selectors that contain common styles for structure and basic behavior.

#### `@extend %name-of-pattern;`
Describe what this pattern does.

## Styles
Customizable presets that give your pattern a specific style-set.

### name-of-style
Describe the visual look and feel of this style.

##### Options

* `$param-name: default-value` Describe what this does

##### Example
```css
/* describe in english what this following statement really means in detail */
@mixin name-of-style default-value;
```

