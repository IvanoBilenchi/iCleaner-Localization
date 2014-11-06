# iCleaner localizations

This repository contains the current [iCleaner](http://exile90software.com/icleaner) localization files.

Keep reading for detailed instructions on how to contribute.

## Status

### Received localizations:

* none

### Incomplete localizations:

* Azerbaijani
* Bulgarian
* Czech
* Finnish
* Hungarian
* Japanese
* Kurdish
* Norwegian
* Persian
* Serbian
* Slovak
* Slovenian
* Ukrainian

## Instructions

If iCleaner does not support your language, please download the [English localization](English.strings), edit it, and rename it to match the language you're translating iCleaner into.

If a translation is incomplete or you want to correct a translation mistake, please download the relative .strings file and make your additions/corrections. You can check which strings are missing by comparing the incomplete localization to the [English localization](English.strings).

Once you finished editing a localization, you can either submit a pull request to this repository, or email me at [exile@live.it](mailto:exile@live.it).

If you want, you can specify your name or nickname and/or your website (in either the pull request details or the body of the email), in order to be added to the [credits page](http://exile90software.com/icleaner/credits.php).

Your help is greatly appreciated.

### Strings symbol reference

Localization files may contain some symbols that are interpreted and expanded at runtime by the iCleaner app. You can place them anywhere it makes sense in the string, as long as you respect the order they appear in.

| Symbol | Meaning |
|:------:|:-------:|
| *%@* | variable string |
| *%d, %u, %f* | variable number |
| *\n* | end of line |
