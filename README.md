# Customized built-in elements `<spinning-dots>`

[![npm](https://img.shields.io/npm/v/@grafikart/spinning-dots-element.svg)](http://npm.im/@grafikart/spinning-dots-element)

The goal of this module is to have a reusable component to display a spinning loader. [Live demo](https://grafikart.github.io/CustomElement-SpinningDots/)

## Usage

### With npm

Install the package using npm or yarn

```bash
npm i @grafikart/spinning-dots-element
# or
yarn add @grafikart/spinning-dots-element
```

Then import it in your script

```js
import '@grafikart/spinning-dots-element'
```

### With unpkg.com

```html
<script type="module" src="//unpkg.com/@grafikart/spinning-dots-element"></script>
```

Then use the custom element in your html using `<spinning-dots>`.

```html
<-- This will create a loader with a 68px width  -->
<spinning-dots></spinning-dots>

<-- Everything scales according to the width -->
<spinning-dots style="width:100px;"></spinning-dots>

<-- Every configuration possible -->
<spinning-dots style="width:100px; stroke-width:20px; color: #535FF6;" dots="8"></spinning-dots>
```

### Attributes

| Attribute | Type     | Description                                          |
|-----------|----------|------------------------------------------------------|
| `dots`    | `number` | The number of dots to display                        |

### CSS Styles

This custom element is affected by these styles

| Property       |  Description                                       |
|----------------|----------------------------------------------------|
| `width`        | Set the size of the element                        |
| `stroke-width` | Set the width of the trail                         |
| `color`        | Set the color, inherit the parent color by default |

## Changelog

**0.0.1**

- Initial release
