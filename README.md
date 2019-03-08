# css-checkbox
> Friendly CSS checkbox control

[![Build Status](https://travis-ci.org/frekyll/css-checkbox.svg?branch=master)](https://travis-ci.org/frekyll/css-checkbox)

This is inspired by [wtf-forms](https://github.com/mdo/wtf-forms). I often find myself copying this source, so I made a package.

## Features
- Create a larger hit area for checking the control
- Replace the default `<input>` with a semantic wrapper
- Trigger the state of `<input>` automatically

## Example

```html
<label class="checkbox">
	<input type="checkbox">
	<span class="checkbox-indicator"></span>
	Custom checkbox
</label>
```

## Usage

You could use a tool like [sheetify](https://github.com/stackcss/sheetify) to consume.

```js
var css = require('sheetify')

css('css-checkbox')
```

## Install

### npm
`npm install css-checkbox`

## Related
- [minimal-reset](https://github.com/frekyll/minimal-reset)
- [sheetify](https://github.com/stackcss/sheetify)
- [wtf-forms](https://github.com/mdo/wtf-forms)
