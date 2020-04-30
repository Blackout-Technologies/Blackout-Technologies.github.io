# Captions

Captions enable your Hook to be multilingual. Captions are saved in the `captions.json` file.
The file must follow this scheme:

```json
{
    "languageCode0": {
        "key0": ["String0", ..., "StringP"],
           .
           .
           .
        "keyM": ["String0", ..., "StringP"]
    },
        .
        .
        .
    "languageCodeN": {
        "key0": ["String0", ..., "StringP"],
           .
           .
           .
        "keyM": ["String0", ..., "StringP"]
    }
}
```
The `languageCode` follows the ISO 639-1 standard.

A Sample captions file for english and german could look like this:

```json
{
    "en-US": {
        "sayQuote": ["{} would say: {}", "{} once said: {}"],
        "sayError": ["Unfortunately I couldn't find a quote for you."]
    },
    "de-DE": {
        "sayQuote": ["{} würde sagen: {}", "{} hat einmal gesagt: {}"],
        "sayError": ["Leider konnte ich kein Zitat für dich finden."]
    }
}
```
