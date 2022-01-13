## Contributing Guide

### Make Changes
Follow this guide when editing existing or adding new translations:

1. Create an Issue with the language code: `Translations - en-US`. We will assign responsible translators to the
   issue and mention you, if updates or changes are required.
2. Fork this repository.
3. Create a file with the IETF language tag (RFC 5646) [[1]](https://gist.github.com/msikma/8912e62ed866778ff8cd) of the language in the `translations` directory, for example: `en-US.lang`.
4. Commit your changes (see: Translation Guidelines).
5. Open a pull request.

#### Caveats

* If the base translations (en-US) ever change, you need to open a new pull request to update the translations.
* If the translations aren't updated in time, they won't be included in the client update.

### Translation Guidelines
1. Do NOT edit translation keys (the part before `=`).
2. Do NOT translate Feature names, Command syntaxes, etc.
3. Long values are advised against, as they may cause problems in the UI.

### Commits Conventions
1. Prefix commits with the language code: `[ru-RU] Add translations for ...`
2. Use verbs in bare infinitive as the first word after the tag