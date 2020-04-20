![Image description](readme_header.jpg)


# Font Awesome 5 Pure CSS
**A solution to include a local version of Font Awesome 5, to increase loading speed and allow you to work localy without an Internet connection.**

&nbsp;
&nbsp;
&nbsp;

## What's the idea behind this project?
**Do more, install less.** This project gives you the strict minimum that you need to quickly start using the 1588 icons of Font Awesome 5.

&nbsp;
&nbsp;
&nbsp;

## Why is there only .woff font files?
Woff font format is supported by every modern browser: https://caniuse.com/#search=woff, and Font Awesome works fine with only these files.

&nbsp;
&nbsp;
&nbsp;

## How to install & use this local repository in your project?

1) Copy the entire 'fa' folder into your project directory


2) Link your web files to the 'fa' folder using the link rel tag in your ```<head>```:

  ```<link rel="stylesheet" href="fa/all.min.css">```
  

3) And voilà! Use it as you want!

Exemple: ```<span class="fas fa-search">Search</span>```

&nbsp;
&nbsp;
&nbsp;

## Font Awesome 5 notes
The 'fa' prefix has been deprecated in version 5. The new default is the 'fas' (solid) style and the 'fab' style for brands.

Find all the available icons here: https://fontawesome.com/icons?d=gallery&m=free
