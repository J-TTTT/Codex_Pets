# G.E.M. 婚纱版 · 验收记录

[返回角色说明](../README.md) · [完整帧表](contact-sheet-extended.png) · [方向图](look-directions.png)

本目录集中保留原制作与安装的检查证据。本次整理没有重新运行图像生成，也没有更改最终精灵图集；新增的结构化视觉结论由原独立检查记录转录。

## 结论一览

| 检查 | 结论 | 记录 |
| --- | --- | --- |
| v2 图集格式 | 1536 × 2288、RGBA、8 × 11，通过；零错误、零警告 | [验证报告](validation-extended.json) |
| 透明边缘 | 处理成功，透明通道保持不变 | [边缘处理](chroma-despill-extended.json) |
| 九种动作 | 全部 57 帧独立检查通过 | [结构检查](review.json)、[视觉检查](standard-visual-qa.json) |
| 四个基本方向 | 上、右、下、左全部通过 | [方向判定](cardinal-semantics.json)、[拆帧检查](cardinal-anchors.json) |
| 十六方向语义 | 每个方向均有单独结论及上下/左右证据 | [逐方向检查](direction-semantics.json) |
| 独立盲测 | 三份判断全部一致，28/28 轴向判断正确 | [验证](direction-blind-validation.json)、[多数合并结果](direction-blind-verdicts.json) |
| 连续性与透明缺口 | 无异常透明缺口；两处像素差异提示经复核接受 | [连续性](look-continuity.json)、[复核说明](blind-review-resolution.json) |
| 最终视觉复核 | 全部 73 帧检查通过，未发现裁切、明显跳变或错误方向 | [结构化结论](final-visual-qa.json)、[原始记录](final-visual-review.txt) |
| 安装与既有拍档 | 安装图集哈希一致，12 个已有文件未改动 | [安装记录](installation.json) |

## 已接受的轻微差异

`000→022.5` 和 `157.5→180` 的像素差异高于邻近过渡。独立检查者结合实际显示大小与完整循环确认，这来自头部和面部姿态变化，没有明显的身体位置或尺寸跳变。部分接近基本方向的斜向姿态，其次要轴向线索较轻，但三份盲测均正确辨认。

跳跃使用共享画幅拆帧以保留起跳和落地的高度变化，原结构报告会对此提示人工检查；独立视觉复核已通过。

盲测本身没有错误或警告，也没有使用例外豁免。`blind-review-resolution.json` 用于集中记录这一事实及已接受的连续性提醒。

## 原始证据与制作记录

- [盲测图](direction-blind-pairs.png)、[答案表](direction-blind-answer-key.json)
- 三份隔离判定：[检查者 1](direction-blind-verdicts-1.json)、[检查者 2](direction-blind-verdicts-2.json)、[检查者 3](direction-blind-verdicts-3.json)
- [注视运动方案](look-mechanics.md)、[第一组注视方向复核](look-row-9-semantic-review.txt)
- [源图轮廓检查](source-geometry.json)、[源图检查说明](source-review.md)、[方向锚点拆帧说明](cardinal-extraction-resolution.md)
- [最终选定素材记录](generation-log.json)、[原生产摘要](production-run-summary.json)、[便携交付摘要](run-summary.json)
- [完整生成提示词](../generation-prompts.md)、[原制作需求](../pet_request.json)

原始记录中的生产路径和部分已清理缓存路径用于追溯，不是预览页面的资源依赖。完整包中所有 README 与 HTML 的本地链接均经过文件存在性检查。
