# README
## This is the README for your extension "the-dark-knight"



## Enable Wallpaper and glow

Install this excellent plugin that allows you to load custom CSS and JS from the VS Marketplace. Please carefully read the ReadMe regarding permission for that extension before continuing with this installation.

Locate the-dark-knight.css either in this extension's VS code install directory, or directly from the github repo.

Copy your chosen CSS file to a location on your machine, such as your user folder. Copy the file path and add it to your VS code settings.json. On Mac it might look something like the snippet below:

{
  "vscode_custom_css.imports": [
    "file:///Users/{your username}/the-dark-knight.css"
    ]
}
Windows might resemble:

{
  "vscode_custom_css.imports": [
    "file:///C:/Users/{your username}/the-dark-knight.css"
    ]
}
Important: Make sure you include the file protocol in the path i.e. file://

Open your command palette with Ctrl + Shift + P or Shift + ⌘ + P and choose "Enable custom CSS and JS". It will prompt you to restart, and when you do the lights should be on :)

At this point, VS Code may pop up a message to say that it is corrupted, this is caused by the custom CSS & JS extension and not this theme. As their installation instructions say, you can click "Don't show again" to dismiss the popup.

NOTE: Every time you update VS code, you will need to repeat this step to re-enable custom CSS and JS. Similarly, when the theme updates, you will need to copy the updated css to your chosen location.

This is less than ideal, but until VS code add the option to use custom CSS natively, it's unfortunately the only option.