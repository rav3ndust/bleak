# captivate

**Captivate** is a beautiful and responsive theme for the [Ghost](https://github.com/tryghost/ghost/) publishing platform. 

This repo is a fork of the gorgeous [bleak theme](https://github.com/zutrinken/bleak) that aims to strip out the social elements and build upon the already beautiful theme. I plan to add other functionalities over time, along with possible iterations to the design. 

## Screenshots

<table>
<tr>
<td valign="top">
<img src="https://raw.githubusercontent.com/zutrinken/bleak/master/src/screenshot-desktop.jpg" />
</td>
<td valign="top">
<img src="https://raw.githubusercontent.com/zutrinken/bleak/master/src/screenshot-mobile.jpg" />
</td>
</tr>
</table>

## ⭐️ Captivate's features: 

* Responsive layout
* Automatic code syntax highlight and line numbers
* Simple to edit from within your Ghost dashboard

## 🎨 In order to set up your own custom colors:

### You can do this from within your Ghost dashboard. 

1. Go to __Code injection__.  
2. Add this to __Blog Header__:  
````
<style>
  :root {
    --color-primary: #D95736;
    --color-primary-active: #BF4526;
  }
</style>
````

## Give your site a Sticky Header

Want to make your header nav stick to the top You can make the navigation stick to the top by adding the following lines via code injection:

```
<style>
  #wrapper {
    padding-top: 4em;
  }
  #nav {
    position: fixed;
  }
</style>
```

## Development

Install [Grunt](http://gruntjs.com/getting-started/):

	npm install -g grunt-cli

Install Grunt modules:

	npm install

Install [Bower](https://bower.io):

	npm install -g bower

Install Bower components:

	bower install

Build Grunt project:

	grunt

Distribute Grunt project:

	grunt build

## Copyright & License

Copyright (C) 2015-2021 Peter Amende - Released under the [MIT License](https://github.com/zutrinken/bleak/blob/master/LICENSE).
