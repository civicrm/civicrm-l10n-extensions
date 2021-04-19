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

For more information, see:  
lab.civicrm.org/dev/translation/-/wikis/Administrator-Guide


Extension translation
=====================

Translations are managed on Transifex:
https://www.transifex.com/projects/p/civicrm_extensions

If you wish to contribute to the translations of extensions, please create
an account on Transifex and join the language translation team. Please do
not do pull requests on this repository. If you wish to translate using an
external tool, you must use the Transifex command line client.

For more information on extension translation:
https://docs.civicrm.org/dev/en/latest/extensions/translation/

Adding a new extension
======================

Each extension is a "resource" in Transifex. New extensions are
automatically added to Transifex by the civiextensions-update-transifex.php
script, which runs daily from Jenkins.

Translations must be reviewed for "automatic distribution".

Forums, help, community
=======================

For questions, please post on the translation issue queue:  
https://lab.civicrm.org/dev/translation/-/issues

We also have a translation channel on Mattermost:  
https://chat.civicrm.org/civicrm/channels/translation
