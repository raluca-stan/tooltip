# rc-tooltip
---

tooltip ui component for react

[![NPM version][npm-image]][npm-url]
[![SPM version](http://spmjs.io/badge/rc-tooltip)](http://spmjs.io/package/rc-tooltip)
[![build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]
[![gemnasium deps][gemnasium-image]][gemnasium-url]
[![node version][node-image]][node-url]
[![npm download][download-image]][download-url]
[![Sauce Test Status](https://saucelabs.com/buildstatus/rc-tooltip)](https://saucelabs.com/u/rc-tooltip)

[![Sauce Test Status](https://saucelabs.com/browser-matrix/rc-tooltip.svg)](https://saucelabs.com/u/rc-tooltip)

[npm-image]: http://img.shields.io/npm/v/rc-tooltip.svg?style=flat-square
[npm-url]: http://npmjs.org/package/rc-tooltip
[travis-image]: https://img.shields.io/travis/react-component/tooltip.svg?style=flat-square
[travis-url]: https://travis-ci.org/react-component/tooltip
[coveralls-image]: https://img.shields.io/coveralls/react-component/tooltip.svg?style=flat-square
[coveralls-url]: https://coveralls.io/r/react-component/tooltip?branch=master
[gemnasium-image]: http://img.shields.io/gemnasium/react-component/tooltip.svg?style=flat-square
[gemnasium-url]: https://gemnasium.com/react-component/tooltip
[node-image]: https://img.shields.io/badge/node.js-%3E=_0.10-green.svg?style=flat-square
[node-url]: http://nodejs.org/download/
[download-image]: https://img.shields.io/npm/dm/rc-tooltip.svg?style=flat-square
[download-url]: https://npmjs.org/package/rc-tooltip

## Screenshots

<img src="http://gtms03.alicdn.com/tps/i3/TB1NQUSHpXXXXaUXFXXlQqyZXXX-1312-572.png" width="600"/>

## Feature

* support ie8,ie8+,chrome,firefox,safari


## install

[![rc-tooltip](https://nodei.co/npm/rc-tooltip.png)](https://npmjs.org/package/rc-tooltip)

## Usage

```js
var Tooltip = require('rc-tooltip');
var React = require('react');
React.render(<Tooltip placement="left" trigger={['click']} overlay={<span>tooltip</span>}><a href='#'>hover</a></Tooltip>, container);
```

## Example

http://localhost:8000/examples/index.md

online example: http://react-component.github.io/tooltip/build/examples/

## API

### props

<table class="table table-bordered table-striped">
    <thead>
    <tr>
        <th style="width: 100px;">name</th>
        <th style="width: 50px;">type</th>
        <th style="width: 50px;">default</th>
        <th>description</th>
    </tr>
    </thead>
    <tbody>
        <tr>
          <td>className</td>
          <td>String</td>
          <td></td>
          <td>additional css class of root dom node</td>
        </tr>
        <tr>
          <td>prefixCls</td>
          <td>String</td>
          <td>rc-tooltip</td>
          <td>prefix class name</td>
        </tr>
        <tr>
          <td>transitionName</td>
          <td>String</td>
          <td></td>
          <td>same as https://github.com/react-component/css-transition-group</td>
        </tr>
        <tr>
          <td>placement</td>
          <td>String</td>
          <td></td>
          <td>one of ['left','right','top','bottom']</td>
        </tr>
        <tr>
          <td>overlay</td>
          <td>React.Element</td>
          <td></td>
          <td>popup content</td>
        </tr>
    </tbody>
</table>


## Development

```
npm install
npm start
```

## Test Case

http://localhost:8000/tests/runner.html?coverage

## Coverage

http://localhost:8000/node_modules/rc-server/node_modules/node-jscover/lib/front-end/jscoverage.html?w=http://localhost:8000/tests/runner.html?coverage

## License

rc-tooltip is released under the MIT license.
