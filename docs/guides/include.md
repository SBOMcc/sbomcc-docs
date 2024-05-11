---
sidebar_position: 2
---

# Include Parts Of An SBOM

To include only parts of an SBOM in the output, use the `-i` or `--include` option to specify the field keys to include.

Provide a comma-separated list of field keys to include in the output. For example:

```bash
$ sbomcc -f mock/spdx.json -i name,packages,versionInfo,licenseConcluded
sbom.cc v0.0.3

Packages
	Name			         com.github.SBOMcc/sbomcc-docs
	Version
	--------------------------------------------------
	License Concluded  MIT
	Name			         npm:@algolia/autocomplete-core
	Version			       1.9.3
	--------------------------------------------------
	License Concluded	 MIT
	Name			         npm:@algolia/autocomplete-plugin-algolia-insights
	Version			       1.9.3
	--------------------------------------------------
	License Concluded	 MIT
	Name			         npm:@algolia/autocomplete-preset-algolia
	Version			       1.9.3
	--------------------------------------------------
	License Concluded	 MIT
	Name			         npm:@algolia/autocomplete-shared
	Version			       1.9.3
	--------------------------------------------------
	License Concluded	 MIT
	Name			         npm:@algolia/cache-browser-local-storage
	Version			       4.20.0
	--------------------------------------------------
	License Concluded	 MIT
	Name			         npm:@algolia/cache-common
	Version			       4.20.0
	--------------------------------------------------
	License Concluded	 MIT
	Name			         npm:@algolia/cache-in-memory
	Version			       4.20.0
	--------------------------------------------------
	License Concluded	 MIT
	Name			         npm:@algolia/client-account
	Version			       4.20.0
	--------------------------------------------------
...
```
