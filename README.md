# 'zen' theme for Jekyll Bootstrap

A really simple theme as seen on [my blog](http://zen.id.au/)

## Notes

### Gravatar & caption
Requires an extra property in your `_config.yaml` file
```yml
author :
  gravatar :
    url : https://en.gravatar.com/userimage/13363990/4bd44ba6339e4525ad9f839f46244100.jpg
    caption : Looking snazzy...
```

If you don't want to use a Gravatar for the avatar image, just go to `_includes/themes/zen/default.html` and set your own image url there.

### Bio
The bio text which sits underneath the image is just hardcoded html in the `_includes/themes/zen/default.html` file - handle this as you wish (I couldn't be bothered implementing a cleaner solution for this, but including another file with a bio is not a difficult task if you wish to do so)

### Homepage layout
Included is a `index.html` file which displays a basic list of posts and dates, feel free to modify this.

## Installation

Just run
`rake theme:install git="https://github.com/Zensavona/theme-zen.git"`

And you're done.


Enjoy!