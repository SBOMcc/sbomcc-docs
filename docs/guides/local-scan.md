---
sidebar_position: 1
---

# Parse a Single SBOM

To parse a single SBOM file, we will use the `-f` or `--file` option to specify the SBOM file to parse.

```bash
$ sbomcc -f mock/spdx.json
sbom.cc v0.0.3

SPDX Version            SPDX-2.3
Packages
        Files Analyzed          #f
        Name                    com.github.SBOMcc/sbomcc-docs
        SPDX ID                 SPDXRef-com.github.SBOMcc-sbomcc-docs
        Version
        External Refs
                Reference Type          purl
                Reference Category      PACKAGE-MANAGER
                Reference Locator       pkg:github/SBOMcc/sbomcc-docs
        Download Location       git+https://github.com/SBOMcc/sbomcc-docs
        Supplier                NOASSERTION
        --------------------------------------------------
        External Refs
                Reference Type          purl
                Reference Category      PACKAGE-MANAGER
                Reference Locator       pkg:npm/%40algolia/autocomplete-core@1.9.3
        License Concluded       MIT
        Files Analyzed          #f
        Name                    npm:@algolia/autocomplete-core
        SPDX ID                 SPDXRef-npm-algolia-autocomplete-core-1.9.3
        Version                 1.9.3
        Download Location       NOASSERTION
        Supplier                NOASSERTION
        --------------------------------------------------
        External Refs
                Reference Type          purl
                Reference Category      PACKAGE-MANAGER
                Reference Locator       pkg:npm/%40algolia/autocomplete-plugin-algolia-insights@1.9.3
        License Concluded       MIT
        Files Analyzed          #f
        Name                    npm:@algolia/autocomplete-plugin-algolia-insights
        SPDX ID                 SPDXRef-npm-algolia-autocomplete-plugin-algolia-insights-1.9.3
        Version                 1.9.3
        Download Location       NOASSERTION
        Supplier                NOASSERTION
        --------------------------------------------------
        External Refs
                Reference Type          purl
                Reference Category      PACKAGE-MANAGER
                Reference Locator       pkg:npm/%40algolia/autocomplete-preset-algolia@1.9.3
        License Concluded       MIT
        Files Analyzed          #f
        Name                    npm:@algolia/autocomplete-preset-algolia
        SPDX ID                 SPDXRef-npm-algolia-autocomplete-preset-algolia-1.9.3
        Version                 1.9.3
        Download Location       NOASSERTION
        Supplier                NOASSERTION
        --------------------------------------------------
        External Refs
                Reference Type          purl
                Reference Category      PACKAGE-MANAGER
                Reference Locator       pkg:npm/%40algolia/autocomplete-shared@1.9.3
        License Concluded       MIT
        Files Analyzed          #f
        Name                    npm:@algolia/autocomplete-shared
        SPDX ID                 SPDXRef-npm-algolia-autocomplete-shared-1.9.3
        Version                 1.9.3
        Download Location       NOASSERTION
        Supplier                NOASSERTION
        --------------------------------------------------
        External Refs
                Reference Type          purl
                Reference Category      PACKAGE-MANAGER
                Reference Locator       pkg:npm/%40algolia/cache-browser-local-storage@4.20.0
        License Concluded       MIT
        Files Analyzed          #f
        Name                    npm:@algolia/cache-browser-local-storage
        SPDX ID                 SPDXRef-npm-algolia-cache-browser-local-storage-4.20.0
        Version                 4.20.0
        Download Location       NOASSERTION
        Supplier                NOASSERTION
        --------------------------------------------------
        External Refs
                Reference Type          purl
                Reference Category      PACKAGE-MANAGER
                Reference Locator       pkg:npm/%40algolia/cache-common@4.20.0
        License Concluded       MIT
        Files Analyzed          #f
        Name                    npm:@algolia/cache-common
        SPDX ID                 SPDXRef-npm-algolia-cache-common-4.20.0
        Version                 4.20.0
        Download Location       NOASSERTION
        Supplier                NOASSERTION
        --------------------------------------------------
        External Refs
                Reference Type          purl
                Reference Category      PACKAGE-MANAGER
                Reference Locator       pkg:npm/%40algolia/cache-in-memory@4.20.0
        License Concluded       MIT
        Files Analyzed          #f
        Name                    npm:@algolia/cache-in-memory
        SPDX ID                 SPDXRef-npm-algolia-cache-in-memory-4.20.0
        Version                 4.20.0
        Download Location       NOASSERTION
        Supplier                NOASSERTION
        --------------------------------------------------
...
```
