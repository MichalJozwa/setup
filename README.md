# This is setup repo for start new projects
You can clone it on your own.

## Using
You need a css compiler (scss to css) which compile scss files to the css folder.
The easiest way, if you're using VS Code editor, is use e.g.:
 - "Live Sass Compiler" by Ritwick Dey - https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass

The best you can use the potential of the project is change the [Live Sass Compiler] json file, through `File>Preferences>Settings>(search) "Live Sass Compile > settings: Formats"> Edit in settings.json`

Edit the latest lines as below: 
_Note: If you don't have this lines, just copy them to your json file from below, or check [explain of it]._
```sh
"liveSassCompile.settings.formats":[
   {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": "~/../css/"
   }
]
```

   [Live Sass Compiler]: https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass
   [explain of it]: https://github.com/ritwickdey/vscode-live-sass-compiler/blob/master/docs/settings.md
