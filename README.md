# iCleaner localizations

This repository contains the current [iCleaner](http://ib-soft.net/icleaner) localization files.

## Instructions

### New localizations

If iCleaner does not support your language, please download the [English localization](English.strings), edit it, and rename it to match the language you're translating iCleaner into. You can then either email me the translated file at [support@ib-soft.net](mailto:support@ib-soft.net), or submit a pull request to this repository.

### Existing localizations

Incomplete localizations are listed in the ["Incomplete" directory](Incomplete/). Each .strings file in that directory contains the currently untranslated strings for that specific language. You can simply download the .strings file, edit it in your favorite text editor, and either:

* Merge it yourself into the main .strings file for that language (make sure to remove the "incomplete" file in that case), then submit a pull request.
* Email me the edited file at [support@ib-soft.net](mailto:support@ib-soft.net).

### Additional notes

* The preferred encoding for localization files is UTF16 little-endian with BOM.
* If you want, you can specify your name or nickname and/or your website (in either the pull request details or the body of the email), in order to be added to the [credits page](http://ib-soft.net/icleaner/credits.php).

### Strings symbol reference

Localization files may contain some symbols that are interpreted and expanded at runtime by the iCleaner app. You can place them anywhere it makes sense in the string, as long as you respect the order they appear in.

| Symbol | Meaning |
|:------:|:-------:|
| *%@* | variable string |
| *%d, %u, %f* | variable number |
| *\n* | end of line |
