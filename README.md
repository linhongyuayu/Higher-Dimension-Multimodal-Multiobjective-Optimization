# Higher-Dimension Multimodal Multiobjective Optimization

<!-- solver-policy-20260922 -->
> **2026-09-22 求解器决定：** 今后不再使用 Gurobi，也不再要求许可证或续期。采用当前项目已验证的替代器；尚未迁移的旧入口保持停用。历史结果及求解器标注保留。本段即本仓当前求解器约束；不改写历史实验记录。
<!-- /solver-policy-20260922 -->

**[逐文件路径与分类](FILEMAP.md) · [机器可读清单](FILEMAP.csv)**

Competition materials for higher-dimensional multimodal multiobjective optimization.

## Files

| File | Description |
|---|---|
| [WCCI-CEC2026-HDMMF.zip](WCCI-CEC2026-HDMMF.zip) | WCCI-CEC2026 HDMMF archive |
| [WCCI-CEC2026 HDMMO Competition Entry Instruction Document.docx](WCCI-CEC2026%20HDMMO%20Competition%20Entry%20Instruction%20Document.docx) | Competition entry instructions |
| [Introduction to WCCI-CEC2026 HDMMO Test Problem.docx](Introduction%20to%20WCCI-CEC2026%20HDMMO%20Test%20Problem.docx) | Test problem introduction |

## Browsable source and complete member index

- [source/](source/): source browsing copies under `source/<archive-stem>/<original-member-path>`.
- [Complete member index](ARCHIVE_INDEX.md) / [JSON index](ARCHIVE_INDEX.json): all 30 archive members, their sizes and SHA256 hashes, including links to 15 source copies.

The original ZIPs are frozen artifacts; `source/` copies preserve the exact member bytes. Running the code still requires the matching archive data, working directory and dependencies; standalone execution has not been verified.

## Directory roles and release boundary (2026-09-21)

| Location | Role |
|---|---|
| [source/WCCI-CEC2026-HDMMF/HDMMF/](source/WCCI-CEC2026-HDMMF/HDMMF/) | 15 benchmark problem classes for browsing |
| `WCCI-CEC2026-HDMMF.zip/HDMMF/*_Reference_PSPF_data.mat` | 15 reference datasets; original bytes remain in the ZIP |
| Root DOCX files | Competition entry instructions and test-problem introduction |

This repository supplies benchmark problems, not a complete optimization algorithm or platform. [NMMF1.m](source/WCCI-CEC2026-HDMMF/HDMMF/NMMF1.m) inherits from external `PROBLEM` and loads `NMMF1_Reference_PSPF_data.mat` by filename. A future run needs a compatible PlatEMO environment and the matching extracted MAT files visible on the MATLAB path; the source-only browsing tree is insufficient. No exact platform version or competition runtime setup has been established here.

All 30 ZIP members passed CRC/path/index-hash checks; the 15 committed source copies match their original member bytes. No MATLAB execution, numerical comparison or DOCX scientific-content review was performed in this check. Keep this package's class/data pairing: equal MAT bytes across releases do not prove equal problem implementations. This is a release snapshot, not a live project-memory record.
