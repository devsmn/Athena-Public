---
layout: page
title: Changelog
subtitle: Information about new features, improvements and fixes
---

## Latest release: v2.0.2 (2025-10-04)
Refer to the [latest release notes](https://devsmn.github.io/Athena-Public/app_latest_release/) page for more details.

___

## v2.0.1 - (2025-09-19) 

### Changed
- In the tag overview, an "empty tag view" is displayed if no tags are available ([#19](https://github.com/devsmn/Athena/issues/19))

### Fixed
- There was an issue where a valid password was treated as incorrect after entering an invalid password before ([#120](https://github.com/devsmn/Athena/issues/120))
- An error messages is displayed when trying to save an empty tag name ([#61](https://github.com/devsmn/Athena/issues/61))

___

## v2.0.0 - (2025-05-28) 
### Added
- Data is now encrypted via biometrics or password for more security ([#4](https://github.com/devsmn/Athena/issues/4))
- A new advanced document scanner can be used ([#90](https://github.com/devsmn/Athena/issues/90))
- Backups can be created and restored ([#76](https://github.com/devsmn/Athena/issues/76))
- Release notes are displayed when using a new version for the first time ([#106](https://github.com/devsmn/Athena/issues/106))

### Changed
- Links were changed to devsmn.de ([#96](https://github.com/devsmn/Athena/issues/96))

### Fixed
- In some cases, tags were not saved correctly ([#118](https://github.com/devsmn/Athena/issues/118))

___

## v1.2.0 - (2025-05-28) 
### Added
- Over **144** text detection languages can now be downloaded on demand ([#60](https://github.com/devsmn/Athena/issues/60))
- The overall design of the app was improved ([#69](https://github.com/devsmn/Athena/issues/69))
- A notification is shown if the ToS were changed ([#58](https://github.com/devsmn/Athena/issues/58))
- PDfs are now compressed before saving to reduce the storage usage ([#45](https://github.com/devsmn/Athena/issues/45))
- Long-running actions are now more transparent by displaying their progress in a popup ([#62](https://github.com/devsmn/Athena/issues/62))
- Certain pages now contain an info icon for addtional information

### Changed
- The orientation is fixed to portrait ([#65](https://github.com/devsmn/Athena/issues/65))
- The compression of images was improved ([#72](https://github.com/devsmn/Athena/issues/72))

### Fixed
- In some cases, tags were not saved correctly ([#68](https://github.com/devsmn/Athena/issues/68))

___

## v1.1.4 - (2025-04-18)
### Changed
- Housekeeping: Update dependencies ([#47](https://github.com/devsmn/Athena/issues/47))
- Tag overview: Hide delete button when adding a new tag ([#46](https://github.com/devsmn/Athena/issues/46))

___


## v1.1.3 - (2024-07-26)
### Changed
- The 'Detect text in documents' option is enabled by default when adding a new document ([#41](https://github.com/devsmn/Athena/issues/41))

### Fixed
- Deleted documents were still visible in some cases ([#42](https://github.com/devsmn/Athena/issues/42))

___

## v1.1.2 - (2024-07-19) 
### Added
- Added support for Android 10 (SDK 29) ([#35](https://github.com/devsmn/Athena/issues/35))

___

## v1.1.1 - (2024-07-18) 
### Changed
- Updated thid-party dependencies to fix issues with certain android versions ([#34](https://github.com/devsmn/Athena/issues/34))
- The help button in the settings view now points to the help page ([#33](https://github.com/devsmn/Athena/issues/33))

### Fixed
- An issue when deleting nested folders was fixed ([#31](https://github.com/devsmn/Athena/issues/31))

___

## v1.1.0 - (2024-07-17) 
### Added
- Added option to submit feedback (bugs, new features or general feedback) in the settings view  ([#30](https://github.com/devsmn/Athena/issues/30))
- Document tags are displayed in all overviews ([#9](https://github.com/devsmn/Athena/issues/9))
- When adding a document, a summary of the process is displayed at the end ([#10](https://github.com/devsmn/Athena/issues/10))
- A home page with the most recent documents and other information was added ([#12](https://github.com/devsmn/Athena/issues/12))
- The language and name can be set on the first usage ([#13](https://github.com/devsmn/Athena/issues/13))
- Tags can be customized with a background color and a text color ([#22](https://github.com/devsmn/Athena/issues/22))

### Fixed
- The app closed unexpectedly when pinning folders ([#15](https://github.com/devsmn/Athena/issues/15))
- Folders with an empty name cannot be saved anymore ([#26](https://github.com/devsmn/Athena/issues/26))

### Changed
- Android target version was updated to Android 14 (API 34) ([#29](https://github.com/devsmn/Athena/issues/29))
- Pages were removed. Instead, folders can be nested indefinitely for more flexibility. Documents can be added directly to folders ([#6](https://github.com/devsmn/Athena/issues/6))
- "Empty" views were improved to display more detailed information ([#17](https://github.com/devsmn/Athena/issues/17))
- The banner ad when saving a document was removed ([#18](https://github.com/devsmn/Athena/issues/18))
- When using the back button while creating a document, the page changes to the previous step instead of closing ([#24](https://github.com/devsmn/Athena/issues/24))

___

## v1.0.5 - (2024-06-17) 
### Fixed
- Fixed rare issue where it wasn't possible to add tags

### Changed
- Activated ads

___

## v1.0.4 - (2024-06-12)
### Fixed
- Fixed scaling issues on some devices after dependency updates

___

## v1.0.3 - (2024-06-06)
### Added
- Documents can be moved to a different page

___

## v1.0.2 - (2024-05-28)
### Changed
- Full-text search performance improved
- Dependencies updated

___

## v1.0.1 - (2024-05-12)
Various issues fixed

___

## v1.0.0 - (2024-05-01)
Initial release of Athena: AI Document Manager
