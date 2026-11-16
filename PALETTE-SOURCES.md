# 色号数据来源与说明

豆小格拼豆生成器本项目新增的 MARD 291 与 COCO 291 参考色号数据，来自公开数据仓库：

- 上游项目：HansBug/pindou-color-data
- 上游仓库：https://github.com/HansBug/pindou-color-data
- MARD 数据：mard-291-github/colors.json
- COCO 数据：coco-291/colors.json
- 上游仓库声明的许可：MIT
- 本项目数据文件：data/mard-291.json、data/coco-291.json

本项目保留上游色号与 HEX，不将其描述为品牌官方测色数据。HEX 仅用于屏幕近似预览，实物颜色可能受材料、批次、光线和显示器影响。不同公开色卡可能存在差异；采购前请以所购品牌实物色卡为准。

本项目与 MARD、COCO 及其他拼豆品牌无隶属或官方授权关系。商标归各自权利人所有。


## Artkal C 197

- 上游项目：HansBug/pindou-color-data
- 上游数据：`artkal-c-197-official/colors.json`
- 上游仓库许可：MIT（保留上游版权与许可声明）
- 本项目数据文件：`data/artkal-c-197.json`
- 官方依据：Artkal 官方 C-2.6mm 色卡页面标注 197 色，并提供 RGB 色卡下载；上游数据大部分颜色来自官方 RGB PDF，CG/CP/CT 等特殊材质色值部分按官方色卡图采样，并在每条记录的 `notes`/`source` 中注明，不应视为厂商发布的精确 RGB。
- 屏幕 HEX 仅供近似预览，实际颜色受材料、批次、光线和显示器影响。本项目与 Artkal/优肯无隶属或官方授权关系，商标归各自权利人所有。


## Artkal M 221

- 上游项目：HansBug/pindou-color-data
- 上游数据：`artkal-m-221-official/colors.json`
- 上游仓库许可：MIT（保留上游版权与许可声明）
- 本项目数据文件：`data/artkal-m-221.json`
- 上游说明：大部分 RGB 来自 Artkal 官方 RGB PDF；MH1 透明色在官方 PDF 中仅标注 Transparent，上游按透明 RGBA 表达，不能称为厂商发布的数值 RGB。
- 屏幕 HEX 仅供近似预览，实际颜色受材料、批次、光线和显示器影响。本项目与 Artkal/优肯无隶属或官方授权关系，商标归各自权利人所有。


## Artkal S 176（社区参考值）

- 本项目数据文件：`data/artkal-s-176.json`
- 上游数据：pomodiary/bitbead.app `data/palettes.json` 中的 `artkal` 数组
- 许可：CC BY 4.0，按许可要求保留署名与来源
- 官方色卡：Artkal S 系列总数为 225；官方 RGB 图表可提供 173 个数字 RGB 条目。当前接入的 176 条是社区整理的屏幕参考值，不代表完整官方 225 色，也不代表每条 HEX 都由厂商发布。
- 屏幕 HEX 仅供近似预览，特殊材质效果无法由纯色块准确表现。
