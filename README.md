# stylelint-max-lines
Limit the count of a lines.

## Installation

1. If you haven't, install [stylelint]:

```
npm install stylelint --save-dev
```

2.  Install `stylelint-order`:

```
npm install stylelint-max-lines --save-dev
```

## Usage

Add `stylelint-max-lines` to your stylelint config `plugins` array, then add rules you need to the rules list. All rules from stylelint-max-lines need to be namespaced with `pitcher`.

```json
{
    "plugins": [
        "stylelint-max-lines"
    ],
    "rules": {
        "pitcher/max-lines": 300
    }
}
```
