# bem-textarea-editor

textarea-editor component based on [i-bem.js](https://en.bem.info/platform/i-bem/).

[Demo](https://tadatuta.github.io/bem-textarea-editor/).

Uses [textarea-editor](https://github.com/eivindfjeldstad/textarea-editor) under the hood.
Depends on [bem-font-awesome-icons](https://github.com/tadatuta/bem-font-awesome-icons/).

## Installation

1. Install packages via `npm`
```
npm i bem-textarea-editor bem-font-awesome-icons --save-dev
```
or `bower`
```
bower i bem-textarea-editor bem-font-awesome-icons --save
```

2. Add `bem-textarea-editor/common.blocks` and `bem-font-awesome-icons` as redefinition levels to your build config.

## Usage

```js
{
    block: 'editor',
    mods: {
        theme: 'islands',
        size: 'm',
        width: 'available',
        mode: 'source',
        renderer: 'marked',
        'has-preview': true,
        'has-actions': true
    }
}
```
