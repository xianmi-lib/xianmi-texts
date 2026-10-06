# 协作指南（Contributing）

**语言 / Language**：简体中文 | [繁體中文](CONTRIBUTING.zh-TW.md)

感谢参与显密文库公开文本仓的勘误协作。

## 提 PR 前请读

- **只对 `zh-cn` 提 PR**：繁体（`zh-tw`）是 OpenCC 机器转繁 + 勘误规则的产物，直接改繁体会与转换管线冲突。繁体错字请[开 issue](https://github.com/xianmi-lib/xianmi-texts/issues)，我们会在勘误规则中修正后重新转换。
- PR 请写明：文件路径、原文位置、修改依据（底本/刻本/出处链接优先）。
- 不接受大规模机器改写类 PR（重排、批量标点转换等）；此类需求请先开 issue 讨论。

## 维护者注意：PR 合并后必须回植主仓（关键闭环）

本仓是**显密文库主内容仓（私有）→ 本仓**的单向镜像：内容更新由同步脚本以 `rsync --delete` 镜像出仓。**若合并的 PR 改动未回植主仓，下次同步即被冲掉。**

正确流程：

1. 在本仓合并社区 PR；
2. **立即把 PR 改动回植到主内容仓（goodweb）对应文件**（cherry-pick 或手工），并走完主仓验证与提交；
3. 由主仓侧运行同步脚本重新出仓（`tools/sync-texts.sh`）。

严禁：直接在本仓改完不通知主仓侧——改动会在下次同步时静默丢失。

## 认领与联系

- 版权/权利相关：见 [README](README.md) 许可节，走 <https://www.xianmi.co/contribute/>。
- 其他问题：开 issue。

## English Summary

Contributions: please submit PRs against `zh-cn` (Simplified Chinese) only — `zh-tw` (Traditional) is machine-converted via OpenCC plus errata rules, and direct edits there conflict with the conversion pipeline. For Traditional typos, open an issue instead. Maintainers: after merging a community PR, the change **must be back-ported to the private master repo** before the next sync run, otherwise it will be silently overwritten. Details are in the Chinese text above.
