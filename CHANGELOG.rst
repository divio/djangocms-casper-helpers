==== 4.0.0 (2017-09-03) ====

- Fixed things to work with CMS 4.0


==== 3.0.0 (2017-11-15) ====

- Changed `addPage` / `removePage` in backwards incompatible way due to page
  tree refactor on the cms


==== 2.0.0 (2017-09-21) ====

- deprecated casper-summoner
- fixed path resolution for casper binary
- added CMS 3.5 helpers


==== 1.4.0 (2017-06-13) ====

- Allowed sleep timeout to be passed as an option
- Increased default sleep timeout to 2 minutes


==== 1.3.0 (2016-08-24) ====

- Updated helpers to work with CMS 3.4
- Added ``waitUntilActionsDropdownLoaded`` method


==== 1.2.0 (2016-07-14) ====

- Server now looks for a free port before starting to avoid clashes
- Exposed current port via settings


==== 1.1.2 (2016-06-09) ====

- Changed ``createJSTreeXPathFromTree`` to start from the root of the tree.


==== 1.1.1 (2016-06-03) ====

- Use namespaced CMS jQuery


==== 1.1.0 (2016-05-25) ====

- Added "getXPathForAdminSection"


==== 1.0.4 (2016-05-24) ====

- Revert casperjs version to 1.1.0-beta5


==== 1.0.3 (2016-05-22) ====

- Reorganized file structure and moved to a separate repo
- Added linting


==== 1.0.2 (2016-05-22) ====

- Fixed a bug with multipl Phantomjs installations


==== 1.0.1 (2016-05-22) ====

- Added possibility to specify own paths to Casper and Phantom


==== 1.0.0 (2016-05-22) ====

- Initial release
