# Roblox Byfron Bypasser

This is a Chrome extension that bypasses Roblox's Byfron system by changing your Roblox channel. It reverts any channel builds that Roblox has placed on your account and reverts them back to the normal version that everyone should have.

# Roblox Byfron Bypasser

This is a Chrome extension and Tampermonkey script that reverts any channel builds that Roblox has placed on your account and reverts them back to the normal version everyone should have.

## Installation

### Option 1: Installing the Chrome Extension

1. Download the latest release of the Roblox Byfron Bypasser from the [releases page](https://github.com/USERNAME/REPOSITORY/releases).
2. Extract the `extension.zip` file.
3. Open the Chrome Extensions page by entering `chrome://extensions/` in the address bar.
4. Enable "Developer mode" by clicking the toggle switch in the upper right corner.
5. Click "Load unpacked" and select the extracted `extension` folder.
6. The extension should now be installed and ready to use.

### Option 2: Installing the Tampermonkey Script

1. Install the Tampermonkey extension for your browser.
2. Click on the `bypass.user.js` file in this repository.
3. Click the "Raw" button in the upper right corner to view the raw script.
4. Tampermonkey should detect the script and open a new tab asking you to install the script. Click "Install" to add the script to Tampermonkey.
5. Navigate to any Roblox game or webpage to start using the script.


## Usage

Once the extension is installed, it will automatically bypass Roblox's Byfron system whenever you visit a Roblox page. You do not need to take any further action to use the extension.

## Technical Details

The bypass functionality is implemented as a user script in `bypass.user.js`. The user script modifies the `Roblox.ProtocolHandlerClientInterface` object to set the `playerChannel`, `channel`, and `studioChannel` properties to empty strings, effectively bypassing the Byfron system.

The extension manifest is defined in `manifest.json` and specifies that the user script should be executed on any page that matches `https://*.roblox.com/*` or `https://roblox.com/*`.

## License

This extension is released under the MIT License. See the `LICENSE` file for more information.

## Credits

This extension was created by jinxz#1337.