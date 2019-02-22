# cityDataForTax

新个税的城市列表数据（用于个税专项扣除中住房租金项目）

网上找到的只有下面的图，所以用代码处理了一下，整理成数据

```
// 直辖市和省会
const directlyCity = [
  {
    "name": "北京市",    // 城市名称
    "code": "110100"    // 行政区划代码
  }
  ...
]

// 人口大于100万的城市
const gtMillionCity = [
  {
    "name": "唐山市",
    "code": "130200"
  }
  ...
]

// 人口小于100万城市
const ltMillionCity = [
  {
    "name": "邢台市",
    "code": "130500"
  }
  ...
]
```

![城市列表](https://a4.qpic.cn/psb?/V10bFcpb0zylvj/S584hXU9cca.SFtYyqFLD1Dw0SERO6dhP2NeyTV7rGQ!/b/dL8AAAAAAAAA&ek=1&kp=1&pt=0&bo=hAVXAwAAAAADV6c!&tl=1&vuin=2049098483&tm=1550804400&sce=60-2-2&rf=viewer_4)

