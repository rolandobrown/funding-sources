# Build Finance Dashboard using Sankey Diagrams

Demo: <http://schafferwilliams.com/finances>

Source Demo: <http://bost.ocks.org/mike/sankey/>

```js
var sankey = d3.sankey()
    .size([width, height])
    .nodeWidth(15)
    .nodePadding(10)
    .nodes(energy.nodes)
    .links(energy.links)
    .layout(32);
```

```
var path = sankey.link();
```
