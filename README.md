# Email Editor With Vue

The excellent drag-n-drop email editor. This is the most powerful and developer friendly visual email builder for your app.

## Installation

The easiest way to use Vue Email Editor is to install it from Npm or Yarn and include it in your own Vue build process.

```
npm install vue-email-editor --save
```

or

```
yarn add vue-email-editor
```

## Usage

Next, you'll need to import the Email Editor component to your app.

### Methods

| method         | params              | description                                             |
| -------------- | ------------------- | ------------------------------------------------------- |
| **loadDesign** | `Object data`       | Takes the design JSON and loads it in the editor        |
| **saveDesign** | `Function callback` | Returns the design JSON in a callback function          |
| **exportHtml** | `Function callback` | Returns the design HTML and JSON in a callback function |

See the [example source](https://github.com/unlayer/vue-email-editor/tree/master/src) for a reference implementation.

### Properties

- `editorId` `String` HTML div id of the container where the editor will be embedded (optional)
- `minHeight` `String` minimum height to initialize the editor with (default 500px)
- `options` `Object` options passed to the Unlayer editor instance (default {})
- `tools` `Object` configuration for the built-in and custom tools (default {})
- `appearance` `Object` configuration for appearance and theme (default {})
- `projectId` `Integer` Unlayer project ID (optional)
- `locale` `String` translations string (default en-US)
