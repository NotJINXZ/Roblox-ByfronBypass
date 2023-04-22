# Roblox Byfron Bypasser

This is a Chrome extension that bypasses Roblox's Byfron system by changing your Roblox channel. It reverts any channel builds that Roblox has placed on your account and reverts them back to the normal version that everyone should have.

## Installation

1. Clone or download this repository to your local machine.
2. Open Google Chrome and go to `chrome://extensions/`.
3. Enable "Developer mode" in the top right corner.
4. Click on "Load unpacked" and select the directory of this extension on your local machine.
5. The extension should now be installed and active in your Chrome browser.

## Usage

Once the extension is installed, it will automatically bypass Roblox's Byfron system whenever you visit a Roblox page. You do not need to take any further action to use the extension.

## Technical Details

The bypass functionality is implemented as a user script in `bypass.user.js`. The user script modifies the `Roblox.ProtocolHandlerClientInterface` object to set the `playerChannel`, `channel`, and `studioChannel` properties to empty strings, effectively bypassing the Byfron system.

The extension manifest is defined in `manifest.json` and specifies that the user script should be executed on any page that matches `https://*.roblox.com/*` or `https://roblox.com/*`.

## License

This extension is released under the MIT License. See the `LICENSE` file for more information.

## Credits

This extension was created by jinxz#1337.