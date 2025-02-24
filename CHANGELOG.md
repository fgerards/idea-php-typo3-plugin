# Changelog

## [Unreleased]
### Added

### Changed

### Deprecated

### Removed
- Removed travis build indicator
### Fixed

### Security
## [0.7.3]
### Added
- Upgrade to platform 213
### Changed
- migrate checkHighlight to testHighlight where possible
- migrate away from using FileTypeIndex.NAME directly
- register inspections individually and remove InspectionTool
- migrate `CreateInjectorQuickFix` away from removed API to use writeCommandAction
- migrate `ExtbaseControllerActionAction` away from removed API to use writeCommandAction
- migrate `createNotification` usage to distinct NotificationGroup
- Remove unused, deprecated API usage related to icons
- Use diamond operator where applicable
### Deprecated

### Removed

### Fixed

### Security
## [0.7.2]
### Added

### Changed
- change main target for changelog patching to master
- use nightly channel when publishing Fluid or TypoScript plugins
- upgrade gradle-intellij plugin to 1.1.6

### Deprecated

### Removed
- only support 2021.2.2
- remove MissingTableInspectionTest as it's not compatible

### Fixed

### Security
## [0.7.1]
### Added

### Changed
- Improve publishing through GitHub actions
- Grab version number from changelog correctly
- Use "nightly" channel for TypoScript and Fluid projects
- Fix syntax of release task

### Deprecated

### Removed

### Fixed

### Security
## [0.7.0]
### Added
- Use GitHub actions to build plugin instead of travis
- c2b9eca [T3CMS] allowed TCA field can contain CSV string of tables (#351) (Cedric Ziel)
- f7e3bb4 [T3CMS] Create convenience method to get locale (#350) (Cedric Ziel)
- d3499ef [All] Update Platform version to 2021.1 (#349) (Cedric Ziel)
- 95a22b1 Update issue templates (Cedric Ziel)
- 8b4849f [T3CMS] Rename settings property for translation folding (#344) (Cedric Ziel)
- 66d717b Prepare v0.6.1 (Cedric Ziel)

### Changed

### Deprecated

### Removed

### Fixed

### Security
