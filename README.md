# kicw 报价表

![](demo1.png)

## 类

| 类 | 修饰 | 说明
|----|------|----
| .kicw         | | 主类
| .kicw         | .stripped | row部分使用奇偶行斑马纹
| .kicw-item    | | 一个报价方案
| .kicw-head    | | item头
| .kicw-foot    | | item尾
| .kicw-row     | | 行
| .kicw-row     | .x      | 字体加大1
| .kicw-row     | .xx     | 字体加大2
| .kicw-row     | .xxx    | 字体加大3
| .kicw-row     | .s      | 字体减小1
| .kicw-row     | .b      | 粗体
| .kicw-row     | .line1      | 1行高（供不同item高度对齐用）
| .kicw-row     | .line2      | 2行高
| .kicw-row     | .line3      | 3行高
| .kicw-row     | .line4      | 4行高
| .kicw-ribbon | | 飘带

## 层次关系

```
.kicw
    .kicw-item
        .kicw-head
        .kicw-row
        .kicw-row
        .kicw-row
        .kicw-foot
```