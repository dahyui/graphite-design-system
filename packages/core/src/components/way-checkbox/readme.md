# way-button



<!-- Auto Generated Below -->


## Properties

| Property        | Attribute       | Description                                                     | Type      | Default        |
| --------------- | --------------- | --------------------------------------------------------------- | --------- | -------------- |
| `checked`       | `checked`       | Set to true to draw the checkbox in a checked state.            | `boolean` | `false`        |
| `disabled`      | `disabled`      | Set to true to disable the checkbox.                            | `boolean` | `false`        |
| `indeterminate` | `indeterminate` | Set to true to draw the checkbox in an indeterminate state.     | `boolean` | `false`        |
| `name`          | `name`          | The name of the control, which is submitted with the form data. | `string`  | `this.inputId` |
| `value`         | `value`         | The checkbox's value attribute.                                 | `string`  | `undefined`    |


## Events

| Event        | Description                                       | Type               |
| ------------ | ------------------------------------------------- | ------------------ |
| `way-blur`   | Emitted when the control loses focus.             | `CustomEvent<any>` |
| `way-change` | Emitted when the control's checked state changes. | `CustomEvent<any>` |
| `way-focus`  | Emitted when the control gains focus.             | `CustomEvent<any>` |


## Methods

### `removeFocus() => Promise<void>`

Removes focus from the checkbox.

#### Returns

Type: `Promise<void>`



### `setFocus(options?: FocusOptions) => Promise<void>`

Sets focus on the checkbox.

#### Returns

Type: `Promise<void>`




## Slots

| Slot | Description           |
| ---- | --------------------- |
|      | The checkboxes label. |


## CSS Custom Properties

| Name                                       | Description                                            |
| ------------------------------------------ | ------------------------------------------------------ |
| `--control-background-color`               | Background color of the control                        |
| `--control-background-color-checked`       | Background color of the control when checked           |
| `--control-background-color-checked-hover` | Background color of the control when checked on hover  |
| `--control-background-color-hover`         | Background color of the control on hover               |
| `--control-border-color`                   | Border color of the control                            |
| `--control-border-color-checked`           | Border color of the control when checked               |
| `--control-border-color-checked-hover`     | Border color of the control when checked on hover      |
| `--control-border-color-hover`             | Border color of the control on hover                   |
| `--control-color-checked`                  | Color of the control when checked (the checkmark icon) |
| `--control-size`                           | Size of the control                                    |
| `--label-color`                            | Color of the label                                     |


----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*