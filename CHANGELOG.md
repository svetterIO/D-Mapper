# D-MAPPER Changelog

D-MAPPER follows **Semantic Versioning** (`MAJOR.MINOR.PATCH`).

- **MAJOR**: incompatible/breaking behavior or stored-data changes that cannot be migrated.
- **MINOR**: backward-compatible features or significant user-facing enhancements.
- **PATCH**: backward-compatible fixes and maintenance changes.

## 1.3.0
- Renamed the application from **X-Mapper** to **D-MAPPER**.
- Set the product subtitle to **Bidirectional Data Mapping**.
- Prepared the standalone HTML for GitHub Pages (`index.html`) with application/description/theme metadata.
- Changed newly exported JSON filenames and format identifiers to the `d-mapper-*` namespace.
- Added migration support for prior X-Mapper browser storage keys.
- Fixed match statistics so each match is counted once.
- Added the MIT License for the GitHub release.

## 1.2.0
- Added collapsible **Rules & Controls**.
- Collapse state is persisted locally.
- INPUT and OUTPUT remain side by side.
- Added explicit application version metadata and separated app versioning from persisted-data/file-format schema versions.

## 1.1.0
- Added global enable/disable for all rules.
- Added independently managed **Default Rules**.
- Added multiple selectable rule sets, with one selected at a time.
- Added create/delete/rename operations for rule sets.
- Added independent Default Rules upload/download.
- Added Selected Rule Set upload/download.
- Reduced header height.

## 1.0.0
- Initial release under the original **X-Mapper** name.
- Single mapping list with enable, regex, case-sensitive matching, reorder, import/export, and Real ↔ Sanitized conversion.
