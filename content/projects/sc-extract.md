+++
title = "sc-extract"
description = "A very fast tool to extract graphics and decode CSVs from compressed game assets."
weight = 1

[extra]
cmd = "cat"
cmd_arg = "sc-extract.md"
toc = false
author = "nextonesfaster"
project_home = "https://github.com/nextonesfaster/sc-extract"
+++

`sc_extract` is a high-performance reusable library and tool for decoding compressed binary asset formats and exporting image and structured-data files.

Some features:

- processes `_tex.sc`, `.sc`, and `.csv` files found in Supercell game assets
- supports LZMA, LZHAM, and zstd compression formats
- 10x faster than similar tools
