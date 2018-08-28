# Change Log

## [1.2.0] 2018-08-28
### Bug fixing
- Added new script command for clean install of node_modules (just run in terminal `npm run install:clean`, this will also start your server)
- Added lint commands
- Run prettier in our code to make it a bit more readable
- Github issues
  - `https://github.com/creativetimofficial/ct-now-ui-dashboard-pro-react/issues/1`
  - `https://github.com/creativetimofficial/ct-now-ui-dashboard-pro-react/issues/2`
  - `https://github.com/creativetimofficial/ct-now-ui-dashboard-pro-react/issues/7`
  - `https://github.com/creativetimofficial/ct-now-ui-dashboard-pro-react/issues/8`
  - `https://github.com/creativetimofficial/ct-now-ui-dashboard-pro-react/issues/10`
  - `https://github.com/creativetimofficial/ct-now-ui-dashboard-pro-react/issues/14`
  - `https://github.com/creativetimofficial/ct-now-ui-dashboard-pro-react/issues/15`
### Deleted dependencies
- `react-nouislider v2.0.1` - it was deprected
### Added dependencies
- `nouislider v11.1.0` - to replace the `react-nouislider`
- Added the following dependencies to stop warnings on `npm install`
  - `@types/googlemaps v3.30.11`
  - `@types/markerclustererplus v2.1.33`
  - `@types/react v16.4.11`
  - `ajv v5.0.0`
### Updated dependencies
- `bootstrap v4.0.0-beta` to `bootstrap v4.1.3`
- `chart.js v2.7.1` to `chart.js v2.7.2`
- `moment v2.19.2` to `moment v2.22.2`
- `node-sass-chokidar v1.2.2` to `node-sass-chokidar v1.3.3`
- `npm-run-all v4.1.2` to `npm-run-all v4.1.3`
- `perfect-scrollbar v1.3.0` to `perfect-scrollbar v1.4.0`
- `react v16.2.0` to `react v16.4.2`
- `react-big-calendar v0.17.0` to `react-big-calendar v0.19.2`
- `react-bootstrap-sweetalert v4.1.0` to `react-bootstrap-sweetalert v4.4.1`
- `react-bootstrap-wizard v0.0.4` to `react-bootstrap-wizard v0.0.5`
- `react-chartjs-2 v2.7.0` to `react-chartjs-2 v2.7.4`
- `react-datetime v2.11.0` to `react-datetime v2.15.0`
- `react-dom v16.2.0` to `react-dom v16.4.2`
- `react-google-maps v9.2.2` to `react-google-maps v9.4.5`
- `react-jvectormap v0.0.2` to `react-jvectormap v0.0.3`
- `react-notification-alert v0.0.7` to `react-notification-alert v0.0.8`
- `react-router-dom v4.2.2` to `react-router-dom v4.3.1`
- `react-scripts v1.0.17` to `react-scripts v1.1.4`
- `react-select v1.0.0-rc.10` to `react-select v2.0.0`
- `react-table v6.8.0` to `react-table v6.8.6`
- `reactstrap v5.0.0-alpha.4` to `reactstrap v6.4.0`

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
