# Contributing to Spryker Translations

Corrections and new translations/locales can be added through pull requests.

Please see the following guidelines:

* Translations can only be added, never removed (to ensure BC to older versions of Spryker modules).
* Keep alphabetical order based on key (first column)
* `"` needed only for multi-words (does not count into ordering)
* Do not translate literal values, technical terms and code pieces, instead use placeholders here

## Tips

* Keep literal values, or colons etc out of the translation itself: Do this: might better be Do this and the colon part of the code instead.
* `"` inside a translation string need to be escaped using a 2nd one: `"A ""quoted"" string"`
* `%` is the placeholder for generic strings when using sprintf(). You can also use more specific placeholders here like `%d` for numeric values.