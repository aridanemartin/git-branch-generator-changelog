# Git Branch Generator: Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.3.0] - 2024-11-22 🚀

### Added

- `Git Branch` command added to creation commands.
- `FE, BE, QA...` added to layer/extra info.
- Integration with Asana.
- Settings Section.
- Automatic Scraping on load with Jira / Asana (Configurable in settings).

### Fixed

- Branch can be formed without task name if wanted.
- Jira buttons are replaced with Asana buttons in the title when using Asana.

## [1.3.1] - 2024-11-28 🚀

- Update Theme / marketing.
- Fix trailing dash errors.

## [1.3.2] - 2024-12-18 🚀

### Added

**Task Branch section**

- Task prefix checkbox removed
- Task prefix includes sections for Team role, Layers, and Environments to enhance UI/UX.
- Improve UI adding a separator, changing colors and updating position of reset data.

**Release Branch section**

- Drag & Drop approach to release branch creation.
- Branch conventions dialog now includes information about Git branching conventions.

**Config**

- Shortcut to changelog added.

### Fixed

- Tooltips added to improve UI/UX experience.
- Errors added in edge cases.

## [1.3.1] - 2024-11-28 🚀

- Update Theme / marketing.
- Fix trailing dash errors.

## [1.3.5] - 2024-12-29 🚀

### Added

**Workflow**

- Github action automatically updates changelog when there's new changes.

**Config**

- New color theme selector section with 4 new available themes.
  - Dark Moon
  - Frankenstein
  - Night City
  - Half Life

### Fixed

- Tooltip confusing messages removed.
- Add consistency to links hover colors.
- Random word refetch button keeps inherit width when loading on refetching
- Refactor tertiary buttons to improve consistency.
- Automatic scraping won't be triggered if there's no need.

### Technical Debt

- Playwright screen POC removed from code.
- Colors stored in theme variables using SASS.
- Remove toast temporarily until decide best approach.

## [1.3.6] - 2025-01-12 🚀

**Global**

- Add the possibility of import/export config (beta).
- Added the ability to reset all states to default in the extension.

## Style fixes

- Improve Branch Convention screen readability.
- Add warning icon to errors.
- Style Task Prefix Sections.
- Style tab underline separately.

## [1.3.7] - 2025

**Release Branch section**

- Renamed 'Refetch' button to 'Generate' for consistency with similar buttons.
- Branch parts no longer move to the end automatically to prevent confusion when enabling/disabling parts.
- Restructured UI to place branch parts sections closer to the resulting branch.
- Repositioned 'Reset Data' button for consistency across pages.

## Low priority known bugs

- When changing tab after copying command/branch toast must close.

## [1.3.8] - WIP 👷‍♂️

**Global**

- Allow import partial config.

## Style fixes

- Different color shadows depending on the themes.
- Style tooltips differently according to the theme.
- Style buttons in config / Differentiate danger zone from previous options

## Low priority known bugs

- When changing tab after copying command/branch toast must close.
- When error is displayed and you start writing again error remains there.
