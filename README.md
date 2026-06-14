# Aiden 学区地图（公开版）

上海宝山与香港校网14 候选学校的交互地图。主教育规划仓库为私有，本仓库**仅发布地图**，住址已脱敏。

## 在线访问

**https://silvermoonswk.github.io/Aiden-s-Education-Plan-map/**

## 文件

| 文件 | 说明 |
|:---|:---|
| `school-map.html` | Leaflet 交互地图 |
| `schools-geo.json` | 学校坐标、通勤、推荐度（公开脱敏版） |

## 隐私说明

- 家庭住址仅显示「宝山区片区示意」，不含门牌
- 香港锚点为「校网14参考点」，不含具体楼盘
- 完整数据在私有主仓库维护

## 更新

主仓库运行 `scripts/sync_public_map.sh` 可同步地图逻辑；`schools-geo.json` 会输出脱敏版。
