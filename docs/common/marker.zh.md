| 参数名  | 类型                          | 默认值 | 描述                             |
| ------- | ---------------------------- | ------ | -------------------------------- |
| symbol  | _Marker_ \| _MarkerCallback_ | -      | 配置图例 marker 的 symbol 形状   |
| style   | _ShapeAttrs_                   | -      | 图例项 marker 的配置项           |
| spacing | _number_                       | -      | 图例项 marker 同后面 name 的间距 |

_Marker_ 为支持的标记类型有： _circle | square | line | diamond | triangle | triangle-down | hexagon | bowtie | cross | tick | plus | hyphen_；
_MarkerCallback_ 为 `(x: number, y: number, r: number) => PathCommand`；
