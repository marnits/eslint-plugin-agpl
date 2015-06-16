eslint-plugin-agpl
===================

![Travis status](https://api.travis-ci.org/ArekZc/eslint-plugin-agpl.svg)

Eslint rules for AGPL

# Installation

Install [ESLint](https://www.github.com/eslint/eslint) either locally or globally

<pre>
npm install eslint
</pre>

If you installed `Eslint` globally, you have to install `eslint-plugin-agpl` plugin globally too. Otherwise, install it locally.

<pre>
npm install eslint-plugin-agpl
</pre>

# Configuration

Add `plugins` section and specify eslint-plugin-agpl as a plugin

```json
{
  "plugins": [
    "agpl"
  ]
}
```
Finally, enable all of the rules that you would like to use.

```json
{
  "rules": {
    "agpl/valid-license": 1
  }
}
```
# List of supported rules

* [valid-license](docs/rules/valid-license.md):

# license

eslint-plugin-smells is licensed under the [MIT License](http://www.opensource.org/licenses/mit-license.php).
