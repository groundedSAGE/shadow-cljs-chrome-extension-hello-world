# Shadow-cljs Chrome Extension Devtool Panel


## Development

```bash
yarn install
yarn dev
```

### Load the dev extension into the Chrome browser

1. Go to `chrome://extensions/`
2. Turn on **developer mode** in top right
3. Load unpacked `your-file-path-to/chrome-extension-hello-world/shells/chrome`


To view the background page click here

![Hello World Extension background page](images/chrome-extension.jpg)

To view the datalog panel open the Chrome console with either of these options.
- Right click anywhere on the page -> Inspect
- **Option + ⌘ + J**   (on macOS)
- **Shift + CTRL + J** (on Windows/Linux)

## Connect REPL

You can connect a repl to each process by opening new windows in your terminal and doing the following.

To connect to the background page
`yarn repl-background`

To connect to the devtool panel in the chrome console
`yarn repl-panel`