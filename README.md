# Built with Polymer

Web components are the `<bees-knees>`. Built with Polymer is a showcase of awesome Polymer projects. And yes, this static website (generated by Middleman) also uses Polymer. It's hosted on [Divshot](https://divshot.com).

## Submit Your Project

Build something cool? Fork this repo and send a pull request after you've added a new blog post with the following format:

```
---
title: Polymer Project
url: http://www.polymer-project.org
date: 2014-09-01
tags: core-collapse, core-icon, core-item, core-media-query, core-menu, core-selection, core-selector, dropdown-panel, feature-carousel, paper-button, paper-icon-button, paper-ripple, paper-shadow
---

[![Polymer Project](screenshots/polymer-project.png)](http://www.polymer-project.org)

Write a short description here. For the image above, use [![Image Title](Image URL)](Website URL).
```

We're looking for complete apps and websites that use Polymer in a significant way. If you'd like to show off your shiny new web component, head on over to [Custom Elements](http://customelements.io/) and [Component Kitchen](http://component.kitchen/)!

### Filename

Use the current date for your filename and frontmatter, e.g. `2014-09-10-polymer-project.markdown` and `date: 2014-09-10`. Add the Markdown file inside `/source/blog`.

### Tags

To generate a list of tags (custom elements used by your project), install the [Polymer Ready](https://chrome.google.com/webstore/detail/aaifiopbmiecbpladpjaoemohhfjcbdk/) extension by François Beaufort. Only provide tags/elements that are common and not specific to your app, such as core and paper elements.

### Screenshot

`1440x804` is the recommended dimensions for screenshots. Use your best judgment. 1136px is the absolute minimum width for high density displays. Keep the file size below 350 KB. Add one screenshot `/images/screenshots` with the title of your project. Use `png`, `jpg`, or `webp`.

## Running Locally

```
bundle install & bower update
middleman server
```

Now you should be able to go to `http://localhost:4567` to see the website locally.
