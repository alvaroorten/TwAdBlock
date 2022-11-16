# TwAdBlocker

uBlock Origin script to block Tw.tv ads.

**Don't combine Twitch specific ad blockers.**

## Script

- twitch-videoad - [ublock](https://github.com/alvaroorten/TwAdBlock/raw/main/twitch-videoad-ublock.js) | [ublock (permalink)](https://github.com/alvaroorten/TwAdBlock/blob/540c226749de6358c90c0354a59129afcf745b82/twitch-videoad-ublock.js)
  - `Video Ad-Block, for Twitch`, as a script.
  - *If the ad-free stream fails you'll see an adblocker warning.*

*For the sake of security it's recommended to use a permalink when using uBlock Origin (permalinks do not auto update).*

## Applying a script (uBlock Origin)

- Navigate to the uBlock Origin Dashboard (the extension options)
- Under the `My filters` tab add `twitch.tv##+js(twitch-videoad)`.
- Under the `Settings` tab, enable `I am an advanced user`, then click the cog that appears. Modify the value of `userResourcesLocation` from `unset` to the full url of the solution you wish to use (if a url is already in use, add a space after the existing url). e.g. `userResourcesLocation https://github.com/alvaroorten/TwAdBlock/raw/main/twitch-videoad-ublock.js` 
- To ensure uBlock Origin loads the script I recommend that you disable/enable the uBlock Origin extension (or restart your browser).

*To stop using a script remove the filter and make the url `unset`.*
