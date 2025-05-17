Extension Live Sass Compiler

start mit 'watch sass' in VSC unten rechts von mitte

Einstellungen in settings.json
"liveServer.settings.CustomBrowser": "chrome:PrivateMode",
  "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.donotVerifyTags": true,
  "liveSassCompile.settings.formats": [
    {
      "format": "compressed",
      "extensionName": ".min.css",
      "savePath": "~/../css"
    }
  ],
  "liveSassCompile.settings.generateMap": false