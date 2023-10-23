# BEPRO Locales
This repository is responsible for the translation of the [BEPRO decentralized marketplace](https://app.bepro.network)

## Folder structure
```
|- locales/ 
|-- [locale-name]/
|--- [page-name].json
```

## New translations
- Create a new locale folder with the locale name under `locales/` folder
- Copy the json files from `locales/en/*.json`
- Translate the files into your locale under your locale folder _without changing the json files names_ and _the json keys_
```json5
// example.json
{
  "this-is-a-key": "This is a key",
  "this-is-a-group-of-keys": {
    "another-key": "value of another key inside a group of keys"
  }
}
```
`this-is-a-key` **cannot** be translated. its value (`"This is a key"`) is want needs to change; This also applies for
any groups of keys.