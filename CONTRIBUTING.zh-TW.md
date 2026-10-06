# 協作指南（Contributing）

**語言 / Language**：[简体中文](CONTRIBUTING.md) | 繁體中文

感謝參與顯密文庫公開文本倉的勘誤協作。

## 提 PR 前請讀

- **只對 `zh-cn` 提 PR**：繁體（`zh-tw`）是 OpenCC 機器轉繁 + 勘誤規則的產物，直接改繁體會與轉換管線衝突。繁體錯字請[開 issue](https://github.com/xianmi-lib/xianmi-texts/issues)，我們會在勘誤規則中修正後重新轉換。
- PR 請寫明：文件路徑、原文位置、修改依據（底本/刻本/出處連結優先）。
- 不接受大規模機器改寫類 PR（重排、批量標點轉換等）；此類需求請先開 issue 討論。

## 維護者注意：PR 合併後必須回植主倉（關鍵閉環）

本倉是**顯密文庫主內容倉（私有）→ 本倉**的單向鏡像：內容更新由同步腳本以 `rsync --delete` 鏡像出倉。**若合併的 PR 改動未回植主倉，下次同步即被沖掉。**

正確流程：

1. 在本倉合併社區 PR；
2. **立即把 PR 改動回植到主內容倉（goodweb）對應文件**（cherry-pick 或手工），並走完主倉驗證與提交；
3. 由主倉側運行同步腳本重新出倉（`tools/sync-texts.sh`）。

嚴禁：直接在本倉改完不通知主倉側——改動會在下次同步時靜默丟失。

## 認領與聯繫

- 版權/權利相關：見 [README](README.zh-TW.md) 許可節，走 <https://www.xianmi.co/zh-tw/contribute/>。
- 其他問題：開 issue。

## English Summary

Contributions: please submit PRs against `zh-cn` (Simplified Chinese) only — `zh-tw` (Traditional) is machine-converted via OpenCC plus errata rules, and direct edits there conflict with the conversion pipeline. For Traditional typos, open an issue instead. Maintainers: after merging a community PR, the change **must be back-ported to the private master repo** before the next sync run, otherwise it will be silently overwritten. Details are in the Chinese text above.
