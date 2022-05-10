# Python Docs - Dark Theme: Changelog


## 2.4.0 - dev
### Added
- Code highlighting
  - New elements with adjusted color: `.highlight` [`.sa`, `.kc`, `.si`]
- Input fields border color added to stylesheet

### Changed
- Code highlighting
  - `.highlight` [`.nd`, `.m`] colors adjusted
  - Adjusted colors for python interpreter input/output simulation


## 2.3.0 - 2022.05.04
### Added
- New [Adaptive theme](./python_docs_dark_adaptive.user.css) variant. Activation depends on selected web browser color scheme.


## 2.2.1 - 2022.04.13
### Fixed
- Text color for `div.body` element
- Code highlighting is now more readable
  - Less contrast fg color for elements: `.nn`, `.nc`, `.vm`, `.nd`, `.gp`, `.gr`, `.gt`, `.go`, `.n`
  - Swapped colors for python interpreter input/output simulation

### Changed
- Modified description text in main `.user.css`


## **2.2.0** - 2022.02.27
### Added
- Support for new elements of python documentation pages
- Support for mobile version elements


## **2.1.1** - 2020.11.16
### Fixed
- Colors highlighting for some code elements
- Border color for `div.note`


## **2.1.0** - 2020.11.11
### Added
- Support for highlighting the searched elements
- Element class `span.copybutton` now included in style

### Changed
- Border rounding of `span.pre` class elements


## **2.0.0** - 2020.11.11
### Added
- Support for domain `packaging.python.org`
- Support for syntax highlighting compatibility with dark colors *(WIP)*
- Search and input fields adjustments now included in style
- Sidebar button added to style

### Fixed
- `css` syntax errors
- Background color for:
  - `.note tt`
  - `div.topic`

### Changed
- Refactored the `css` stylesheet
- Remade the README file
- Borders color for table elements
- Adjusted colors for variables:
  - `--background-gray`
  - `--text-code-general`


## **1.0.1** - 2020.11.11
### Fixed
- Background color for `tt.*` elements now gray. White artifacts removed.

## **1.0.0** - 2020.10.22
- First release of this `usercss` theme
