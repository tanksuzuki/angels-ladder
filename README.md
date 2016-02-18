# Angel's Ladder

## Overview

Angel's Ladder is a simple blog theme for Hugo.

* Simple and clean design
* Responsive design
* Pagination
* Tagging
* Disqus
* Source code highlighting
* Google Analytics

## Screenshot

All of the display [here](https://github.com/tanksuzuki/angels-ladder/tree/master/images/tn_full.png).

![](https://raw.githubusercontent.com/tanksuzuki/angels-ladder/master/images/readme.png?token=ALXg6utVKJxUhSjlO_-voAEgA75oYTseks5VXtd1wA%3D%3D)  


## Installation

Clone this repository to your hugo theme directory.

```
cd themes
git clone https://github.com/tanksuzuki/angels-ladder
hugo server -t angels-ladder -D -w
```


## Configuration

To take full advantage of the features in this theme, you can add variables to your site config file.

The following is the example configuration.

```
baseurl = "http://tanksuzuki.com/"
languageCode = "ja"
title = "TANKSUZUKI.COM"
disqusShortname = "tanksuzuki"

[Params]
subtitle = "I would like to be a layer 3 switch."
facebook = "https://facebook.com/foobar"
twitter = "https://twitter.com/foobar"
github = "https://github.com/foobar"
showsRSS = true
profile = "/images/profile.png"
copyright = "Written by Asuka Suzuki"
analytics = "UA-XXXXXXXX-X"
shareThis = "XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX"
```

Details of each parameter are as follows.

| Parameter | Required | Comment |
| :--- | :--- | :--- |
| baseurl | yes | Enter the title of your site. |
| languageCode | yes | Enter the language code of HTML. Example: en, ja. |
| title | yes | Enter the title of your site. |
| disqusShortname | no | Enter the short name of the disqus. If you do not enter, disqus section is hidden. |
| subtitle | no | Enter the subtitle of your site. If you do not enter, subtitle is hidden. |
| facebook | no | Enter the URL of Facebook. If you do not enter, the link is hidden. |
| twitter | no | Enter the URL of Twitter. If you do not enter, the link is hidden. |
| github | no | Enter the URL of Github. If you do not enter, the link is hidden. |
| showsRSS | no | Enter true to show the URL of RSS. If you enter false or nothing, the link is hidden. |
| profile | no | Enter the path to the profile image. If you do not enter, profile section will be hidden. |
| copyright | no | Enter the copyright notice. If you do not enter, copyright display is hidden. |
| analytics | no | Enter the tracking ID of Google analytics. If you do not enter, the analysis will be skipped. |
| shareThis | no | Enter the publisher key of ShareThis. If you do not enter, the ShareThis buttons are hidden. |


## Style Customization

To change the theme color, edit the `layouts/static/theme.less`.
Then compile the LESS file by using [one of LESS compilers](http://leafo.net/lessphp/editor.html),
and replace the content of `layouts/static/theme.css` with the compiled CSS.

The default theme color is `#29abe2`.
Please change the favorite color.

```
/* Theme color
--------------------------------------------------*/
@color: #29abe2;
```

For original styles, please edit the `layouts/static/custom.css`.


## License

Open sourced under the [MIT license](https://github.com/tanksuzuki/angels-ladder/blob/master/LICENSE.md).


## Author

Asuka Suzuki


## Contact

Please contact me via [email](https://github.com/tanksuzuki) / [Twitter](https://twitter.com/tanksuzuki) :smile:
