# 问题

1. tooltip 基本配置

```js
    tooltip: {
                trigger: 'axis',
                triggeron: 'mousemove',
                formatter: function(param) {
                    const item = param[0];
                    return `
                    语文<br/>
                    成绩: ${item.data}
                    `
                }
            },
```

2. title 的配置

```js
    title: {
                text: '成绩排行',
                textStyle: {
                    color: 'red',
                },
                borderWidth: 4,
                borderRadius: 5,
                borderColor: 'green',
                top: 30,
                left: 30,
            },
```

3. 写百分数需要加引号
