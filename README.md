# react-echarts-v3
React component wrap for ECharts(v3.x)


## Installation

```
$ npm install --save react-echarts-v3
```


## Usage

``` javascript
import IECharts from 'react-echarts-v3';

const option = {
    title: { text: 'ECharts 入门示例' },
    tooltip: {},
    xAxis: {
        data: ["衬衫","羊毛衫","雪纺衫","裤子","高跟鞋","袜子"]
    },
    yAxis: {},
    series: [{
        name: '销量',
        type: 'bar',
        data: [5, 20, 36, 10, 10, 20]
    }]
};

return (
    <IECharts option={option} />
);
```

OR

``` javascript
import IECharts from 'react-echarts-v3/lib/echarts';

// Import all charts and components
// require('echarts/lib/chart/line');
require('echarts/lib/chart/bar');
// require('echarts/lib/chart/pie');
// require('echarts/lib/chart/scatter');
// require('echarts/lib/chart/radar');

// require('echarts/lib/chart/map');
// require('echarts/lib/chart/treemap');
// require('echarts/lib/chart/graph');
// require('echarts/lib/chart/gauge');
// require('echarts/lib/chart/funnel');
// require('echarts/lib/chart/parallel');
// require('echarts/lib/chart/sankey');
// require('echarts/lib/chart/boxplot');
// require('echarts/lib/chart/candlestick');
// require('echarts/lib/chart/effectScatter');
// require('echarts/lib/chart/lines');
// require('echarts/lib/chart/heatmap');

// require('echarts/lib/component/graphic');
// require('echarts/lib/component/grid');
// require('echarts/lib/component/legend');
// require('echarts/lib/component/tooltip');
// require('echarts/lib/component/polar');
// require('echarts/lib/component/geo');
// require('echarts/lib/component/parallel');
// require('echarts/lib/component/singleAxis');
// require('echarts/lib/component/brush');

// require('echarts/lib/component/title');

// require('echarts/lib/component/dataZoom');
// require('echarts/lib/component/visualMap');

// require('echarts/lib/component/markPoint');
// require('echarts/lib/component/markLine');
// require('echarts/lib/component/markArea');

// require('echarts/lib/component/timeline');
// require('echarts/lib/component/toolbox');

// require('zrender/lib/vml/vml');


const option = {
    title: { text: 'ECharts 入门示例' },
    tooltip: {},
    xAxis: {
        data: ["衬衫","羊毛衫","雪纺衫","裤子","高跟鞋","袜子"]
    },
    yAxis: {},
    series: [{
        name: '销量',
        type: 'bar',
        data: [5, 20, 36, 10, 10, 20]
    }]
};

return (
    <IECharts option={option} />
);
```

## Properties

``` javascript
    option: React.PropTypes.object.isRequired,
    style:  React.PropTypes.object
```

[Read More](http://echarts.baidu.com/option.html)

# License

MIT
