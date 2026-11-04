# Upgrade changelog — mass_edit_server actions (server_action_mass_edit)

Path: Odoo 16.0 → 20.0 (hops 16→17, 17→18, 18→19, 19→20)

Made by Upforge from the run ledger and the fix records; every run stays listed. An undone run is marked *reverted*.

## Run run_2026-11-04T08:51:42 — apply — 96 files

- —: 90 add
- 19→20: 2 add
- 17→18: 2 add
- 16→17: 2 add

| Hop | File | Rule | Change | Origin |
| --- | --- | --- | --- | --- |
| — | server_action_mass_edit/README.rst:1 | source-change | added | auto |
| — | server_action_mass_edit/__init__.py:1 | source-change | added | auto |
| 19→20 | server_action_mass_edit/__manifest__.py:1 | odoo:19.4-00-ir-access | added | auto |
| — | server_action_mass_edit/demo/mass_editing.xml:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/am.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/ar.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/bg.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/bs.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/ca.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/cs.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/da.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/de.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/el_GR.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/en_GB.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/es.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/es_AR.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/es_CL.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/es_CO.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/es_CR.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/es_DO.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/es_EC.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/es_ES.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/es_MX.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/es_PE.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/es_PY.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/es_VE.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/et.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/eu.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/fa.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/fi.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/fr.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/fr_CA.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/fr_CH.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/fr_FR.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/gl.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/gl_ES.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/he.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/hr.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/hr_HR.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/hu.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/id.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/it.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/ja.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/ko.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/lt.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/lt_LT.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/lv.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/mk.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/mn.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/nb.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/nb_NO.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/nl.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/nl_BE.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/nl_NL.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/pl.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/pt.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/pt_BR.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/pt_PT.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/ro.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/ru.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/server_action_mass_edit.pot:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/sk.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/sl.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/sr.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/sr@latin.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/sv.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/th.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/tr.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/tr_TR.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/uk.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/vi.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/vi_VN.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/zh_CN.po:1 | source-change | added | auto |
| — | server_action_mass_edit/i18n/zh_TW.po:1 | source-change | added | auto |
| — | server_action_mass_edit/migrations/20.0.2.0.0/pre-migration.py:1 | source-change | added | auto |
| — | server_action_mass_edit/models/__init__.py:1 | source-change | added | auto |
| — | server_action_mass_edit/models/ir_actions_server.py:1 | source-change | added | auto |
| — | server_action_mass_edit/models/ir_actions_server_mass_edit_line.py:1 | source-change | added | auto |
| — | server_action_mass_edit/readme/CONFIGURE.rst:1 | source-change | added | auto |
| — | server_action_mass_edit/readme/CONTRIBUTORS.rst:1 | source-change | added | auto |
| — | server_action_mass_edit/readme/DESCRIPTION.rst:1 | source-change | added | auto |
| — | server_action_mass_edit/readme/ROADMAP.rst:1 | source-change | added | auto |
| — | server_action_mass_edit/readme/USAGE.rst:1 | source-change | added | auto |
| 19→20 | server_action_mass_edit/security/ir.access.csv:1 | odoo:19.4-00-ir-access | added | auto |
| — | server_action_mass_edit/static/description/icon.png:1 | source-change | added | auto |
| — | server_action_mass_edit/static/description/index.html:1 | source-change | added | auto |
| — | server_action_mass_edit/static/description/mass_editing-item_tree-res… | source-change | added | auto |
| — | server_action_mass_edit/static/description/mass_editing-item_tree.png… | source-change | added | auto |
| — | server_action_mass_edit/static/description/mass_editing-wizard_form.p… | source-change | added | auto |
| — | server_action_mass_edit/static/description/mass_editing_form.png:1 | source-change | added | auto |
| — | server_action_mass_edit/tests/__init__.py:1 | source-change | added | auto |
| 17→18 | server_action_mass_edit/tests/test_mass_editing.py:1 | odoo:17.5-01-tree-to-list | added | auto |
| 16→17 | server_action_mass_edit/views/ir_actions_server.xml:1 | attrs-to-expressions | added | auto |
| — | server_action_mass_edit/wizard/__init__.py:1 | source-change | added | auto |
| 17→18 | server_action_mass_edit/wizard/mass_editing_wizard.py:1 | odoo:17.5-01-tree-to-list | added | auto |
| 16→17 | server_action_mass_edit/wizard/mass_editing_wizard.xml:1 | attrs-to-expressions | added | auto |

## Verify — 20.0 — 0 error(s), 0 warning(s), 0 blocking (run_2026-11-04T10:59:20)
