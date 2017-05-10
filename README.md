# Rocket Chat Inverted
A dark theme for Rocket Chat

## Preview
![](./screenshot_main.png)

## Installing

  1. Get the Stylish addon for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/2108/), [Chrome](https://chrome.google.com/extensions/detail/fjnbnpbmkenffdnngjfgmeleoegfcffe), [Opera](https://addons.opera.com/en/extensions/details/stylish/), [Safari](http://sobolev.us/stylish/) and [Firefox Mobile](https://addons.mozilla.org/en-US/firefox/addon/2108/).
  2. Then install this style using:
    * [userstyles.org](https://userstyles.org/styles/136988)
    * or, add it [manually](https://raw.githubusercontent.com/jakebathman/Rocket-Chat-Inverted/master/RocketChatInverted.css) into the editor.

## Notes

* Make sure to set your Rocket Chat domain though a `@-moz-document` rule (Firefox) or add it to the `Applies to` section in (Chrome).

## Release Notes

#### v1.2.0

* Latest supported Rocket Chat version is now v0.55.1, and this value will be reflected in the CSS header for future releases
* More Unreads on lower sidebar now fixed to bottom of the screen [fixes #7]
* Message dropdown background is no longer transparent [fixes #8]
* Fixed new primary-background-color class to use the default dark grey (instead of blue) [fixes #5]
* Fix issue with highlight words that changed color because of a new selector
* Change to Unread Messages banner based on new :before and :after styles. It's not possible to override these pseudo selectors using this user style without a weird flicker/movement, so now it's a solid dark blue bar. Will continue investigating a way to bring back the old thin blue unreads line
* Fix calculation of sidebar height and overflow, caused by new universal search box [fixes #4]
* Fix background color of inline code blocks [fixes #6]
* Add styling override for pages not meant to be styled (like /api/info) where the JSON returned was black on black. May cause a white flicker when first loading the Rocket application; will investigate a way to eliminate that on empty `<body>`` elements
* Change color of quoted text left border to better match the theme

## Contribute

Contributions are welcome! If you would like to contribute to this repository, please...

1. Fork
2. Make changes 
3. Create a pull request
