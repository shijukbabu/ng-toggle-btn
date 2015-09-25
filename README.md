# ng-toggle-btn

AngularJS Directive for switch toggle button with styles. 
**Version 0.1.0**
Tested with AngularJS 1.4.2 and 1.4.6

[ng-toggle-btn Page](http://shijukbabu.github.io/ng-toggle-btn/)

[Demo Here](http://plnkr.co/edit/oUxD3vgUsnM2Hrgd2cA4?p=preview)

## Bower Install 
`bower install ng-toggle-btn`
## Usage
Add dependency to app.
`angular.module('moduleName', ['ng-toggle.btn']);`
**HTML**

`<input ng-model="modelName" name="{{name}}" type="checkbox"`
	`toggle-btn `
        `on-type="{{on-color}}" off-type={{off color}}`
        `on-label="{{right side label}}" off-label="{{left side lable}}"`
        `is-disabled="boolean true or false"`
        `ng-change="doSomething()"`
`>`

`on-type, off-type` = Color types, supported values are - `default, primary, info, success, warning, danger, inverse`. Default `on-type` is `primary` and default `off-type` is `default`
                    
