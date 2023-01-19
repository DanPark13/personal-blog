---
title: "About the Bilberry Theme"
date: 2021-11-01T09:31:27+01:00

categories: ['Code', 'Tutorials']
tags: ['Hugo', 'Bilberry Theme']
author: "Lednerb"
---
You will find all information to setup this theme with your hugo site
on the official <br> [Github Repository](https://github.com/Lednerb/bilberry-hugo-theme).

Bilberry is a premium theme for the [Hugo Static Website Builder](https://gohugo.io).

It is full of little nice features, such as:

- built-in integration for the wonderful [algolia search](https://algolia.com)
- built-in integration for the powerful [disqus comments](https://disqus.com)
- gravatar and custom image integration for the header
- keyboard shortcut for the search (press the `s` key, type something and hit `enter` or `esc`)
- responsive design - optimized for desktop and mobile devices
- full internationalization (i18n) support (en, de, fr, ru, es out of the box!)
- full multi-language support
- custom post types (`article`, `audio`, `code`, `gallery`, `link`, `page`, `picture`, `quote`, `video`)
    - easy configuration to add more according to your needs

*This Bilberry theme is inspired by the Lingonberry theme from [Anders Norén](http://www.andersnoren.se/teman/lingonberry-wordpress-theme/)*

**[Further information at GitHub](https://github.com/Lednerb/bilberry-hugo-theme)**

<!--more-->

__If you want to install this theme, follow these steps:__

- Install Hugo and create a new site:

```plaintext
hugo new site my-new-blog
```

- Switch to your `theme` folder and import the latest version of the Bilberry Theme

```plaintext
cd my-new-blog/themes
git clone https://github.com/Lednerb/bilberry-hugo-theme.git
```

- Copy the example content to your new site

```plaintext
cp -r bilberry-hugo-theme/exampleSite/* ../
```

- Test the installation

```plaintext
cd ../
hugo server -D
```

- Configure the `config.toml` file according to your needs
- Start blogging
