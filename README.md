civicrm-l10n-extensions
=======================

Localisation files for CiviCRM extensions: http://civicrm.org/extensions

This repository helps keep track of the source .pot files (uploaded to
Transifex) and translated .po files (downloaded from Transifex). The
compiled .mo files are then uploaded to https://download.civicrm.org.

When installing extensions, the automatic web installer (from the CiviCRM
admin section "Manage Extensions") downloads the translations (.mo files
automatically. Admins managing their extensions manually (FTP, build scripts)
should also download from download.civicrm.org, using, for example:

https://download.civicrm.org/civicrm-l10n-extensions/mo/[shortname]/xx_XX/[shortname].mo

... where xx_XX is the locale (ex: fr_FR, es_ES) and the shortname is the same
name as the myextension.php, or equivalent to the "file" key in the info.xml
of the extension. For example: the short name for ca.bidon.i18nexample is
"i18nexample".


Extension translation
=====================

Translations are managed on Transifex:
https://www.transifex.com/projects/p/civicrm_extensions

If you wish to contribute to the translations of extensions, please create
an account on Transifex and join the language translation team. Please do
not do pull requests on this repository. If you wish to translate using an
external tool, you must use the Transifex command line client.

For more information on extension translation:
http://wiki.civicrm.org/confluence/display/CRMDOC/Extension+translation


Adding a new extension
======================

Each extension is a "resource" in Transifex. New extensions are
automatically added to Transifex by the civiextensions-update-transifex.php
script, which runs daily from a cron on biryani.


Forums, help, community
=======================

For questions, please post on the Internationalisation forum:
http://forum.civicrm.org/index.php/board,10.0.html

Or on the language-specific forums:
French: http://forum.civicrm.org/index.php/board,58.0.html
German: http://forum.civicrm.org/index.php/board,62.0.html
Spanish: http://forum.civicrm.org/index.php/board,69.0.html
UK: http://forum.civicrm.org/index.php/board,34.0.html
