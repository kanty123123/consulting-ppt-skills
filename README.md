# Consulting PPT Skills

中文咨询风PPT策划与GPT Image图片制作技能集，当前参考风格为麦肯锡。

## 所含技能

- `consulting-ppt-image`：主技能，当前版本1.4.1。内容组织、七大论证版式、图文区域、复杂图表与整页图片生成。
- `consulting-ppt-planner`：确定每页问题、结论、证据、实际文案及图文比例。
- `consulting-ppt-planner-123`：仅以01叙事、02论证、03表达为方法依据的试验性策划。

[下载完整Skill安装包](consulting-ppt-skills.zip)

## 安装与调用

将`skills/`下面需要的技能目录复制到Codex个人技能目录（通常为`~/.codex/skills/`），重新打开会话后调用。保留每个技能中的SKILL.md、references、assets及scripts目录结构。

```text
使用 $consulting-ppt-image
受众：领导上级
表达目标：解释业绩及其驱动
页数：4页
交付：生成4张PPT图片
原始材料：[粘贴材料]
```

只做内容策划时调用`$consulting-ppt-planner`；试验01–03方法时调用`$consulting-ppt-planner-123`。

## 运行依赖与范围

普通图片路线需要当前环境可用的GPT Image工具。`scripts/prepare_chart_reference.cjs`代码参考路线可选，另依赖已安装的`zerox-consulting-report-forge`及其Node/Playwright运行环境；此仓库未打包该独立技能。具体入口以各SKILL.md为准。

本包仅包含这三个技能及其运行参考，不含个人账户配置、密钥、用户业务材料、生成项目或其他个人技能。字体与像素参数为生成近似目标，最终图片须依据原数据验收；默认交付图片。

## 参考素材

内含报告页截图和教学图片用于私有参考、布局与图式学习，相关标识和内容权利归原权利人。此仓库不授予第三方素材的再分发许可，也不代表与咨询公司存在关联。不要把参考业务数据或署名用于新报告的事实来源。

导出日期：2026-11-04。
