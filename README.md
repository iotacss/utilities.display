# Display Utility #

The display utility contains helper classes for the CSS display property.


### Installation ###

```
npm install --save iotacss-display
```


### Dependencies ###

* [Settings.Default](https://github.com/iotacss/settings.default)
* [Settings.Breakpoint](https://github.com/iotacss/settings.breakpoint)


### Options ###

```
$iota-display--res                      : false !default;
$iota-display-block-namespace           : 'block' !default;
$iota-display-hidden-namespace          : 'hidden' !default;
$iota-display-hidden-visually-namespace : 'hidden-visually' !default;
$iota-display-inline-namespace          : 'inline' !default;
$iota-display-inline-block-namespace    : 'inline-block' !default;
```


### Classes ###

```
.u-block
.u-hidden
.u-hidden-visually
.u-inline
.u-inline-block


// Responsive Class Syntax

.u-[name]@[breakpoint-name]  // Example: .u-block@sm
```
