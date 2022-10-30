# Prettier Setup guide

The Respository contains a sample Vite typescript app that is fomatted with prettier

## Visual Studio code setup

1. Install Prettier plugin

1. Update Editor Preferences

    Press **CTRL+SHIFT+P** or **CMD+SHIFT+P** type in

    > open user settings json

    update the settings file

    ```json
    {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    }
    ```

    Aditional Information can be found at
    https://prettier.io/docs/en/editors.html

## Installing prettier

1. Install prettier package
    ```sh
    npm install --save-dev --save-exact prettier
    ```
1. create configuration file for prettier
    ```sh
    echo {}> .prettierrc.json
    ```
1. Configuration files can be updated based on user's formatting preferences
