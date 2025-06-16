# Changelog

## [2.0.0](https://github.com/Meniole/daemon-merging/compare/v1.0.0...v2.0.0) (2025-06-16)


### ⚠ BREAKING CHANGES

* removed database and scrap GitHub organizations and repos
* changed configuration to take a repo list

### Features

* added configuration generation script ([910811d](https://github.com/Meniole/daemon-merging/commit/910811df63ae916b2539eb016f87ed5694f57a27))
* added schema validation workflow ([fdffadb](https://github.com/Meniole/daemon-merging/commit/fdffadbb96638ba41a863285e85fe12e45391749))
* added schema validation workflow ([447f421](https://github.com/Meniole/daemon-merging/commit/447f4215c8fffeb07e86f6c025f649ec1feb30e0))
* added summary ([125f313](https://github.com/Meniole/daemon-merging/commit/125f31304bf94a1928f05490d48e5fb1dc0bf66e))
* changed configuration for repo watch ([58182e6](https://github.com/Meniole/daemon-merging/commit/58182e6b27fe286f29e63683855ee632c088dca9))
* changed configuration to take a repo list ([4cba61c](https://github.com/Meniole/daemon-merging/commit/4cba61c4351f4d61d1c7daf6cdb37b8594f42428))
* database update step ([5bad80a](https://github.com/Meniole/daemon-merging/commit/5bad80a8049890dcf16a5661caadfdacc89fdf2b))
* formatting checks ([4ee151c](https://github.com/Meniole/daemon-merging/commit/4ee151ca05e8c6af064b90aaacaf5785b68600df))
* job summary ([0eddb9d](https://github.com/Meniole/daemon-merging/commit/0eddb9df1ee2bc22751a0b80c4dd6aace640f14b))
* job summary ([e0f4b64](https://github.com/Meniole/daemon-merging/commit/e0f4b64ad78073dd270b306b5a3fc1eda41c0f76))
* pull requests are automatically merged based on their activity ([8da60bb](https://github.com/Meniole/daemon-merging/commit/8da60bb8871921d96943948956bc0ae903bee3b6))
* removed database and scrap GitHub organizations and repos ([cba2f9f](https://github.com/Meniole/daemon-merging/commit/cba2f9f575551e7191b09b36207d771e6b2100ca))
* schema validation ([425758a](https://github.com/Meniole/daemon-merging/commit/425758a37097b5f2f153dc8895912e32b7d85228))
* SDK and command interface ([ab95741](https://github.com/Meniole/daemon-merging/commit/ab95741fbce345e71e801eeadfabedf3a0a222ec))
* set db to be sqlite ([2dbe73b](https://github.com/Meniole/daemon-merging/commit/2dbe73be10f9ae436050f6b3626890db847c166c))
* used ubiquity's knip-reporter ([e7710f4](https://github.com/Meniole/daemon-merging/commit/e7710f4195b2116f530934bff3d66717f770c410))
* used ubiquity's knip-reporter ([cc77be6](https://github.com/Meniole/daemon-merging/commit/cc77be6e1d4196b0514fc5f5848c0aeb01426a64))


### Bug Fixes

* add environment ([a9079f9](https://github.com/Meniole/daemon-merging/commit/a9079f9e1c43fd1fa32f20407e6e0a2a05372a39))
* add environment ([2fbe7b1](https://github.com/Meniole/daemon-merging/commit/2fbe7b1aec710cc17239b6137bbc8e62e49655e6))
* bumped SDK and added bot event skip in manifest.json ([b0689c9](https://github.com/Meniole/daemon-merging/commit/b0689c90015200fb0f57274fdadbceadea14670d))
* bumped SDK and added bot event skip in manifest.json ([5a77cc5](https://github.com/Meniole/daemon-merging/commit/5a77cc53c61062a83bf979b05c2b71d05e5ffba4))
* changed approval requirement check to use the configuration ([e1f50e9](https://github.com/Meniole/daemon-merging/commit/e1f50e95576f81ce01196bbdc0890b0617bf23df))
* changed summary output ([dc847c1](https://github.com/Meniole/daemon-merging/commit/dc847c1699c40f3f44a7b8482435d5fd9e838844))
* **config:** add descriptions to JSON schema properties ([4298993](https://github.com/Meniole/daemon-merging/commit/42989936d8a7092e275e818419d7f0a74c885978))
* **config:** add descriptions to JSON schema properties ([69c1ced](https://github.com/Meniole/daemon-merging/commit/69c1cedb036442a86ebf774ec7e6b865c3728186))
* console log ([43f30d4](https://github.com/Meniole/daemon-merging/commit/43f30d4de3bdc2c0e0ab571936faa3cca260a0c7))
* contributor approvals ([4eae211](https://github.com/Meniole/daemon-merging/commit/4eae211a01ed1b6a07ac1ef625d1402da1636cd7))
* contributor's pull-requests do not get merged automatically ([b71ef15](https://github.com/Meniole/daemon-merging/commit/b71ef15eb2fff662f83bf264b052d7f300bd6c46))
* cross-env ([e8c7724](https://github.com/Meniole/daemon-merging/commit/e8c7724b23bc2763f1f8bbb5b9aa91cf1bfd5078))
* cross-env ([b27aad9](https://github.com/Meniole/daemon-merging/commit/b27aad93fd6f4f55287f7247c9fee68524c10d6e))
* default org is not handled at pull-request check stage ([0980040](https://github.com/Meniole/daemon-merging/commit/09800408ff6c07e50e001ebf8b5f45988a6cc0eb))
* filter reviews by approved author_association ([286f1b1](https://github.com/Meniole/daemon-merging/commit/286f1b1fcc7da02a50f6c0caf1854870eee0f36d))
* fixed event manifest.json ([6689f55](https://github.com/Meniole/daemon-merging/commit/6689f55420bc88a79a18da4983e9ebd6c9535752))
* fixed event manifest.json ([082bddd](https://github.com/Meniole/daemon-merging/commit/082bddd7a8f3278d343c102b1fcdd7269ce5a91d))
* fixed imports within main ([bb001cf](https://github.com/Meniole/daemon-merging/commit/bb001cf3204593a79b2d214941940a9a44675c00))
* formatting and deploy ([bd2f03e](https://github.com/Meniole/daemon-merging/commit/bd2f03e829444555800b3c26c6708ef22e569db2))
* knip ([14ad597](https://github.com/Meniole/daemon-merging/commit/14ad597fbe8444a640d7472bd2f0a4be94cff10c))
* manifest name ([0004a4b](https://github.com/Meniole/daemon-merging/commit/0004a4b54c5f601c6c994d0226e9403953c00d76))
* manifest name ([a2b901c](https://github.com/Meniole/daemon-merging/commit/a2b901c5fa6da976bc117f36406b212e827fe91b))
* removed space in additional org in query search ([df70e07](https://github.com/Meniole/daemon-merging/commit/df70e0794787cda05554a157c3d73999a0df11fc))
* set repo target to null if none is provided ([6b5cfbf](https://github.com/Meniole/daemon-merging/commit/6b5cfbfc406ea581c5790b705631ad3bdbbb20a7))
* setting default owner when monitor is empty ([c451dfa](https://github.com/Meniole/daemon-merging/commit/c451dfa1a87deb4130262f5c8efbac86ca5eddfb))
* workflow for CRON and watch issues ([b1fa6a1](https://github.com/Meniole/daemon-merging/commit/b1fa6a1a5745e552191f7e764484dd268061f102))

## 1.0.0 (2024-07-29)

### Features

- database update step ([5bad80a](https://github.com/ubiquibot/automated-merging/commit/5bad80a8049890dcf16a5661caadfdacc89fdf2b))
- set db to be sqlite ([2dbe73b](https://github.com/ubiquibot/automated-merging/commit/2dbe73be10f9ae436050f6b3626890db847c166c))

### Bug Fixes

- changed approval requirement check to use the configuration ([e1f50e9](https://github.com/ubiquibot/automated-merging/commit/e1f50e95576f81ce01196bbdc0890b0617bf23df))
- fixed imports within main ([bb001cf](https://github.com/ubiquibot/automated-merging/commit/bb001cf3204593a79b2d214941940a9a44675c00))
