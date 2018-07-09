<img align="right" width="32" src="Images/Icons/install_windows-0001.png" style="margin: 0 20px">

*GitHub Windows Edition: User style transforming GitHub into Windows 9x*
========================================================================

* [**GitHub repository**](https://github.com/Athari/CssGitHubWindows)

[![Install with Stylus](https://img.shields.io/badge/Install%20with-Stylus-00adad.svg)](https://raw.githubusercontent.com/Athari/CssGitHubWindows/master/GitHubWindows.user.css)

CssGitHubWindows is a user style which transforms GitHub's pages into GUI resembling Windows 9x. All modern browsers should be supported.

NOTE: the style is a proof-of-concept / alpha. Only some parts of the website have been fully transformed.

Screenshots
===========

![YaLinqo](Images/Screenshots/YaLinqo.png)

![CoreFX](Images/Screenshots/CoreFX.png)

Features
========

* Almost pixel-perfect reproduction of buttons, tabs, separators, groups, edit boxes, list boxes, tooltips, windows.
* Focus rectangles, text selection styles and other elements adjusted where possible.
* Some icons changed into icons from Windows 9x.
* Some UI has been transformed, for example repository stats are displayed as a shell list box and various group boxes have been titled.

Install
=======

You can use the **Stylus** extension. Stylus is free, and open-source  with more features; If your browser is neither Firefox nor Chrome, please refer to online guides, it gets more complicated.

Click on the extension title to see detailed instructions.

<details>
<summary><b>A. Stylus</b></summary>

1. Add Stylus extension to your browser:

   * [Stylus for Firefox]
   * [Stylus for Chrome]

2. Add user style:

   * Open [CSS file in this Gist](https://raw.githubusercontent.com/Athari/CssGitHubWindows/master/GitHubWindows.user.css).
   * Click "Install Style" button in the opened window.
</details>


Known issues
============

* Due to requirement of elements to have multiple borders, size of some controls like buttons has been changed. If GitHub uses pixel sizes for buttons, they may be cut by a few pixels.
* Due to tooltips being children of controls, they change full control size, so focus borders may be displayed incorrectly.

License
=======
Licensed under the [MIT License](License.md).

Links
=====

* [Source of inspiration](https://twitter.com/nikitonsky/status/1003593821723267072) — post on Twitter
* [Resource Hacker](http://www.angusj.com/resourcehacker/) — tool for extracting icons from executable files, including Windows 95 system files
* [PNG optimizer](https://tinypng.com/) — online tool for optimizing PNG files
* [Base64 encoder](https://www.base64-image.de/) — online tool for embedding images in CSS as data URIs
* [Simpler competitor](https://userstyles.org/styles/160991/github-windows-classic) — someone did that before
* [Stylus for Firefox] — modern extension for applying user styles for Firefox
* [Stylus for Chrome] — modern extension for applying user styles for Chrome

   [Stylus for Firefox]: https://addons.mozilla.org/en-US/firefox/addon/styl-us/
   [Stylus for Chrome]: https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmnefor/fjnbnpbmkenffdnngjfgmeleoegfcffe
