# Change Log

## [1.3.0] 2019-06-07
### Bug fixing
- Rewrote our buggy routing system (no more `src/routes/*` - three files, now there is only one file src/routes.js)
- Renamed `src/layouts/Dashboard/Dashboard.jsx` to `src/layouts/Admin.jsx`
- Renamed `src/layouts/Pages/Pages.jsx` to `src/layouts/Auth.jsx`
- Renamed `src/components/Header/Header.jsx` to `src/components/Navbars/AdminNavbar.jsx`
- Renamed `src/components/Header/PagesHeader.jsx` to `src/components/Navbars/AuthNavbar.jsx`
### Added components
- `jsconfig.json`
- `classnames@2.2.6`
- `src/components/FixedPlugin/FixedPlugin.jsx`
### Removed components
- `.env`
- `.eslintignore`
- `.eslintrc.js`
- `src/components/index.js`
- `src/components/Accordion/Accordion.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/CardElements/CardAuthor.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/CardElements/CardCategory.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/CardElements/CardDescription.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/CardElements/CardIcon.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/CardElements/CardSocial.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/CardElements/CardSocials.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/CardElements/CardStats.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/CustomButton/CustomButton.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/CustomCheckbox/IconCheckbox.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/CustomCheckbox/SimpleCheckbox.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/CustomProgress/CustomProgress.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/CustomRadio/CustomRadio.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/FormInputs/FormInputs.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/InfoArea/InfoArea.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/Instructions/Instructions.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/Statistics/Statistics.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/Stats/Stats.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/Tasks/Tasks.jsx` (replaced with simple HTML/React/Reactstrap syntax)
- `src/components/Timeline/Timeline.jsx` (replaced with simple HTML/React/Reactstrap syntax)
### Removed dependencies
- "babel-eslint": "^7.2.3",
- "eslint": "^4.19.1",
- "eslint-config-prettier": "^2.9.0",
- "eslint-plugin-prettier": "^2.6.2",
- "eslint-plugin-react": "^7.10.0",
- "prettier": "^1.13.7"
### Added dependencies
### Updated dependencies
```
bootstrap                    4.1.3   →     4.3.1
chart.js                     2.7.2   →     2.8.0
moment                      2.22.2   →    2.24.0
node-sass-chokidar           1.3.3   →     1.3.5
nouislider                  11.1.0   →    13.1.5
npm-run-all                  4.1.3   →     4.1.5
react                       16.4.2   →    16.8.6
react-big-calendar          0.19.2   →    0.21.0
react-bootstrap-wizard       0.0.5   →     0.0.7
react-chartjs-2              2.7.4   →     2.7.6
react-datetime              2.15.0   →    2.16.3
react-dom                   16.4.2   →    16.8.6
react-jvectormap             0.0.3   →    0.0.12
react-notification-alert     0.0.8   →    0.0.12
react-router-dom             4.3.1   →     5.0.0
react-scripts                1.1.4   →     3.0.1
react-select                 2.0.0   →     3.0.4
react-table                  6.8.6   →    6.10.0
reactstrap                   6.4.0   →     8.0.0
@types/googlemaps          3.30.11   →    3.36.2
@types/react               16.4.11   →   16.8.19
ajv                          5.0.0   →    6.10.0
```

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
