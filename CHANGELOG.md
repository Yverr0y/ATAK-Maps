## 1.0.0 (2026-10-31)

### ⚠ BREAKING CHANGES

* **release:** every map file and display name changed in v1.10.1 (#100). ATAK keys offline caches by map name, so old <name>.sqlite caches are orphaned; re-download offline tiles.
* every map file and display name changed. Old offline caches (<name>.sqlite) are orphaned; re-download tiles after updating.

### Features

* add BC Wildfire Overlay source ([#76](https://github.com/Yverr0y/ATAK-Maps/issues/76)) ([d6c4bf9](https://github.com/Yverr0y/ATAK-Maps/commit/d6c4bf9f40ced3fbda8aefd0675c91a47dee93c9))
* add Bing Satellite (aerial-only) map source ([#67](https://github.com/Yverr0y/ATAK-Maps/issues/67)) ([5fefc27](https://github.com/Yverr0y/ATAK-Maps/commit/5fefc27150dc87c3c7ee3cde254e3a5ad47bdc55)), closes [#64](https://github.com/Yverr0y/ATAK-Maps/issues/64)
* add BLM land ownership (SMA) map sources ([#80](https://github.com/Yverr0y/ATAK-Maps/issues/80)) ([39b2eda](https://github.com/Yverr0y/ATAK-Maps/commit/39b2edaf4ddb426c4e6df3484f493e7338db49b1))
* add CI workflows for mapvalidator, remove standalone script ([f78a785](https://github.com/Yverr0y/ATAK-Maps/commit/f78a785dc4e78add8a185605fbd198cb50e17e70))
* add deep validation script with liveness probing ([3675175](https://github.com/Yverr0y/ATAK-Maps/commit/3675175f013fdd4c2dd32a384d513e5d096e54c3))
* add map validation & liveness monitoring ([#70](https://github.com/Yverr0y/ATAK-Maps/issues/70)) ([974c2a1](https://github.com/Yverr0y/ATAK-Maps/commit/974c2a1ccb606a40fddc82fb6851de6244a28f93))
* add mapvalidator package with deep XML validation and liveness probing ([185a8eb](https://github.com/Yverr0y/ATAK-Maps/commit/185a8eb9757d09db1b98aaaf3a37ba89fbc7677c))
* add Ordnance Survey map layers (Great Britain) ([#83](https://github.com/Yverr0y/ATAK-Maps/issues/83)) ([ddba21d](https://github.com/Yverr0y/ATAK-Maps/commit/ddba21d0d664ede6552b6b97edcaf9a0a4de674a)), closes [#68](https://github.com/Yverr0y/ATAK-Maps/issues/68)
* add soft-block detection, multi-region probing, and remove dead map sources ([66be333](https://github.com/Yverr0y/ATAK-Maps/commit/66be3339976b399b9b65546beb8eb485b1fe8661))
* add XSD schema for MOBAC XML map validation ([9da31a9](https://github.com/Yverr0y/ATAK-Maps/commit/9da31a993c14da2fe7e741d5fa67d743ab486516))
* Adding Polish Ortho Maps ([7c2d25e](https://github.com/Yverr0y/ATAK-Maps/commit/7c2d25e62b888356332878a878a91cbe42115ebb))
* Adding Polish Ortho Maps ([f999740](https://github.com/Yverr0y/ATAK-Maps/commit/f99974041390d40975636890b312599422d4989b))
* BasemapDE - German government topographical map ([#59](https://github.com/Yverr0y/ATAK-Maps/issues/59)) ([2c1648d](https://github.com/Yverr0y/ATAK-Maps/commit/2c1648d3252da403e760b15a4aa2a22c4b6d1519))
* bundle all maps as an importable ATAK data package ([#86](https://github.com/Yverr0y/ATAK-Maps/issues/86)) ([c71a2ff](https://github.com/Yverr0y/ATAK-Maps/commit/c71a2ff97bc77a7274457c99a8195632a9f8cfa2))
* clarify release workflow ([#60](https://github.com/Yverr0y/ATAK-Maps/issues/60)) ([526c288](https://github.com/Yverr0y/ATAK-Maps/commit/526c288b6f1f85384be32ab6b3edf4cf704dfba5))
* GitHub Pages site with per-map QR codes and Add-to-ATAK ([#84](https://github.com/Yverr0y/ATAK-Maps/issues/84)) ([4935b03](https://github.com/Yverr0y/ATAK-Maps/commit/4935b0335a92c69643d7b9367d7a0e7cd55c65bf)), closes [#81](https://github.com/Yverr0y/ATAK-Maps/issues/81)
* **google:** add hybrid no-POI, bike and transit layers; short clear names ([#97](https://github.com/Yverr0y/ATAK-Maps/issues/97)) ([843d54b](https://github.com/Yverr0y/ATAK-Maps/commit/843d54bfb5c51ebf79e8e820c2df97d08e459ba8))
* **maps:** FAA charts, OpenRailwayMap and USGS Hydro; TAK Aware compatibility ([#109](https://github.com/Yverr0y/ATAK-Maps/issues/109)) ([637cb63](https://github.com/Yverr0y/ATAK-Maps/commit/637cb637bff54688bd43626442e632e8c318b933))
* redesign the Maps catalog, landing page, and README ([#88](https://github.com/Yverr0y/ATAK-Maps/issues/88)) ([83f56ee](https://github.com/Yverr0y/ATAK-Maps/commit/83f56eeb8d65c03f33a1094c726e584f7d7fdcab))
* Refine XML map source by removing redundant comment in PL Geoportal Ortofoto EPSG3857 configuration for improved clarity. ([f4440b3](https://github.com/Yverr0y/ATAK-Maps/commit/f4440b35efe1272fda07edac6b67c24d4eef015a))
* Remove broken FEMA NFHL XML layers and introduce new Flood Hazard Zones WMS configuration ([5c721b3](https://github.com/Yverr0y/ATAK-Maps/commit/5c721b3c0ea3b894fe1e9d934bc3ab91e68230f5))
* **site:** new site with a live map explorer ([#104](https://github.com/Yverr0y/ATAK-Maps/issues/104)) ([065f46d](https://github.com/Yverr0y/ATAK-Maps/commit/065f46da585864b9a9df2772ca77c689314e92bf))
* **validator:** ATAK harness that tests maps exactly as ATAK fetches them ([#101](https://github.com/Yverr0y/ATAK-Maps/issues/101)) ([ac29eda](https://github.com/Yverr0y/ATAK-Maps/commit/ac29eda62ca0d26b3cb68dc27b0044840008dda1))
* **validator:** per-map health for the site + real maxZoom for 2 maps ([#103](https://github.com/Yverr0y/ATAK-Maps/issues/103)) ([bb8e6da](https://github.com/Yverr0y/ATAK-Maps/commit/bb8e6dafd41b031dd265c0dbfbae79d33321665b))

### Bug Fixes

* Add catch-all release rule for non-conventional commits ([2b78a77](https://github.com/Yverr0y/ATAK-Maps/commit/2b78a779f9c3af8d48332fe0beae1dba1a9b6c77))
* address linter failures and Copilot review feedback ([d4252c6](https://github.com/Yverr0y/ATAK-Maps/commit/d4252c6dbe090a9000991653b2c797b1499573fb))
* address PR review comments ([537b23d](https://github.com/Yverr0y/ATAK-Maps/commit/537b23df6af0ee55ffca0e26a6314245d7708ade))
* **bc-wildfire:** conform merged source to schema and conventions ([#82](https://github.com/Yverr0y/ATAK-Maps/issues/82)) ([767d630](https://github.com/Yverr0y/ATAK-Maps/commit/767d630970780ec567d5dfe6914a095f5a1bee06)), closes [#76](https://github.com/Yverr0y/ATAK-Maps/issues/76)
* **ci:** checkout latest master tip in release workflow ([330f36c](https://github.com/Yverr0y/ATAK-Maps/commit/330f36c0d19a6a568dc3745cbd4f4ce4e023e682))
* **ci:** disable npm plugin & grant issues permission ([b612196](https://github.com/Yverr0y/ATAK-Maps/commit/b612196b6801b04da4f1eae881807bf512177293))
* clarify docs phrasing ([#50](https://github.com/Yverr0y/ATAK-Maps/issues/50)) ([ca0f758](https://github.com/Yverr0y/ATAK-Maps/commit/ca0f7584d22388ec7ba73328cf7212227a3af385))
* correct XML issues found by mapvalidator ([fd779db](https://github.com/Yverr0y/ATAK-Maps/commit/fd779dbfb7786d3f83fd2f640b3a130a5f8eb5cc))
* **deps:** bump the python group with 5 updates ([#114](https://github.com/Yverr0y/ATAK-Maps/issues/114)) ([e79fe1b](https://github.com/Yverr0y/ATAK-Maps/commit/e79fe1bbc5e52cfa3a12c26ed28d0b80ccd11afb))
* **deps:** Pillow 13 (41 Dependabot alerts); pin all actions to commits ([#108](https://github.com/Yverr0y/ATAK-Maps/issues/108)) ([40d7899](https://github.com/Yverr0y/ATAK-Maps/commit/40d7899901839954af71217e076fd4d63c628251))
* disable isort in super-linter, keep black for formatting ([42173d4](https://github.com/Yverr0y/ATAK-Maps/commit/42173d411672f98bf1f88bd952663013b72cd63c))
* disable JSCPD and configure isort in super-linter ([53f2c04](https://github.com/Yverr0y/ATAK-Maps/commit/53f2c0496b9079e60f984cd76a96291cae411cf8))
* Harden release pipeline against history rewrites ([3644396](https://github.com/Yverr0y/ATAK-Maps/commit/36443963efb45efe33fcc0f8a69305b16e1b3f01))
* **health:** failed issue calls fail the run; health is saved first ([#111](https://github.com/Yverr0y/ATAK-Maps/issues/111)) ([44e959a](https://github.com/Yverr0y/ATAK-Maps/commit/44e959a9c29f436378d542ca52a4d73128dc67c0))
* import per-map XML from GitHub Pages (application/xml), not raw ([#85](https://github.com/Yverr0y/ATAK-Maps/issues/85)) ([2a0c4af](https://github.com/Yverr0y/ATAK-Maps/commit/2a0c4afdc16fc43c007b590eae9ed9fab6452dc2))
* **maps:** NAIP from USGS The National Map ([#115](https://github.com/Yverr0y/ATAK-Maps/issues/115)) ([dcc5d5a](https://github.com/Yverr0y/ATAK-Maps/commit/dcc5d5a5f54de9f0a35374e8d655368bcd87a614)), closes [#113](https://github.com/Yverr0y/ATAK-Maps/issues/113)
* minor update to force a release. ([f0ba377](https://github.com/Yverr0y/ATAK-Maps/commit/f0ba3770cfe65b6f4eeb0902ee7acafd5772cc9c))
* **release:** breaking commits make a major release ([#102](https://github.com/Yverr0y/ATAK-Maps/issues/102)) ([7e9e918](https://github.com/Yverr0y/ATAK-Maps/commit/7e9e9189c972d2966204b0e986e32c9d331d0064))
* Remove redundant comment in PL Geoportal Ortofoto EPSG3857 XML configuration for improved clarity ([1694bcb](https://github.com/Yverr0y/ATAK-Maps/commit/1694bcb0b69667992f39e01db122c3d1f712793b))
* rename basemapDE files to remove spaces in filenames ([8d23b1e](https://github.com/Yverr0y/ATAK-Maps/commit/8d23b1ebd3117cdccd07eacc7619fd1d3c0c24d0))
* Replace install diagram with simplified ATAK Import flow ([de4d09a](https://github.com/Yverr0y/ATAK-Maps/commit/de4d09a9795a883e18d7a2342af5e1d43661dbf3))
* resolve remaining CI lint failures ([cd6b43d](https://github.com/Yverr0y/ATAK-Maps/commit/cd6b43d1ea80857e6c0ce545b6d4c64f36f8eb85))
* **security:** update docs dependency and reporting policy ([#95](https://github.com/Yverr0y/ATAK-Maps/issues/95)) ([d610afd](https://github.com/Yverr0y/ATAK-Maps/commit/d610afd941539f5a2bb4deafa0518367658192b6))
* Simplify semantic-release configuration and update workflow comments for clarity ([07cdb07](https://github.com/Yverr0y/ATAK-Maps/commit/07cdb074edf84bd0d5c0b9fe9fa24eb1505f1f2c))
* **site:** explorer opens dark for returning visitors; clearer Fix a problem ([#106](https://github.com/Yverr0y/ATAK-Maps/issues/106)) ([149bc5b](https://github.com/Yverr0y/ATAK-Maps/commit/149bc5b4aa1e8b522abdcc7b65e4a88790ea90fb))
* **ui:** tap-to-enlarge QR lightbox; bigger scannable README QR ([#89](https://github.com/Yverr0y/ATAK-Maps/issues/89)) ([93c6cf2](https://github.com/Yverr0y/ATAK-Maps/commit/93c6cf2a45609b2e275e07270113277faa1d591d))
* Update asset label in semantic-release configuration to include dynamic versioning for improved clarity in releases ([2df3f63](https://github.com/Yverr0y/ATAK-Maps/commit/2df3f631e821ee7b00f0b65d5b32d8f4a7baf700))
* update OpenSeaMap endpoints and document map tips ([df4ff0f](https://github.com/Yverr0y/ATAK-Maps/commit/df4ff0f2120ca48ca046c8983d4e60b517cbfafe))
* Update semantic-release configuration to rename ZIP files dynamically and improve asset labeling for GitHub releases ([433c0e6](https://github.com/Yverr0y/ATAK-Maps/commit/433c0e67de352aa4f4bc8d0cfdb759180167bf15))
* Updated basemapDE to use a WMTS service ([#93](https://github.com/Yverr0y/ATAK-Maps/issues/93)) ([5e5cca0](https://github.com/Yverr0y/ATAK-Maps/commit/5e5cca0e4a84e9da8d2c4f64865df8e73d1b0483))

### Code Refactoring

* rename all maps to short names and fix broken sources ([#100](https://github.com/Yverr0y/ATAK-Maps/issues/100)) ([81bded0](https://github.com/Yverr0y/ATAK-Maps/commit/81bded019d027ebc8d1bccef35aea847fe1257e1))

## [2.3.1](https://github.com/joshuafuller/ATAK-Maps/compare/v2.3.0...v2.3.1) (2026-10-31)

### Bug Fixes

* **deps:** bump the python group with 5 updates ([#114](https://github.com/joshuafuller/ATAK-Maps/issues/114)) ([e79fe1b](https://github.com/joshuafuller/ATAK-Maps/commit/e79fe1bbc5e52cfa3a12c26ed28d0b80ccd11afb))
* **health:** failed issue calls fail the run; health is saved first ([#111](https://github.com/joshuafuller/ATAK-Maps/issues/111)) ([44e959a](https://github.com/joshuafuller/ATAK-Maps/commit/44e959a9c29f436378d542ca52a4d73128dc67c0))
* **maps:** NAIP from USGS The National Map ([#115](https://github.com/joshuafuller/ATAK-Maps/issues/115)) ([dcc5d5a](https://github.com/joshuafuller/ATAK-Maps/commit/dcc5d5a5f54de9f0a35374e8d655368bcd87a614)), closes [#113](https://github.com/joshuafuller/ATAK-Maps/issues/113)

## [2.3.0](https://github.com/joshuafuller/ATAK-Maps/compare/v2.2.0...v2.3.0) (2026-10-31)

### Features

* **maps:** FAA charts, OpenRailwayMap and USGS Hydro; TAK Aware compatibility ([#109](https://github.com/joshuafuller/ATAK-Maps/issues/109)) ([637cb63](https://github.com/joshuafuller/ATAK-Maps/commit/637cb637bff54688bd43626442e632e8c318b933))

### Bug Fixes

* **deps:** Pillow 13 (41 Dependabot alerts); pin all actions to commits ([#108](https://github.com/joshuafuller/ATAK-Maps/issues/108)) ([40d7899](https://github.com/joshuafuller/ATAK-Maps/commit/40d7899901839954af71217e076fd4d63c628251))

## [2.2.0](https://github.com/joshuafuller/ATAK-Maps/compare/v2.1.0...v2.2.0) (2026-10-31)

### Features

* **site:** new site with a live map explorer ([#104](https://github.com/joshuafuller/ATAK-Maps/issues/104)) ([065f46d](https://github.com/joshuafuller/ATAK-Maps/commit/065f46da585864b9a9df2772ca77c689314e92bf))

### Bug Fixes

* **site:** explorer opens dark for returning visitors; clearer Fix a problem ([#106](https://github.com/joshuafuller/ATAK-Maps/issues/106)) ([149bc5b](https://github.com/joshuafuller/ATAK-Maps/commit/149bc5b4aa1e8b522abdcc7b65e4a88790ea90fb))

## [2.1.0](https://github.com/joshuafuller/ATAK-Maps/compare/v2.0.0...v2.1.0) (2026-10-31)

### Features

* **validator:** per-map health for the site + real maxZoom for 2 maps ([#103](https://github.com/joshuafuller/ATAK-Maps/issues/103)) ([bb8e6da](https://github.com/joshuafuller/ATAK-Maps/commit/bb8e6dafd41b031dd265c0dbfbae79d33321665b))

## [2.0.0](https://github.com/joshuafuller/ATAK-Maps/compare/v1.11.0...v2.0.0) (2026-10-30)

### ⚠ BREAKING CHANGES

* **release:** every map file and display name changed in v1.10.1 (#100). ATAK keys offline caches by map name, so old <name>.sqlite caches are orphaned; re-download offline tiles.

### Bug Fixes

* **release:** breaking commits make a major release ([#102](https://github.com/joshuafuller/ATAK-Maps/issues/102)) ([7e9e918](https://github.com/joshuafuller/ATAK-Maps/commit/7e9e9189c972d2966204b0e986e32c9d331d0064))

# [1.11.0](https://github.com/joshuafuller/ATAK-Maps/compare/v1.10.1...v1.11.0) (2026-10-30)


### Features

* **validator:** ATAK harness that tests maps exactly as ATAK fetches them ([#101](https://github.com/joshuafuller/ATAK-Maps/issues/101)) ([ac29eda](https://github.com/joshuafuller/ATAK-Maps/commit/ac29eda62ca0d26b3cb68dc27b0044840008dda1))

## [1.10.1](https://github.com/joshuafuller/ATAK-Maps/compare/v1.10.0...v1.10.1) (2026-10-30)


* refactor!: rename all maps to short names and fix broken sources ([#100](https://github.com/joshuafuller/ATAK-Maps/issues/100)) ([81bded0](https://github.com/joshuafuller/ATAK-Maps/commit/81bded019d027ebc8d1bccef35aea847fe1257e1))


### BREAKING CHANGES

* every map file and display name changed. Old offline caches (<name>.sqlite) are orphaned; re-download tiles after updating.

# [1.10.0](https://github.com/joshuafuller/ATAK-Maps/compare/v1.9.0...v1.10.0) (2026-10-30)


### Features

* **google:** add hybrid no-POI, bike and transit layers; short clear names ([#97](https://github.com/joshuafuller/ATAK-Maps/issues/97)) ([843d54b](https://github.com/joshuafuller/ATAK-Maps/commit/843d54bfb5c51ebf79e8e820c2df97d08e459ba8))

# [1.9.0](https://github.com/joshuafuller/ATAK-Maps/compare/v1.8.0...v1.9.0) (2026-10-13)


### Bug Fixes

* import per-map XML from GitHub Pages (application/xml), not raw ([#85](https://github.com/joshuafuller/ATAK-Maps/issues/85)) ([2a0c4af](https://github.com/joshuafuller/ATAK-Maps/commit/2a0c4afdc16fc43c007b590eae9ed9fab6452dc2))
* **security:** update docs dependency and reporting policy ([#95](https://github.com/joshuafuller/ATAK-Maps/issues/95)) ([d610afd](https://github.com/joshuafuller/ATAK-Maps/commit/d610afd941539f5a2bb4deafa0518367658192b6))
* **ui:** tap-to-enlarge QR lightbox; bigger scannable README QR ([#89](https://github.com/joshuafuller/ATAK-Maps/issues/89)) ([93c6cf2](https://github.com/joshuafuller/ATAK-Maps/commit/93c6cf2a45609b2e275e07270113277faa1d591d))
* update OpenSeaMap endpoints and document map tips ([df4ff0f](https://github.com/joshuafuller/ATAK-Maps/commit/df4ff0f2120ca48ca046c8983d4e60b517cbfafe))
* Updated basemapDE to use a WMTS service ([#93](https://github.com/joshuafuller/ATAK-Maps/issues/93)) ([5e5cca0](https://github.com/joshuafuller/ATAK-Maps/commit/5e5cca0e4a84e9da8d2c4f64865df8e73d1b0483))


### Features

* bundle all maps as an importable ATAK data package ([#86](https://github.com/joshuafuller/ATAK-Maps/issues/86)) ([c71a2ff](https://github.com/joshuafuller/ATAK-Maps/commit/c71a2ff97bc77a7274457c99a8195632a9f8cfa2))
* redesign the Maps catalog, landing page, and README ([#88](https://github.com/joshuafuller/ATAK-Maps/issues/88)) ([83f56ee](https://github.com/joshuafuller/ATAK-Maps/commit/83f56eeb8d65c03f33a1094c726e584f7d7fdcab))

# [1.8.0](https://github.com/joshuafuller/ATAK-Maps/compare/v1.7.1...v1.8.0) (2026-07-13)


### Bug Fixes

* **bc-wildfire:** conform merged source to schema and conventions ([#82](https://github.com/joshuafuller/ATAK-Maps/issues/82)) ([767d630](https://github.com/joshuafuller/ATAK-Maps/commit/767d630970780ec567d5dfe6914a095f5a1bee06)), closes [#76](https://github.com/joshuafuller/ATAK-Maps/issues/76)


### Features

* add BC Wildfire Overlay source ([#76](https://github.com/joshuafuller/ATAK-Maps/issues/76)) ([d6c4bf9](https://github.com/joshuafuller/ATAK-Maps/commit/d6c4bf9f40ced3fbda8aefd0675c91a47dee93c9))
* add BLM land ownership (SMA) map sources ([#80](https://github.com/joshuafuller/ATAK-Maps/issues/80)) ([39b2eda](https://github.com/joshuafuller/ATAK-Maps/commit/39b2edaf4ddb426c4e6df3484f493e7338db49b1))
* add Ordnance Survey map layers (Great Britain) ([#83](https://github.com/joshuafuller/ATAK-Maps/issues/83)) ([ddba21d](https://github.com/joshuafuller/ATAK-Maps/commit/ddba21d0d664ede6552b6b97edcaf9a0a4de674a)), closes [#68](https://github.com/joshuafuller/ATAK-Maps/issues/68)
* GitHub Pages site with per-map QR codes and Add-to-ATAK ([#84](https://github.com/joshuafuller/ATAK-Maps/issues/84)) ([4935b03](https://github.com/joshuafuller/ATAK-Maps/commit/4935b0335a92c69643d7b9367d7a0e7cd55c65bf)), closes [#81](https://github.com/joshuafuller/ATAK-Maps/issues/81)

## [1.7.1](https://github.com/joshuafuller/ATAK-Maps/compare/v1.7.0...v1.7.1) (2026-03-13)


### Bug Fixes

* **ci:** checkout latest master tip in release workflow ([330f36c](https://github.com/joshuafuller/ATAK-Maps/commit/330f36c0d19a6a568dc3745cbd4f4ce4e023e682))

# [1.7.0](https://github.com/joshuafuller/ATAK-Maps/compare/v1.6.0...v1.7.0) (2026-03-13)


### Bug Fixes

* address linter failures and Copilot review feedback ([d4252c6](https://github.com/joshuafuller/ATAK-Maps/commit/d4252c6dbe090a9000991653b2c797b1499573fb))
* correct XML issues found by mapvalidator ([fd779db](https://github.com/joshuafuller/ATAK-Maps/commit/fd779dbfb7786d3f83fd2f640b3a130a5f8eb5cc))
* disable isort in super-linter, keep black for formatting ([42173d4](https://github.com/joshuafuller/ATAK-Maps/commit/42173d411672f98bf1f88bd952663013b72cd63c))
* disable JSCPD and configure isort in super-linter ([53f2c04](https://github.com/joshuafuller/ATAK-Maps/commit/53f2c0496b9079e60f984cd76a96291cae411cf8))
* resolve remaining CI lint failures ([cd6b43d](https://github.com/joshuafuller/ATAK-Maps/commit/cd6b43d1ea80857e6c0ce545b6d4c64f36f8eb85))


### Features

* add CI workflows for mapvalidator, remove standalone script ([f78a785](https://github.com/joshuafuller/ATAK-Maps/commit/f78a785dc4e78add8a185605fbd198cb50e17e70))
* add deep validation script with liveness probing ([3675175](https://github.com/joshuafuller/ATAK-Maps/commit/3675175f013fdd4c2dd32a384d513e5d096e54c3))
* add map validation & liveness monitoring ([#70](https://github.com/joshuafuller/ATAK-Maps/issues/70)) ([974c2a1](https://github.com/joshuafuller/ATAK-Maps/commit/974c2a1ccb606a40fddc82fb6851de6244a28f93))
* add mapvalidator package with deep XML validation and liveness probing ([185a8eb](https://github.com/joshuafuller/ATAK-Maps/commit/185a8eb9757d09db1b98aaaf3a37ba89fbc7677c))
* add soft-block detection, multi-region probing, and remove dead map sources ([66be333](https://github.com/joshuafuller/ATAK-Maps/commit/66be3339976b399b9b65546beb8eb485b1fe8661))

# [1.6.0](https://github.com/joshuafuller/ATAK-Maps/compare/v1.5.0...v1.6.0) (2026-03-13)


### Bug Fixes

* address PR review comments ([537b23d](https://github.com/joshuafuller/ATAK-Maps/commit/537b23df6af0ee55ffca0e26a6314245d7708ade))
* rename basemapDE files to remove spaces in filenames ([8d23b1e](https://github.com/joshuafuller/ATAK-Maps/commit/8d23b1ebd3117cdccd07eacc7619fd1d3c0c24d0))


### Features

* add XSD schema for MOBAC XML map validation ([9da31a9](https://github.com/joshuafuller/ATAK-Maps/commit/9da31a993c14da2fe7e741d5fa67d743ab486516))

# Changelog

## [1.5.0](https://github.com/joshuafuller/ATAK-Maps/compare/v1.4.1...v1.5.0) (2025-10-02)

### Features

* add Bing Satellite (aerial-only) map source ([#67](https://github.com/joshuafuller/ATAK-Maps/issues/67)) ([433733e](https://github.com/joshuafuller/ATAK-Maps/commit/433733e9fb161b32cd48ac1cfe6eb9b7c02b8386)), closes [#64](https://github.com/joshuafuller/ATAK-Maps/issues/64)

## [1.4.1](https://github.com/joshuafuller/ATAK-Maps/compare/v1.4.0...v1.4.1) (2025-05-20)

### Bug Fixes

* minor update to force a release ([5a388b8](https://github.com/joshuafuller/ATAK-Maps/commit/5a388b8))
* Update asset label in semantic-release configuration ([5f17164](https://github.com/joshuafuller/ATAK-Maps/commit/5f17164))

## [1.4.0](https://github.com/joshuafuller/ATAK-Maps/compare/v1.3.0...v1.4.0) (2025-05-20)

### Features

* BasemapDE - German government topographical map ([#59](https://github.com/joshuafuller/ATAK-Maps/issues/59)) ([040798a](https://github.com/joshuafuller/ATAK-Maps/commit/040798a))

### Bug Fixes

* Simplify semantic-release configuration ([7d7c60e](https://github.com/joshuafuller/ATAK-Maps/commit/7d7c60e))

## [1.3.0](https://github.com/joshuafuller/ATAK-Maps/compare/v1.2.1...v1.3.0) (2025-05-20)

### Features

* Remove broken FEMA NFHL XML layers and introduce new Flood Hazard Zones WMS configuration ([f4d5535](https://github.com/joshuafuller/ATAK-Maps/commit/f4d5535))
* Adding Polish Ortho Maps ([a889bc8](https://github.com/joshuafuller/ATAK-Maps/commit/a889bc8))

### Bug Fixes

* Update semantic-release configuration to rename ZIP files dynamically ([ca2be44](https://github.com/joshuafuller/ATAK-Maps/commit/ca2be44))
* Remove redundant comment in PL Geoportal Ortofoto EPSG3857 XML configuration ([f983afc](https://github.com/joshuafuller/ATAK-Maps/commit/f983afc))

## [1.2.1](https://github.com/joshuafuller/ATAK-Maps/compare/v1.2.0...v1.2.1) (2025-05-17)

### Bug Fixes

* clarify docs phrasing ([#50](https://github.com/joshuafuller/ATAK-Maps/issues/50)) ([d317f2e](https://github.com/joshuafuller/ATAK-Maps/commit/d317f2e722a202a25877c9ce0c17251e7f3cb240))
