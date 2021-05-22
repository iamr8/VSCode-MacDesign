# VSCode-MacDesign
A bunch of settings to mac-like visual studio for windows

## Preview
![macstyle](/screenshot.png)

## How to install
* Install [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) in `vscode`.
    * For better knowledge, visit [extension's repo](https://github.com/be5invis/vscode-custom-css)
* Download [`mac-style.css`](/mac-style.css)
* Open your VSCode's `settings.json` ( [How to find](https://code.visualstudio.com/docs/getstarted/settings) )
* Add following line and save:
    ```
    "vscode_custom_css.imports": [
        "file:///{your-style-location}.css"
    ]
    ```

    *Your-style-location*: The location your downloaded css file has been located.
* Try to activate extension in vscode by Pressing `F1`, and entering `Enable Custom CSS and JS`.
* VSCode asks you to restarts the application and you have to accept.

## Optional
The font-family name located in css file, in better to be mac fonts, and i strongly recommend to use `SF Pro Rounded`

Also, you can use `SF Mono` font for codes by using the following line to `settings.json`
```
 "editor.fontFamily": "SF Mono",
 "editor.fontWeight": "normal",
```

## Known issue
After enabling the extension, you will face VSCode's alert about corruption. Just try to click `Don't show again`. It is not important.