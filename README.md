# [Now UI Dashboard PRO React](https://creativetimofficial.github.io/now-ui-dashboard-pro-react/#/dashboard)
[![version][version-badge]][CHANGELOG]

![alt text](https://s3.amazonaws.com/creativetim_bucket/products/73/opt_nudp_react_thumbnail.jpg)

**[Now UI Dashboard PRO React](https://creativetimofficial.github.io/now-ui-dashboard-pro-react/#/dashboard)** is a premium admin dashboard template designed to be beautiful and simple. It is built on top of [Reactstrap](https://reactstrap.github.io/), using [Now UI Dashboard PRO](https://www.creative-tim.com/product/now-ui-dashboard-pro) and it is fully responsive. It comes with a big collections of elements that will offer you multiple possibilities to create the app that best fits your needs. It can be used to create admin panels, project management systems, web applications backend, CMS or CRM.

The product represents a big suite of front-end developer tools that can help you jump start your project. We have created it thinking about things you actually need in a dashboard. Now UI Dashboard React contains multiple handpicked and optimized plugins. Everything is designed to fit with one another. As you will be able to see, the dashboard you can access on Creative Tim is a customization of this product.

It comes with 5 filter colors for the sidebar (`yellow`, `blue`,`green`,`orange`,`red`).

## Links:

+ [Live Preview](https://creativetimofficial.github.io/now-ui-dashboard-pro-react/#/dashboard)

## Quick Start:

Quick start options:

+ [Download from Creative Tim](https://www.creative-tim.com/product/now-ui-dashboard-pro-react).

Other Products:

+ [Download HTML PRO Version](https://www.creative-tim.com/product/now-ui-dashboard-pro).

## Local Development

1. Install NodeJs from [NodeJs Official Page](https://nodejs.org/en)
2. Open Terminal
3. Go to your file project
4. Run in terminal ```npm install```
5. Then run ```npm start```
6. (Optional) You can create a new react application like this
    1. Run in terminal ```npm install -g create-react-app```
    2. Go to the folder where you want to create your app
    3. Run in terminal ```create-react-app your-app-name```
    4. Navigate to your-app-name
    5. Run in terminal ```npm start```
    6. More information → create-react-app
7. Navigate to http://localhost:3000
8. More information → react

## Live Production on Heroku

1. Open terminal
2. Go to your file project
3. Run in terminal one by one: (Replace ```$APP_NAME``` with a name for your unique app.)
    1. ```git init```
    2. ```heroku create $APP_NAME --buildpack https://github.com/mars/create-react-app-buildpack.git```
    3. ```git add .```
    4. ```git commit -m "Start with create-react-app"```
    5. ```git push heroku master```
    6. ```heroku open```
4. More info → here


### What's included

Within the download you'll find the following directories and files:
```
now-ui-dashboad-pro-react
│
├── Documentation
│   └── tutorial-components.html
├── package.json
├── public
│   ├── index.html
│   └── manifest.json
└── src
    ├── index.js
    ├── assets
    │   ├── css
    │   ├── fonts
    │   ├── img
    │   │   ├── flags
    │   │   ├── img
    │   │   │   ├── examples
    │   │   │   ├── flags
    │   │   │   ├── nucleo-logo.svg
    │   │   │   └── presentation-page
    │   │   │       └── Pages
    │   │   └── nucleo-logo.svg
    │   └── scss
    │       ├── now-ui-dashboard
    │       │   ├── mixins
    │       │   └── plugins
    │       └── now-ui-dashboard.css
    ├── components
    │   ├── Accordion
    │   │   └── Accordion.jsx
    │   ├── CardElements
    │   │   ├── CardAuthor.jsx
    │   │   ├── CardCategory.jsx
    │   │   ├── CardDescription.jsx
    │   │   ├── CardIcon.jsx
    │   │   ├── CardSocial.jsx
    │   │   ├── CardSocials.jsx
    │   │   └── CardStats.jsx
    │   ├── CustomButton
    │   │   └── CustomButton.jsx
    │   ├── CustomCheckbox
    │   │   ├── IconCheckbox.jsx
    │   │   └── SimpleCheckbox.jsx
    │   ├── CustomProgress
    │   │   └── CustomProgress.jsx
    │   ├── CustomRadio
    │   │   └── CustomRadio.jsx
    │   ├── CustomUpload
    │   │   ├── ImageUpload.jsx
    │   │   └── PictureUpload.jsx
    │   ├── Footer
    │   │   └── Footer.jsx
    │   ├── FormInputs
    │   │   └── FormInputs.jsx
    │   ├── Header
    │   │   ├── Header.jsx
    │   │   └── PagesHeader.jsx
    │   ├── InfoArea
    │   │   └── InfoArea.jsx
    │   ├── Instructions
    │   │   └── Instructions.jsx
    │   ├── PanelHeader
    │   │   └── PanelHeader.jsx
    │   ├── Sidebar
    │   │   └── Sidebar.jsx
    │   ├── Statistics
    │   │   └── Statistics.jsx
    │   ├── Stats
    │   │   └── Stats.jsx
    │   ├── Tasks
    │   │   └── Tasks.jsx
    │   ├── Timeline
    │   │   └── Timeline.jsx
    │   └── index.js
    ├── layouts
    │   ├── Dashboard
    │   │   └── Dashboard.jsx
    │   └── Pages
    │       └── Pages.jsx
    ├── logo.svg
    ├── routes
    │   ├── dashboad.jsx
    │   ├── index.jsx
    │   └── pages.jsx
    ├── variables
    │   ├── charts.jsx
    │   ├── general.jsx
    │   └── icons.jsx
    └── views
        ├── Calendar
        │   └── Calendar.jsx
        ├── Charts
        │   └── Charts.jsx
        ├── Components
        │   ├── Buttons.jsx
        │   ├── GridSystem.jsx
        │   ├── Icons.jsx
        │   ├── Notifications.jsx
        │   ├── Panels.jsx
        │   ├── SweetAlertPage.jsx
        │   └── Typography.jsx
        ├── Dashboard
        │   └── Dashboard.jsx
        ├── Forms
        │   ├── ExtendedForms.jsx
        │   ├── RegularForms.jsx
        │   ├── ValidationForms.jsx
        │   └── Wizard
        │       ├── Step1.jsx
        │       ├── Step2.jsx
        │       ├── Step3.jsx
        │       └── Wizard.jsx
        ├── Maps
        │   ├── FullScreenMap.jsx
        │   ├── GoogleMaps.jsx
        │   └── VectorMap.jsx
        ├── Pages
        │   ├── LockScreenPage.jsx
        │   ├── LoginPage.jsx
        │   ├── PricingPage.jsx
        │   ├── RegisterPage.jsx
        │   ├── TimelinePage.jsx
        │   └── UserPage.jsx
        ├── Tables
        │   ├── DataTables.jsx
        │   ├── ExtendedTables.jsx
        │   └── RegularTables.jsx
        └── Widgets
            └── Widgets.jsx
```
## Useful Links

More products from Creative Tim: <https://www.creative-tim.com/bootstrap-themes>

Tutorials: <https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w>

Freebies: <https://www.creative-tim.com/products>

Affiliate Program (earn money): <https://www.creative-tim.com/affiliates/new>

Social Media:

Twitter: <https://twitter.com/CreativeTim>

Facebook: <https://www.facebook.com/CreativeTim>

Dribbble: <https://dribbble.com/creativetim>

Google+: <https://plus.google.com/+CreativetimPage>

Instagram: <https://instagram.com/creativetimofficial>

[CHANGELOG]: ./CHANGELOG.md

[LICENSE]: ./LICENSE.md
[version-badge]: https://img.shields.io/badge/version-1.1.1-blue.svg
