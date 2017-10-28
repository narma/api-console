[![Build Status](https://travis-ci.org/advanced-rest-client/paper-input.svg?branch=stage)](https://travis-ci.org/advanced-rest-client/paper-input)  

# paper-input

`<paper-input>` single line text input styled for the Anypoint platform as a Polymer
powered web component

It may include an optional error message.
```
<paper-input required error-message="Value is required"></paper-input>
```

It may include a custom validator(s).
```
<paper-input validator="my-validator" error-message="Value is required"></paper-input>
```
See `Anypoint.AnypointValidatableBehavior` for API and examples.

### Styling

See `anypoint-text-container` for styling options.



### Events
| Name | Description | Params |
| --- | --- | --- |
| change | Fired when the input changes due to user interaction. | __none__ |
# paper-input-container


The `<paper-input-container>` is a container for a `label` and input text styled to match the
Anypoint platform styling.

### Styling

`<paper-input-field>` provides the following custom properties and mixins for styling:

Custom property | Description | Default
----------------|-------------|----------
`--paper-input-container` | Mixin applied to the input container | `{}`
`--paper-input-container-disabled` | Mixin applied to the disabled container | `{}`
`--paper-input-container-border` | Mixin applied to the border element on the left and right hand side of the input | ``
`--paper-input-container-border-focused` | Mixin applied to the border element on the left and right hand side of the input | ``
`--paper-input-container-border-color` | Color of the right and left border of the input | `--anypoint-color-aluminum4`
`--paper-input-container-border-focused-color` | Color of the right and left border of the input when the input is focused | `--anypoint-color-steel2`
`--paper-input-container-invalid-color,` | Error color | `--anypoint-color-danger`
`--paper-input-container-label-color` | Color of the label | `--anypoint-color-aluminum5`
`--paper-input-container-label` | Mixin applied to the label | `{}`
`--paper-input-container-label-floating` | Mixin applied to the floating label | `{}`
`--paper-input-container-label-focus` | Mixin applied to the label when focused | `{}`
`--paper-input-container-focus-color` | Color applied to the label and input when focused | `--anypoint-color-aluminum5`
`--paper-input-field-prefix` | Mixin applied to any prefix element added to the container | `{}`
`--paper-input-field-suffix` | Mixin applied to any suffix element added to the container | `{}`
`--paper-input-container-input-color` | Color of the input control | `--anypoint-color-steel5`
`--paper-input-container-input` | Mixin applied to the input control | ``

# paper-input-error

The `<paper-input-error>` is a container for an error message or list of validation
rules if the input element uses `validator`s.

### Styling

Custom property | Description | Default
----------------|-------------|----------
`--paper-input-error-container` | Mixin applied to the element | `{}`
`--paper-input-error-border-color` | Border color of the popover | `--anypoint-color-aluminum3`
`--paper-input-error-left-border` | Color of the right border of the popover | `--anypoint-color-steel4`
`--anypoint-text-container-invalid-color` | Color of error messages and borders when corresponding form control is invalid | `--anypoint-color-danger`
`--paper-input-error-message-size` | Font size of the validation message. | `12px`

