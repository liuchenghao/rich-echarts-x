ECharts-X
=======

ECharts-X is an extension pack of [ECharts](https://github.com/luqin/echarts) providing globe visualization and 3D plots. Maintained by [ECharts](http://echarts.baidu.com/doc/about.html) team.

It is built on top of Canvas library [ZRender](https://github.com/luqin/zrender) and WebGL graphic library [QTEK](https://github.com/luqin/qtek)。

[![NPM version][npm-badge]][npm]

[![Dependency Status][deps-badge]][deps]
[![devDependency Status][dev-deps-badge]][dev-deps]
[![peerDependency Status][peer-deps-badge]][peer-deps]

[npm-badge]: http://badge.fury.io/js/echarts-x.svg
[npm]: http://badge.fury.io/js/echarts-x

[deps-badge]: https://david-dm.org/luqin/echarts-x.svg
[deps]: https://david-dm.org/luqin/echarts-x

[dev-deps-badge]: https://david-dm.org/luqin/echarts-x/dev-status.svg
[dev-deps]: https://david-dm.org/luqin/echarts-x#info=devDependencies

[peer-deps-badge]: https://david-dm.org/luqin/echarts-x/peer-status.svg
[peer-deps]: https://david-dm.org/luqin/echarts-x#info=peerDependencies

### Installation

Using npm:

```sh
$ npm i --save echarts-x
```

Then with a module bundler like [webpack](https://github.com/webpack/webpack), require `text-loader`:

```js
import echarts from 'rich-echarts';
import 'rich-echarts-x';
import 'rich-echarts/chart/map';
import 'rich-echarts/chart/bar';
import 'rich-echarts-x/chart/map3d';

let mychart = echarts.init(dom);
mychart.setOption({...});
```

### [Documentation](http://echarts.baidu.com/x/doc/cn/article/getting_started.html)

### [Examples](http://echarts.baidu.com/x/doc/example.html)

[online demo](http://luqin.github.io/echarts-x/examples/webpack) [webpack example source code](https://github.com/luqin/echarts-x/tree/master/examples/webpack)

### [Changelog](https://github.com/ecomfe/echarts-x/wiki/Changelog)
