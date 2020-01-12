# The Dark Knight
[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/VikasSharma.the-dark-knight?color=blue)](https://marketplace.visualstudio.com/items?itemName=VikasSharma.the-dark-knight)
[![Visual Studio Marketplace Rating (Stars)](https://img.shields.io/visual-studio-marketplace/stars/VikasSharma.the-dark-knight)](https://marketplace.visualstudio.com/items?itemName=VikasSharma.the-dark-knight)
![GitHub repo size](https://img.shields.io/github/repo-size/vikas0sharma/the-dark-knight?color=purple)

**Not the theme you deserve, but the one you need right now!!**

> I am vengeance!

> I am the night!

> I am Batman!

Batman inspires so many people, always been my childhood hero I would not call him superhero because he is not, he is the one trying to right the wrong in the society without any superpower.

> A hero can be anyone. Even a man doing something as simple and reassuring as putting a coat around a young boy's shoulders to let him know that the world hadn't ended

I have created this theme dedicated to Batman.

If you are a Batman fan like me then you definitely gonna like this theme.

## Screen
![screen](https://raw.githubusercontent.com/vikas0sharma/the-dark-knight/master/screens/screens.png)

## Enable Wallpaper and glow

Install [this](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) excellent plugin that allows you to load custom CSS and JS from the VS Marketplace. Please carefully read the ReadMe regarding permission for that extension before continuing with this installation.

Locate the-dark-knight.css either in this extension's VS code install directory, or directly from the [github repo](https://github.com/vikas0sharma/the-dark-knight/blob/master/the-dark-knight.css).

Copy your chosen CSS file to a location on your machine, such as your user folder. Copy the file path and add it to your VS code settings.json. On Mac it might look something like the snippet below:

```javascript
{
  "vscode_custom_css.imports": [
    "file:///Users/{your username}/the-dark-knight.css"
    ],
    "vscode_custom_css.policy": true,
}
```
Windows might resemble:

```javascript
{
  "vscode_custom_css.imports": [
    "file:///C:/Users/{your username}/the-dark-knight.css"
    ],
    "vscode_custom_css.policy": true,
}
```

Important: Make sure you include the file protocol in the path i.e. file://

Open your command palette with Ctrl + Shift + P or Shift + ⌘ + P and choose "Enable custom CSS and JS". It will prompt you to restart, and when you do the lights should be on :)

At this point, VS Code may pop up a message to say that it is corrupted, this is caused by the custom CSS & JS extension and not this theme. As their installation instructions say, you can click "Don't show again" to dismiss the popup.

NOTE: Every time you update VS code, you will need to repeat this step to re-enable custom CSS and JS. Similarly, when the theme updates, you will need to copy the updated css to your chosen location.

This is less than ideal, but until VS code add the option to use custom CSS natively, it's unfortunately the only option.
