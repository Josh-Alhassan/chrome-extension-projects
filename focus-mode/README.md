This project builds an extension that simplifies the styline of the Chrome extension and Web store documentation pages so that they are easier to read.

Extensions can monitor browser events in the background using the extensions service worker.

*Service workers* are special JavaScript environments that are loaded to handle events and terminated when they're no longer needed.

`runtime.onInstalled()` method allows the extension to set an intial state or complete some tasks on installation.

Extensions can use the _storage API_ and _indexDB_ to store the application state.

The extension `action` controls the extension's toolbar icon. So whenever the user clicks on the extension action, it will either run some code or display a popup.

The `activeTab` permission grants the extension temporary ability to execute code on the currently active tab. It allows access to _sentitive properties_ of the _current tab_.