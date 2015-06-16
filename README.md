# Impromptu React Side Menu

A (sliding) side menu component for React. 

### What does it look like?

## Installation

Npm is the recommended install method.

```
npm install impromptu-react-sidemenu
```

## How to use

### HTML

## Props

| Property        | Type                     | Description   | Default      | 
| --------------- | ------------------------ | ------------- | ------------ |
| `width`         | Integer                  | Width of the menu, in pixels.  | 250         |
| `autoClose`     | Boolean                  | Controls whether the menu should automatically close when a menu item is clicked.      | false      |
| `position`      | 'left'&nbsp;&vert;&nbsp;'right'         | Position of the menu.     | 'right'            |
| `showDividers`  | Boolean                  | When true, this setting enables a visible line between menu items.     | false    |

## CSS

### Customization

```
/* Open button color values */
$button-open-bg           : rgba(0, 0, 0, 0.4);
$button-open-bg-active    : rgba(0, 0, 0, 0.7);
$button-open-fg           : rgb(255, 255, 255);

/* Close button color values */
$button-close-bg          : rgb(255, 255, 255);
$button-close-bg-active   : rgba(255, 255, 255, 0.7);
$button-close-fg          : rgb(51, 51, 51);

/* Menu color values */
$menu-background          : rgb(51, 51, 51);
$menu-text-base           : rgb(153, 153, 153);
$menu-text-active         : rgb(255, 255, 255);
$menu-selected-bg         : rgba(255, 255, 255, 0.2);
$menu-divider             : rgb(74, 74, 74);
```

## Contribute

Please, do. Like the ancient Greek proverb says; "Pull requests are welcome."

## License

Code licensed under the BSD License.

#### Font Awesome

This project is distributed with Font Awesome. [Font Awesome](http://fontawesome.io/) is created and maintained by Dave Gandy. Fonts licensed under SIL OFL 1.1. Code licensed under the MIT License.
