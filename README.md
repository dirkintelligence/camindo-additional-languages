# Installing Additional Languages

In an existing camindo CMS installation, you can add backend languages later on. These are provided as ***translation packages*** in the form of `.ini` files.

The language code is located at the beginning of the filename: `{code}_core.ini`, `{code}_pdf.ini`…
plus `en_US_{code}.ini`. These files are stored in `var/translation/translated/`
(the `var` directory of the CMS).

A package becomes effective after rebuilding the snippet cache (under the "Tools" module, "Developer" tab, or via the command line with `php Core/cron/camindo.php refresh snippets`).

## The following languages are always available in the CMS:

| Code | Langauge |
| --- | --- |
| ar_SA | ‫العربية‬ |
| bn_BD | বাংলা |
| zh_CN | 简体中文 |
| de_DE | Deutsch |
| en_US | English |
| es_ES | Español |
| fr_FR | Français |
| hi_IN | हिन्दी |
| ja_JP | 日本語 |
| ko_KR | 한국어 |
| pt_BR | Português |
| ur_PK | ‫اردو‬ |

## The following languages are located here and can be installed subsequently:

| Code | Langauge |
| --- | --- |
| el_GR | Ελληνικά |
| it_IT | Italiano |
| nl_NL | Nederlands |
| pl_PL | Polski |
| sv_SE | Svensk |

