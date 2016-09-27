
Reload browser tabs from the terminal in OSX.

Uses a sneaky four-line AppleScript that works across all[1] browsers.

### Usage

```bash
	# 1. reload front-most tab in Google Chrome containing 'github' in the URL
	#    ^- this is almost valid AppleScript
    reload-browser chrome github

    # 2. reload URL containing 'localhost' in Safari
    reload-browser safari localhost
```

### Install

Copy the `reload-browser` script to your favorite bin folder (`/usr/local/bin`, `~/bin`). Or, if you trust me, and github:

`curl -o /usr/local/bin/reload-browser https://raw.githubusercontent.com/ricardobeat/reload-browser/master/reload-browser && chmod +x /usr/local/bin/reload-browser`

### TODO

- publish executable somewhere

_[1] not all_

_[2] Firefox doesn't work_

_[3] Opera not supported_