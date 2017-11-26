# Temporary Containers Firefox Add-on

[![Build Status](https://travis-ci.org/stoically/firefox-add-on-temporary-containers.svg?branch=master)](https://travis-ci.org/stoically/firefox-add-on-temporary-containers)

Open Tabs in new Temporary Containers when:
* Clicking the "Temporary Containers"-Icon
* Pressing the Alt+C Shortcut

With "Automatic Mode" active (default):
* Clicking the "New Tab"-Icon
* Clicking "New Tab" or "New Window" in the Browser Menu
* Pressing the Ctrl+T or Ctrl+N Shortcut
* MiddleMouse Click on a Link on a Website
* Ctrl+LeftMouse Click on a Link on a Website
* An external Program opens a http(s) Link in the Browser

Never open Tabs in new Temporary Containers when:
* Regular click on a Link on a Website
* Website redirects or opens new Tab itself
* Clicking "New Tab" in the RightClick ContextMenu on a Link on a Website
* Pressing Shift+LeftMouseClick on a Link on a Website

[Get it here.](https://addons.mozilla.org/en-US/firefox/addon/temporary-containers/)

## Notes
If you have any Suggestions, Feedback or BugReports please make sure to leave me an Issue here on GitHub.

Works together with [Multi-Account Containers](https://github.com/mozilla/multi-account-containers).

The automatically created Temporary Containers get removed 5 seconds after the Last Tab in a given Temporary Container closes. Sometimes removing the Temporary Container doesn't work immediately - but don't worry, not needed Temporary Containers will automatically get removed eventually!


## Limitations
* Opening a "New Window" or starting Firefox, only opens a Temporary Container if you <strong>don't</strong> set the Preference "When Firefox starts" to "Show a blank page". Although as soon as you start navigating to a http(s) Website it will convert the Tab to a Temporary Container one.
* Disabled in "Private Windows" since Firefox doesn't support it
* MiddleMouse and Ctrl+LeftMouse Click don't work on addons.mozilla.org


## Known Bugs
This Add-on is in rapid development. Expect Bugs. Currently in the Bugfix queue are:
* Disable/Enable sometimes breaks the Add-on because of local storage problems. Remove/Add as workaround to get it working again.


## Privacy
There's a discussion about [Moving between containers](https://github.com/mozilla/multi-account-containers/wiki/Moving-between-containers) and I think that this Add-on enhances privacy by providing Temporary/Throw-away/Disposable Containers whenever possible, while not breaking normal navigation or e.g. OAuth redirects on a given Website.


## License

MIT
