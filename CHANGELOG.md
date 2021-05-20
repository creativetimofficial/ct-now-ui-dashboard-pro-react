# Change Log

## [1.5.0] 2020-05-20
### Bug fixing
- https://github.com/creativetimofficial/ct-now-ui-dashboard-pro-react/issues/35 (This was not fixed unfortunately, please check the warnings down bellow)
- https://github.com/creativetimofficial/ct-now-ui-dashboard-pro-react/issues/34
### Major style changes
### Deleted components
### Added components
### Deleted dependencies
- `history` (no longer needed due to the `BrowserRouter`)
- `react-google-maps` (no longer maintained, so we'll use simple Google Maps API)
- `@types/googlemaps`
- `@types/markerclustererplus`
- `@types/react`
- `ajv` (was only installed to stop warnings)
- `npm-run-all` (no longer used)
### Added dependencies
- `@babel/core@7.14.3` (to stop warnings on install)
- `node-sass@6.0.0` (this should have been installed a long time ago)
### Updated dependencies
```
bootstrap                      4.5.0   →    4.6.0
chart.js                       2.9.3   →    3.2.1
classnames                     2.2.6   →    2.3.1
gulp-append-prepend            1.0.8   →    1.0.9
match-sorter                   4.1.0   →    6.3.0
moment                        2.26.0   →   2.29.1
nouislider                    14.5.0   →   15.1.1
perfect-scrollbar              1.5.0   →    1.5.1
react                        16.13.1   →   17.0.2
react-big-calendar            0.25.0   →   0.33.3
react-bootstrap-sweetalert    5.1.11   →    5.2.0
react-bootstrap-wizard         0.0.7   →    0.0.9
react-chartjs-2                2.9.0   →    3.0.3
react-datetime                2.16.3   →    3.0.4
react-dom                    16.13.1   →   17.0.2
react-notification-alert      0.0.12   →   0.0.13
react-scripts                  3.4.1   →    4.0.3
react-select                   3.1.0   →    4.3.1
react-table                    7.2.0   →    7.7.0
reactstrap                     8.4.1   →    8.9.0
typescript                     3.9.5   →    4.2.4
```
### Warning
_We will update Bootstrap to v5 when we'll release a new design for the Now UI products._
_While in development some of the plugins that were used for this product will throw some warnings - note, this only happens in development, the UI or the functionality of the product is not affected, also, if the issues will persist in React 17, we'll drop usage of those plugins, and replace them with other ones._
```
npm WARN react-datetime@3.0.4 requires a peer of react@^16.5.0 but none is installed. You must install peer dependencies yourself.
npm WARN react-tagsinput@3.19.0 requires a peer of react@^16.0.0 || ^15.0.0 || ^0.14.0 but none is installed. You must install peer dependencies yourself.
```
_You will also have the following message: found 80 vulnerabilities (1 low, 79 moderate). This comes from react-scripts, and will be fixed in the next version. NOTE: the product works as expected with these vulnerabilities._

## [1.4.0] 2019-06-15
### Bug fixing
- Run prettier on all files and there might be changes due to this
- Remove `perfect-scrollbar` from `Auth` layout
- Rename all files from `jsx` to `js`
- https://github.com/creativetimofficial/ct-now-ui-dashboard-pro-react/issues/31
- https://github.com/creativetimofficial/ct-now-ui-dashboard-pro-react/issues/27
- https://github.com/creativetimofficial/ct-now-ui-dashboard-pro-react/issues/17 - could not reproduce is, so it was closed
- https://github.com/creativetimofficial/ct-now-ui-dashboard-pro-react/issues/13
- https://github.com/creativetimofficial/ct-now-ui-dashboard-pro-react/issues/11 (this was already solved by one of the previous releases)
- https://github.com/creativetimofficial/ct-now-ui-dashboard-pro-react/issues/10 (this was already solved by one of the previous releases)
- Other Now UI React products Github issues:
  - https://github.com/creativetimofficial/ct-now-ui-kit-pro-react/issues/2 (added warnings on the documentation about this issue - unfortunately, we need to keep our own homepage prop inside the package.json for copyright issues)
  - https://github.com/creativetimofficial/now-ui-dashboard-react/issues/10
### Major style changes
- `src/assets/scss/now-ui-dashboard/_variables.scss` (changed the fonts import to `~assets/fonts` and also added assets path inside `jsconfig.json` file)
- `src/assets/scss/now-ui-dashboard/_nucleo-outline.scss` (changed the fonts import to `~assets/fonts` and also added assets path inside `jsconfig.json` file)
- `src/assets/scss/now-ui-dashboard/plugins/_plugin-nouislider.scss` (due to new `noUiSlider` API)
- `src/assets/scss/now-ui-dashboard/react/plugins/_plugin-react-table.scss` (due to new `React-Table` API)
- `src/assets/scss/now-ui-dashboard/react/plugins/_plugin-react-bootstrap-wizard.scss` (solves #27)
- `src/assets/scss/now-ui-dashboard/react/plugins/_plugin-react-bootstrap-sweetalert.scss` (due to new `react-bootstrap-sweetalert` API)
### Deleted components
### Added components
- `src/components/ReactTable/ReactTable.js` (because of the new React-Table API - NOTE: this is just a demo component to showcase the usage of the API, if you wish to add more functionality from the API, you should either duplicate the component, or work over it.)
### Deleted dependencies
+ node-sass-chokidar@1.3.5
### Added dependencies
+ match-sorter@4.1.0 (because of the new React-Table API)
+ gulp-append-prepend@1.0.8 (for Creative Tim copyrights)
+ gulp@4.0.2 (for Creative Tim copyrights)
### Updated dependencies
```
bootstrap                      4.3.1   →     4.5.0
chart.js                       2.8.0   →     2.9.3
moment                        2.24.0   →    2.26.0
nouislider                    13.1.5   →    14.5.0
perfect-scrollbar              1.4.0   →     1.5.0
react                         16.8.6   →   16.13.1
@types/react                 16.8.19   →   16.9.36
react-big-calendar            0.21.0   →    0.25.0
react-bootstrap-sweetalert     4.4.1   →    5.1.11
react-chartjs-2                2.7.6   →     2.9.0
react-dom                     16.8.6   →   16.13.1
react-jvectormap              0.0.12   →    0.0.16
react-router-dom               5.0.0   →     5.2.0
react-scripts                  3.0.1   →     3.4.1
react-select                   3.0.4   →     3.1.0
react-table                   6.10.0   →     7.2.0
reactstrap                     8.0.0   →     8.4.1
@types/googlemaps             3.36.2   →    3.39.6
ajv                           6.10.0   →    6.12.2
typescript                     3.5.1   →     3.9.5
```
### Warning
_All the following products: Now UI Kit React, Now UI Dashboard React, Now UI Kit PRO React and Now UI Dashboard PRO React have been updated together, and thus, we've added to all of them the same version of 1.4.0 - we may have skipped some versions for some of the above products, we've done so, since we want all Now UI & React products to share the same versions._
_While in development some of the plugins that were used for this product will throw some warnings - note, this only happens in development, the UI or the functionality of the product is not affected, also, if the issues will persist in React 17, we'll drop usage of those plugins, and replace them with other ones._
_Warnings might appear while doing an npm install - they do not affect the UI or the functionality of the product, and they appear because of NodeJS and not from the product itself._

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
