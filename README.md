# 显密文库 · 公开文本仓（xianmi-texts）

**语言 / Language**：简体中文 | [繁體中文](README.zh-TW.md)

[显密文库](https://www.xianmi.co/) 的公开文本仓库，作为社区协作入口，从少到多逐步开放。

**首发收录：公有领域佛典与古德著述（2,029 篇/侧，简繁双版镜像）**，后续将逐步开放更多部类。

## 首发内容（六组）

| 组 | 内容 | 篇数/侧 |
| --- | --- | --- |
| 阿含部 | 杂阿含经（刘宋·求那跋陀罗译）、长阿含经（后秦·佛陀耶舍等译） | 1,385 |
| 汉传经本与注疏 | 净土、天台、华严三系经本与古德注疏（曹魏至清，带大正藏编号核验） | 222 |
| 华严三译 | 六十华严（东晋·佛驮跋陀罗译）、八十华严（唐·实叉难陀译）、四十华严（唐·般若译） | 36 |
| 僧传史籍 | 高僧传系（梁·慧皎等）、居士传（清·彭际清）、隋唐居士文集 | 242 |
| 禅宗典籍 | 经、论、文集、语录、灯录与观音经疏 | 111 |
| 其他古典 | 安士全书、了凡四训、地藏系经典、金刚经六译、秽迹经典 | 33 |

## 目录结构

```
zh-cn/   简体（路径与显密文库主站一一对应）
zh-tw/   繁体（与简体镜像同构）
```

文件为 Markdown（含 Astro Starlight 组件语法的页面原样保留），各栏目附索引页。

## 繁体目录（zh-tw）说明

繁体内容为 **OpenCC 机器转繁（s2tw 台湾正体）+ 勘误规则** 的产物：文本**以简体（zh-cn）为准**；繁体错字请开 issue，我们会在勘误规则中修正后重新转换（详见 [CONTRIBUTING](CONTRIBUTING.md)）。

## 许可与版权（License）

<a href="https://creativecommons.org/publicdomain/zero/1.0/deed.zh-hans"><img src="images/cc0.png" alt="CC0 1.0 公有领域贡献" width="88" height="31"></a>

- 本仓收录文本均为**公有领域**（public domain）典籍：古代译本、古代注疏、僧传与文集，可自由使用，无任何限制。
- 本站的**整理、校勘与内容提要**等加工成果以 [CC0 1.0 Universal](LICENSE) 释出，同样可自由使用（含商用），无需署名。
- 第三方权利：若内容涉及您的权利，请通过 <https://www.xianmi.co/contribute/> 与我们联系，我们会在核实后尽快处理。

## English Summary

**xianmi-texts** is the public text repository of [Xianmi Library](https://www.xianmi.co/) (显密文库), a free Chinese Buddhist digital library. Debut collection: public-domain Buddhist canon and classical commentarial works — 2,029 texts per side, mirrored in Simplified (`zh-cn/`, canonical) and Traditional (`zh-tw/`) Chinese. All included texts are in the public domain; our editorial layer (organization, collation, synopses) is released under [CC0 1.0](LICENSE). Traditional files are machine-converted from the Simplified side — please submit PRs against `zh-cn` only. See the Chinese text above for details, or open an issue.
