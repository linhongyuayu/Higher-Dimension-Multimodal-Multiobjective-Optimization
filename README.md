# Higher-Dimension Multimodal Multiobjective Optimization

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

## Archive layout inspected on 2026-09-15

`WCCI-CEC2026-HDMMF.zip` contains 30 files: 15 MATLAB problem classes and 15 reference MAT files under `HDMMF/`. For example, `HDMMF/NMMF1.m` derives from `PROBLEM` and loads `NMMF1_Reference_PSPF_data.mat`.

The archive directory and selected source text were inspected; the compatible platform version, competition environment and numerical results were not validated. Keep the reference data with its corresponding problem-source version. Matching reference MAT files in another release do not establish identical MATLAB sources.
