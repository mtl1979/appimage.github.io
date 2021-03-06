---
layout: app

permalink: /Museeks/
description: A simple, clean and cross-platform music player, written with Node.js, Electron and React.js.
license: MIT

icons:
  - Museeks/icons/128x128/museeks.png

screenshots:
  - Museeks/screenshot.png

authors:
  - name: KeitIG
    url: https://github.com/KeitIG

links:
  - type: GitHub
    url: KeitIG/museeks
  - type: Download
    url: https://github.com/KeitIG/museeks/releases

desktop:
  Desktop Entry:
    Name: Museeks
    Comment: A simple, clean and cross-platform music player, written with Node.js,
      Electron and React.js.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: museeks
    X-AppImage-Version: 0.9.4
    X-AppImage-BuildId: bb6899a0-46cb-11a8-183b-2b942b640ac2
    Categories: AudioVideo
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  description: A simple, clean and cross-platform music player, written with Node.js,
    Electron and React.js.
  main: "./src/main/main.js"
  repository:
    type: git
    url: https://github.com/KeitIG/museeks
  author: Pierre de la Martinière <pierre.de.la.martiniere@gmail.com>
  license: MIT
  bugs:
    url: https://github.com/KeitIG/museeks/issues
  dependencies:
    bootstrap-css-only: 3.3.7
    classnames: 2.2.5
    font-awesome: 4.7.0
    globby: 8.0.1
    history: 4.7.2
    keymirror: 0.1.1
    level-js: 2.2.4
    linvodb3: 3.25.1
    lodash: "^4.17.5"
    music-metadata: 0.10.2
    open-sans-fontface: 1.4.0
    prop-types: 15.6.1
    queue: 4.4.2
    react: 16.3.0
    react-bootstrap: 0.32.1
    react-custom-scrollbars: 4.2.1
    react-dom: 16.3.0
    react-fontawesome: 1.6.1
    react-keybinding-component: 0.5.1
    react-redux: 5.0.7
    react-router: 4.2.0
    react-router-bootstrap: 0.24.4
    react-router-dom: 4.2.2
    react-simple-input: 0.4.1
    react-svg-inline: 2.1.0
    redux: 3.7.2
    redux-thunk: 2.2.0
    semver: 5.5.0
    teeny-conf: 1.1.0
---
