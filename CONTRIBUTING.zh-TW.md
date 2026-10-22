# 協作指南（Contributing）

**語言 / Language**：[简体中文](CONTRIBUTING.md) | 繁體中文

感謝參與顯密文庫公開文本倉的勘誤協作。

## 提 PR 前請讀

- **只對 `zh-cn` 提 PR**：繁體（`zh-tw`）是 OpenCC 機器轉繁 + 勘誤規則的產物，直接改繁體會與轉換管線衝突。繁體錯字請[開 issue](https://github.com/xianmi-lib/xianmi-texts/issues)，我們會在勘誤規則中修正後重新轉換。
- PR 請寫明：文件路徑、原文位置、修改依據（底本/刻本/出處連結優先）。
- 不接受大規模機器改寫類 PR（重排、批量標點轉換等）；此類需求請先開 issue 討論。

## 維護者注意：PR 合併後必須回植上游內容源（關鍵閉環）

本倉內容不是在此直接維護的：文章正文維護於上游內容源，本倉由其定期發佈。**若合併的 PR 改動未回植上游內容源，下次發佈會把本倉的改動覆蓋掉。**

正確流程：

1. 在本倉合併社群 PR；
2. 維護方把 PR 改動回植到上游內容源的對應檔案，並完成上游驗證；
3. 由維護方重新發佈到本倉，使兩側一致。

請勿只在本倉改動而不回植——此類改動會在下次發佈時遺失。

## 認領與聯繫

- 版權/權利相關：見 [README](README.zh-TW.md) 許可節，走 <https://www.xianmi.co/zh-tw/contribute/>。
- 其他問題：開 issue。

## English Summary

Contributions: please submit PRs against `zh-cn` (Simplified Chinese) only — `zh-tw` (Traditional) is machine-converted via OpenCC plus errata rules, and direct edits there conflict with the conversion pipeline. For Traditional typos, open an issue instead. Maintainers: after merging a community PR, the change **must be back-ported to the upstream content source** before the next publication, otherwise it will be overwritten by the next publish. Details are in the Chinese text above.
