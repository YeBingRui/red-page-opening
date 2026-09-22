---
# 技能展示名称，最多50字
display_name: "红色网页打开器"

# 一句话简介，最多200字
display_description: "一键打开一个红色背景的本地网页，完全离线可用，支持按需调整红色色值和页面标题。"

# 分类，单选
type: "办公学习"

# 使用示例，最多三个
use_cases: ["打开一个红色网页", "打开一个深红色页面，标题叫测试通过", "再打开一个红色网页，别覆盖之前那个"]

# 核心功能点，使用\n进行换行
detail_describe: "开箱即用的纯红色背景本地网页，双击即可打开\n支持自定义色值、页面标题与中央文案，自动保证文字可读性\n修改时生成副本，同名文件自动换名，不覆盖已有文件\n完全离线运行，不请求外部资源、不采集任何数据\nWin/Mac 通用，由 Agent 直接唤起浏览器打开并验证加载结果"

# 来源名称，单选
# 可选值：Marvis、Claude、Github、ClawHub、SkillHub
author: "Marvis"

# Agent 路由，可多选
# 可选值：search-agent、file-agent、win-use、app-use、browser、main
scope: ["file-agent", "browser", "main"]

# 支持展示的场景列表，可多选
support_plat_ids: "[win端, mac端]"

#技能zip名称，与main.md文件同级的技能zip文件名称
skillZipName: "red-page-opening"

#用例zip名称，与main.md文件同级的用例zip文件名称
skillTestCaseZipName: "redpage-testcase"
---
