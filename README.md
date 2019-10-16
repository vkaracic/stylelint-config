<p align="center">
  <a href="#">
    <img width="100" src="logo.png">
  </a>
</p>

# @extensionengine/stylelint-config

[![circleci build status](https://badgen.net/circleci/github/ExtensionEngine/stylelint-config/master?icon)](https://circleci.com/gh/extensionengine/stylelint-config)
[![npm package version](https://badgen.net/npm/v/@extensionengine/stylelint-config)](https://npm.im/@extensionengine/stylelint-config)
[![github license](https://badgen.net/github/license/extensionengine/stylelint-config)](https://github.com/extensionengine/stylelint-config/blob/master/LICENSE)

This package provides Extension Engine's extensible stylelint config.

## Usage

Configuration supports `css` and `scss`.

### Install

Use `install-peerdeps`

```
npx install-peerdeps --dev @extensionengine/stylelint-config
```

or the classic way:

```
npm install --save-dev stylelint @extensionengine/stylelint-config
```

### Using `@extensionengine/stylelint-config` in your project

In your local `stylelint.config.js` extend this configuration

```js
'use strict';

module.exports = {
  extends: '@extensionengine'
};
```

Check [stylelint documentation](https://stylelint.io/user-guide/rules) for rules explanation.


### Badge

If you are using this config in your project you can include this badge in a
readme to let people know that your code is using it.

[![js @extensionengine style](https://badgen.net/badge/stylelint/@extensionengine/black)](https://github.com/ExtensionEngine/stylelint-config)

```markdown
[![js @extensionengine style](https://badgen.net/badge/stylelint/@extensionengine/black)](https://github.com/ExtensionEngine/stylelint-config)
```