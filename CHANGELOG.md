# Change Log

## [1.1.1] 2018-05-22
### Bug fixing
- Changed links for the live preview and changed links from `http` to `https`

## [1.1.0] 2018-04-13
### Bug fixing
- Small changes in scss so latest version of `node-sass` and `node-sass-chokidar` can be used
### Deleted dependencies
- `node-sass@4.6.1`
- `d3-scale@1.0.7`
- `datatables.net@1.10.16`
- `datatables.net-bs@1.10.16`
- `datatables.net-responsive@2.2.1`
- `jquery@3.2.1`
- `react-simple-maps@0.10.1`
### Added dependencies
- `react-jvectormap@0.0.2` (instead of `react-simple-maps@0.10.1` and `d3-scale@1.0.7`)
- `react-table@6.8.0` (instead of `datatables.net@1.10.16`, `datatables.net-bs@1.10.16`, `datatables.net-responsive@2.2.1` and `jquery@3.2.1` - but kept scss for `datatables`)
### Updated dependencies
- `node-sass-chokidar@0.0.3` to `node-sass-chokidar@1.2.2`
- `npm-run-all@4.1.1` to `npm-run-all@4.1.2`
- `react@16.1.0` to `react@16.2.0`
- `react-dom@16.1.0` to `react-dom@16.2.0`

## [1.0.1] 2018-03-28
### Bug fixing
- Deleted `overflow-x: hidden;` on `.card-chart`
- Changed live preview and live documentation links
- Added `node-sass@4.6.1` as dependencie so that scss compiles without errors
- Changed version of `react-bootstrap-switch@15.5.2` to `react-bootstrap-switch@15.5.3` for `react^16` better support
- Moved notifications of activate/deactivate sidebar mini outside the `sidebar`
- Changed `z-index: 9999` to `z-index: 1030` on `Sidebar`
- Added `top: 1px; position: relative;` on `.Select-value-icon`

## [1.0.0] 2018-02-13
### Original Release
- Added Reactstrap as base framework
- Added design from Now UI Dashboard Pro by Creative Tim
