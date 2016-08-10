## Classy Material Icons

[Classy Material Icons](https://github.com/bpmarkowitz/classy-material-icons) is simply a CSS file you can add to your project along with the [Google Material Icons](https://design.google.com/icons/) web font that allows you to use classes instead of content to set an icon. It's sometimes easier to change the class of an element than to change the content.

Classy Material Icons works with either the Google Hosted Web Font method or the Self Hosted Web Font method defined in the [Material Icons Icon font for the web](http://google.github.io/material-design-icons/#icon-font-for-the-web) specifications. It does not change the default behavior, it only adds additional functionality.

It saved me a bunch of time on something, hopefully it will help you out as well.

### Example

The standard way to incorporate Material Icons into your web page looks like this:

`<i class="material-icons">face</i>`

Classy Material Icons allows you to also use this, and get the same result:

`<i class="material-icons icon-face"></i>`

You can also use codepoints:

`<i class="material-icons icon-e87c"></i>`

### Usage

First, if you are not already using Google Material Icons, add them to your project using [these steps](http://google.github.io/material-design-icons/#icon-font-for-the-web).

Second, grab the classy-material-icons.css file from the repo and add the file to your project.

`<link href="css/classy-material-icons.css" rel="stylesheet">`

Finally, use either of these additional methods to add icons to your project:

`<i class="material-icons icon-face"></i>`

`<i class="material-icons icon-e87c"></i>`

Note that you must append "icon-" to the icon name, or codepoint to create the class name. You can find the icon names on the [Material Icon](https://design.google.com/icons/) documentation and the codepoints within the [Material Icon repo](https://github.com/google/material-design-icons/blob/master/iconfont/codepoints).

### About

This was made by [Ben Markowitz](http://www.benmarkowitz.com). I'm a Senior Product Designer at [Protenus](http://www.protenus.com). You can follow me on [Twitter](http://www.twitter.com/bpmarkowitz).
