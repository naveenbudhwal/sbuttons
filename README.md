# sButtons
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](./LICENSE.md)
 [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](./CONTRIBUTING.md) [![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](./CONTRIBUTING.md) <!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-73-orange.svg?style=flat-square)](./CONTRIBUTORS.md)
<!-- ALL-CONTRIBUTORS-BADGE:END --> 
  
:bulb: Simple buttons you can use easily for your next project.

# Particpate in Hacktoberfest!

This repository will help people who don't know how to participate in [Hacktoberfest](https://hacktoberfest.digitalocean.com/) or where to start contributing. We will be adding a Hacktoberfest label to help contributors find the issues they can contribute to. If you have any ideas for new issues or ways to help contributors participate in Hacktoberfest, please add them [here](https://github.com/shahednasser/sbuttons/issues/161).

# Usage
You can download the CSS file [here](https://cdn.statically.io/gh/shahednasser/sbuttons/c135f5f7/dist/sbuttons.min.css) and then add it to your html file inbetween the `<head>` tags:

```
<link rel="stylesheet" href="/path/to/sbuttons.min.css">
```

Or instead of downloading the file, you can use the [CDN](https://cdn.statically.io/gh/shahednasser/sbuttons/c135f5f7/dist/sbuttons.min.css):

```
<link rel="stylesheet" href="https://cdn.statically.io/gh/shahednasser/sbuttons/c135f5f7/dist/sbuttons.min.css">
```

In case of using buttons that have icons in them, make sure to include font awesome's [CDN](https://use.fontawesome.com/releases/v5.14.0/css/all.css) in the `<head>` tag:

```
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.14.0/css/all.css" integrity="sha384-HzLeBuhoNPvSl5KYnjx0BT+WB0QEEqLprO+NBkkk5gbc67FTaL7XIGa2w1L0Xbgc" crossorigin="anonymous">
```
To use sButtons in your project , just add the classes of sButton you want to either  `<button>` or `<a>` tags :

```
<button class='sbtn basic-btn blue-btn'>Button</button>
```
This code will produce basic sButton with blue colour. Same can be done for `<a>` tag

```
<a href='#' class='sbtn basic-btn blue-btn'>Button</a>
```

To use sButtons with block display, add the class to either `<button>` or `<a>` tags
 
```
<button class="sbtn basic-btn block-btn">Button</button>
```

To make a `<button>` or `<a>` tag disabled, add disabled-btn class as shown below.

```
<button class="sbtn basic-btn blue-btn disabled-btn">Button</button>
```
```
<a class="sbtn basic-btn blue-btn disabled-btn">Button</a>
```

You can find all classes and their corresponding sButtons mentioned in our [website](https://shahednasser.github.io/sbuttons/). 

# Installation

1. Clone the repository
   ```
   git clone https://github.com/shahednasser/sbuttons.git
   ```
2. Run NPM install
   ```
   npm install
   ```

# Contribution

Please see the [contributing guidelines](./CONTRIBUTING.md) for details.

### Button ideas

If you have ideas for buttons, or would like to see a list of ideas that have not been implemented to work on, you can add them [here](./BUTTON_IDEAS.md).

# Contributors

Check out our awesome contributors [here](./CONTRIBUTORS.md)!

# LICENSE

[MIT](./LICENSE)
