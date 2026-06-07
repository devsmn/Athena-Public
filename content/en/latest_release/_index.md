---
title: Latest release
menu: { main: { weight: 40 } }
# Add blocks of content here to add more sections to the community page
---


{{% blocks/section color=white" %}}
https://athena.devsmn.de/blog/2026/06/07/2026-06-07-release-v210/
Take a look at our [blog post](https://athena.devsmn.de/blog/2026/06/07/2026-06-07-release-v210/) for a detailed description of the release.

## v2.1.0 - (2026-06-17) 

### Added
- The document scanner import limit was removed ([#155](https://github.com/devsmn/Athena/issues/155))

### Fixed
- Authentication: The authentication no longer worked when closing the app while changing the password/biometrics ([#148](https://github.com/devsmn/Athena/issues/148))
- Documents: The available folders in the 'Move document' popup were empty ([#152](https://github.com/devsmn/Athena/issues/152))
- OCR: The app could crash if the network was interrupted while downloading OCR languages ([#147](https://github.com/devsmn/Athena/issues/147))

### Changed
- The localization is now resolved dynamically. The app does not have to be restarted after changing the language. ([#157](https://github.com/devsmn/Athena/issues/157))
- Folders are now longer cached ([#159](https://github.com/devsmn/Athena/issues/159))
- The process of creating and restoring a backup was simplified ([#162](https://github.com/devsmn/Athena/issues/162))
- The subtitle "AI Document Manager" was changed to "Document Manager" ([#165](https://github.com/devsmn/Athena/issues/165))
- The following dependencies were updated:
  - Nuke.Common to v10.0.0
  - Microsoft.Extensions.Logging to v9.0.15
  - Syncfusion to v33.2.5

{{% /blocks/section %}}
