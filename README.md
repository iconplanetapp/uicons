# <img src="https://iconplanet.app/images/logo.svg" height="28" style="vertical-align:middle"> IconPlanet &nbsp;<img src="https://iconplanet.app/images/uicons-logo.svg" height="28" style="vertical-align:middle">

Install the latest version of Uicons – which includes each individual icon in SVG format, CSS stylesheets and font files – and easily keep your project up to date with the latest icons and enhancements through the npm package manager.

<br>

# Get Started

## Installation
<hr>

Install latest version of IconPlanet uicons package with ```npm``` package manager:

``` js
npm i @iconplanet/uicons
```

In short, with this method you get the same result as with the downloadable format but in an easier-to-update package.

This package contains the following directories and files:

| Path     | What it is                   |
|----------|------------------------------|
| /css     | Stylesheets for Web Fonts    |
| /svg     | Individual SVG for each icon |
| /webfont | Web Font files used with CSS |

<br>

## CSS @import
<hr>

<br>

### 1. Import all packages
You can import all available packages with importing this file:

``` css
@import '~@iconplanet/uicons/css/ip-all';
```

<br>

### 2. Single style 
Or just import certain packages individually:

``` css
@import '~@iconplanet/uicons/css/ip-[PACKAGE-NAME]';

@import '~@iconplanet/uicons/css/ip-brands';
```

|  **Package Name** | **Prefix** |              **Example**               |
|-------------------|------------|----------------------------------------|
| brands            | ip-brands  | &lt;i class="ip-brands-instagram"></i> |
| awesome-regular   | ip-ar      | &lt;i class="ip-ar-user"></i>          |
| flat-bold-rounded | ip-fbr     | &lt;i class="ip-fbr-home"></i>         |

## Use icons
<hr>

``` html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Iconic Project</title>
    <!-- you should import IconPlanet Uicons css files inside this file -->
    <link rel="stylesheet" href="[/path-to-your-project/css-file.css]"/>
  </head>
  <body>
    <i class="ip-brands-instagram"></i>
    <i class="ip-ar-book"></i>
    <i class="ip-frr-user"></i>
    <i class="ip-fbr-arrow-right"></i>
  </body>
</html>
```