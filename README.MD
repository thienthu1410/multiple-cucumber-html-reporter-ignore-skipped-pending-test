Multiple Cucumber HTML Reporter - Ability to ignore the skipped and pending skipped
===============================

[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT)


This project is based on the project [https://www.npmjs.com/package/multiple-cucumber-html-reporter](https://www.npmjs.com/package/multiple-cucumber-html-reporter).
On this project, I add the ability to ignore the skipped and pending tests (feature,scenario) on html reporter


## Install
Install this module locally with the following command:

``` bash
npm install multiple-cucumber-html-reporter-ignore-skipped-pending-tested
```

Save to dependencies or dev-dependencies:

``` bash
npm install mmultiple-cucumber-html-reporter-ignore-skipped-pending-tested --save
npm install multiple-cucumber-html-reporter-ignore-skipped-pending-tested --save-dev
```

## Legacy multiple-cucumber-html-reporter
Refer [https://www.npmjs.com/package/multiple-cucumber-html-reporter] https://www.npmjs.com/package/multiple-cucumber-html-reporter

## New configuration to ignore the skipped and pending tests from generating html report
To ignore the skipped and pending tests from generating html report, add configuration report.generate: `ignoreSkipTest: true` in the file cucumber-html-reporter.js

```javascript
cconst report = require("multiple-cucumber-html-reporter");

report.generate({
//  configuration...
    ignoreSkipTest: true
})
```