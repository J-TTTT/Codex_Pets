# G.E.M. · 制作与修复记录

- 仅使用用户确认的黑色舞台装图作为角色外观依据，中性参考调整了站姿、空手位置和麦克风高度。
- 左右跑动分别生成，避免镜像造成固定持麦侧、发型分区及服装配件方向改变。
- 待机初稿的卷发相连且末帧靠边；完整六帧重绘间距后通过检查。
- 向右跑初稿首帧发梢靠边；完整八帧缩小构图、增加间距后通过检查。
- 失败动作初稿姿态间头发靠近；完整八帧修正间距后通过检查。
- 向右跑和跳跃使用技能的统一视口提取，以保留原图中的抬脚、腾空及落地高度；默认逐帧紧裁会丢失这些自然变化。具体依据见 extraction-decisions.md。
- 当前各行源图轮廓、帧数与提取检查结果保存在对应的 source-geometry 和最终 review 记录中。

- Row 10 third source: eight complete silhouettes, source heights 452–454 px vs approved row 9 heights 421–423 px. Fixed row 9 registration produced 111 edge pixels in direction 180; rejected. Requested complete coherent row repair with smaller drawings; no acceptance thresholds changed.

- Row10 smaller coherent source passed all8direction semantics and edges, but independent normal-size loop review failed: body/head/shoulder/mic/belt visibly shrink at157.5→180, grow337.5→000. Complete row framing repair required; semanticposes retained.

- Final accepted row10 source7b7b1048: eight separated fullbody components,410–413pxsourceheight, noouterclipping. Originalrow9registration retainedexactly; all8finaledgechecks pass. Independentnative-loop review passes: lowerbody/waist/mic scale remainsstable; boundary head/hairchanges acceptedminorwarnings. No rescalingrow9, one-offcellpatches or thresholdchanges used.
