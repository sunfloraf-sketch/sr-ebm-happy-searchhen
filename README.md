# SR x EBM Happy SearchHen 搜尋策略生成雞

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21960702.svg)](https://doi.org/10.5281/zenodo.21960702)

Four independent, browser-based tools for systematic-review (SR) literature searching. Everything runs in your browser by default, and every page links to the others. Only MeSH lookups and PubMed result counts are sent to the official NLM MeSH services and NCBI E-utilities API: in PubMed Light (live counts can be switched off), or when you explicitly request a count estimate in the PICO Builder.

四個獨立、在瀏覽器中執行的系統性文獻回顧（SR）檢索小工具。資料預設只在瀏覽器本機處理，每一頁都能跳到其他工具；只有 MeSH 查詢與 PubMed 筆數會送至 NLM MeSH 服務及 NCBI 官方 E-utilities API：PubMed Light 查詢 MeSH 與即時筆數時（即時筆數可關閉），或使用者主動要求 PICO 產生器估算 PubMed 結果數時。

## Use it online · 線上使用

### ➡️ https://sunfloraf-sketch.github.io/sr-ebm-happy-searchhen/

Just open the link in any modern browser (Chrome, Edge, Firefox, Safari) — no installation and no download needed. The site is always the latest version. Switch between Chinese and English with the language button at the top-right of any page.

用任何現代瀏覽器打開上面的網址就能直接使用，**免安裝、免下載，永遠是最新版**。各頁右上角可切換中文／英文，切換後會記住偏好。

## Tools · 工具

The four tool families are **not sequential** — use whichever you need. The PICO Strategy Builder has separate medical and non-medical pages.

四個工具類型**沒有先後順序**，依需要挑選使用；PICO 檢索策略產生器分為醫學與非醫學兩個頁面。

| Tool | 工具 | What it does |
|------|------|--------------|
| **Proximity Builder** | 鄰近字組合器 | Turn stacks of synonyms into a proximity (adj/near/N) fragment, or auto-split a *Before* list into stacks. Choose ordered or unordered, and adjacent (0). Can send the result straight to the PICO Builder or the Converter. |
| **PICO Strategy Builder** | PICO 檢索策略產生器 | Fill in free-text and controlled terms per PICO concept, pick a field level, and generate line-numbered strategies for each database, with MeSH / Emtree / CINAHL Headings mapping. Import a filled Word template, compare PubMed counts, run the expanded final strategy directly in PubMed, or copy it and open another database's official search page. |
| **Non-medical PICO Builder** | 非醫學領域 PICO 產生器 | Build strategies for Web of Science, Scopus, ProQuest PQDT, Academic Search Complete, Business Source Complete, ERIC, a custom EBSCOhost database, Ei Compendex, and IEEE Xplore. Platform-native controlled-vocabulary expressions are carried through verbatim; IEEE output includes official-rule compatibility checks. |
| **Search Syntax Converter** | 資料庫檢索語法轉換器 | Paste a query written for any starting database and generate syntax for seven databases/platforms in one click; reference lines with `#1 #2`, and export to Word. |
| **PubMed Light ✦** | PubMed Light ✦ | Build a PubMed search row by row, guided by PICO + study design. MeSH headings are suggested as you type; picking one adds the heading and its synonyms (Entry Terms) in one click. Choose MeSH and free-text fields, apply proximity per row, browse broader/narrower headings and See Also, write custom combinations (`#1 AND (#2 OR #3)`), and see live PubMed counts. |

Supported databases/platforms: MEDLINE (Ovid), PubMed, Cochrane, Embase, CINAHL (EBSCOhost), Web of Science, Scopus.

支援的資料庫／平台：MEDLINE (Ovid)、PubMed、Cochrane、Embase、CINAHL (EBSCOhost)、Web of Science、Scopus。

## Citation · 引用

If you use this toolkit in your work, please cite it using the DOI below, or use the metadata in [`CITATION.cff`](CITATION.cff). The DOI always resolves to the latest version.

如果你在研究中使用本工具，請以下列 DOI 引用，或使用 [`CITATION.cff`](CITATION.cff) 內的資訊。此 DOI 永遠指向最新版本。

> Fang, C.-J. (2026). *SR / EBM Search Toolkit: Proximity Builder, PICO Strategy Builder, Search Syntax Converter, and PubMed Light*. Zenodo. https://doi.org/10.5281/zenodo.21960702

## License · 授權

All rights reserved. You may use the tool online, free of charge, at its official address for personal, educational, research or clinical work; search strategies you create are yours to use. Copying, modifying, re-hosting (including mirrors and iframe embedding), redistribution or commercial use require the author's prior written consent. See [LICENSE](LICENSE).

著作權所有，保留一切權利。歡迎透過官方網址免費線上使用（個人、教學、研究、臨床皆可），產生的檢索策略歸使用者自由運用；未經作者書面同意，不得複製、修改、改作、放置於其他網站（含鏡像、iframe 嵌入）、再散布或商業利用。詳見 [LICENSE](LICENSE)。

© 2026 Ching-Ju Fang
