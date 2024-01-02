# Firefox-CSS

For now, the `Firefox-CSS` is based on the existing repository [Godiesc/Chameleons-Beauty](https://github.com/Godiesc/Chameleons-Beauty) and the Firefox theme [Beautiful GX Proton](https://addons.mozilla.org/en-US/firefox/addon/beautiful-opera-gx-proton/).

The goal is to make a `CSS` without third party stuff, but for now this approach must suffice.

## Installation

Set `toolkit.legacyUserProfileCustomizations.stylesheets = true` under `about:config` in [Firefox](https://www.mozilla.org/en-US/firefox/new/).

Set the theme in [Firefox](https://www.mozilla.org/en-US/firefox/new/) to the default dark theme that comes with the installation.

Goto to the `Root Directory` of the `Default Profile` of Firefox. Can be found via `about:profiles` in [Firefox](https://www.mozilla.org/en-US/firefox/new/).

```sh
cd ~/.mozilla/firefox/profiles/<default-profile-folder>/
```

Clone the repository into the profile directory as follows:

``` sh
git clone https://github.com/Godiesc/Chameleons-Beauty chrome
git clone https://github.com/tonigineer/firefox-css chrome_edit
```

Now edit the `userChrome.css` of the `Chameleons-Beauty` repository:

```sh
echo "@import url('../chrome_edit/changes.css');" >> chrome/userChrome.css
```

Restart [Firefox](https://www.mozilla.org/en-US/firefox/new/).
