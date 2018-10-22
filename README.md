# Accessibile inline error message associated with fieldset and radio buttons

Demo version: https://russmaxdesign.github.io/accessible-error-fieldset/

## Methods

The following methods have been used to programmatically associated the error message with the radio buttons within a `fieldset`:

**Method 1**: no programmatic association.

**Method 2**: `aria-describedby` attribute applied to the `fieldset` element

**Method 3**: `aria-describedby` attribute applied to the `legend` element

**Method 4**: `aria-describedby` attribute applied to all `input` elements

## Tests

The following tests are to determine if the error message is programmatically associated with the radio buttons within a `fieldset`:

**Test 1**: The error message is announced with first checked radio button when it receives focus (when traveling forward through form)

**Test 2**: The error message is announced with last checked radio button label when it receives focus (when traveling backwards through form)

**Test 3**: The error message is announced with a checked radio button when it receives focus (when traveling forward through form)

**Test 4**: The error message is announced with a checked radio button when it receives focus (when traveling backwards through form)

See [Licence information](LICENCE) for use.
