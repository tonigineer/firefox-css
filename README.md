# Firefox-CSS



## Installation

Set `toolkit.legacyUserProfileCustomizations.stylesheets = true` under `about:config` in [Firefox](https://www.mozilla.org/en-US/firefox/new/).

Set the theme in [Firefox](https://www.mozilla.org/en-US/firefox/new/) to the default dark theme that comes with the installation.

Goto to the `Root Directory` of the `Default Profile` of Firefox. Can be found via `about:profiles` in [Firefox](https://www.mozilla.org/en-US/firefox/new/).

```sh
cd ~/.mozilla/firefox/profiles/<default-profile-folder>/
```

Clone the repository into the profile directory as `chrome` folder.

``` sh
git clone https://github.com/tonigineer/firefox-css chrome
```

Restart [Firefox](https://www.mozilla.org/en-US/firefox/new/).