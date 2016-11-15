# selectize-plugin-clear
Plugin for Selectize which adds a "clear" button

## Usage
### Basic
Use the **plugins** option to turn on the plugin: 

```js
$("#element").selectize({
  plugins: ["clear_button"]
});
```

### Options

| Option        | Description                                      | Default value |
| ------------- |--------------------------------------------------|:-------------:|
| label         | Char that represents content of button           | "&amp;times;" |
| title         | Hint to display                                  | "Remove"      |
| className     | Css class added to button html element           | "clearAll"    |
| hideWhenEmpty | If true, button is hidden when no value selected | true          |
| leaveOpen     | If true, select will open      after clearing    | false         |

```js
$("#element").selectize({
  plugins: {
    "clear_button": {
       leaveOpen: true
     }
  }
});
```