# iCleaner localizations

This repository contains the current [iCleaner](http://ib-soft.net/icleaner) localization files. You can contribute either by [creating a new localization](#create-a-new-localization) or by [completing or fixing an existing one](#complete-or-fix-an-existing-localization).

## Instructions

### Create a new localization

If iCleaner does not support your language, please use the [English localization](English.strings) as a template: grab it, edit it, then rename it to match the language you're translating iCleaner into.

### Complete or fix an existing localization

**Incomplete localizations** are listed in the [Incomplete](Incomplete) directory. Each .strings file in that directory contains the currently untranslated strings for that specific language, which you can edit in-place. You can also **fix mistakes in existing localizations** by editing the main .strings files.

### Notes

* The preferred encoding for localization files is UTF16 little-endian with BOM.
* If you want, you can specify your name or nickname and/or your website (in either the pull request details or the body of the email), in order to be added to the [credits page](http://ib-soft.net/icleaner/credits.php).
* Localization files may contain [format strings](#appendix-format-strings-reference) that are interpreted and expanded at runtime by the iCleaner app. You can place them anywhere it makes sense in the string, as long as you respect the order they appear in.

### Test your changes (optional)

You can test your changes yourself directly within the app. In order to do so, place your .strings file in `/Applications/iCleaner.app` (eventually overwriting existing files) and the app will pick up your updated translation as soon as it is restarted. You can change the active localization in the settings tab of the app.

### Submit your changes

Finally, you can submit your changes in two ways:

* [Create a pull request](https://help.github.com/articles/creating-a-pull-request/) on this repository.
* Email me the edited .strings file(s) at [support@ib-soft.net](mailto:support@ib-soft.net).

## Appendix: Format strings reference

| String | Meaning |
|:------:|:-------:|
| *%@* | variable string |
| *%d, %u, %f* | variable number |
| *\n* | end of line |
