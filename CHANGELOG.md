# Changelog

## [1.16.0](https://github.com/kevinthornodegard-sys/mcp-aiven/compare/v1.15.3...v1.16.0) (2026-09-14)


### Features

* adapt to new app service credential integration format ([#98](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/98)) ([3f19431](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/3f194313b30f957e8e33c9c7bf5d00b3babb6939))
* add aiven_application_build_logs_get tool ([#116](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/116)) ([0ecde0e](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/0ecde0e4a0e305c22684938e819bb1fbe71b4eea))
* add aiven_service_connection_info tool gated by allow_secrets ([#121](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/121)) ([73d8d3a](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/73d8d3a6ebfcb141ce5955f4fb042c986c7d79af))
* add CI and release github actions workflows, bump version to 1.0.0 ([67cf078](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/67cf07810a827419e07265b46f21865b9d12cc27))
* add docs search tool ([8d23507](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/8d23507915897b5281f2554c607455e00fd95209))
* add docs search tool ([e438093](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/e438093c2111b48383d15c06ce243deb9defe8d2))
* add observability headers and reasoning field to all tools ([df6b063](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/df6b063920aeb2664626fd4e033b7d0e87104b5a))
* add observability headers and reasoning field to all tools ([92a7548](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/92a75486473394f19eff152fa40a5ae50230bfd9))
* add opt-in Sentry integration for error tracking and logging ([#88](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/88)) ([1f56fa0](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/1f56fa04b22060d03080a764a5f52e46510dc784))
* add remote read_only support by query param [EVERSQL-1817] ([bc9bf99](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/bc9bf99e7f04dcb5141aa3fc0cacb64fa4de2180))
* add remote read_only support by query param [EVERSQL-1817] ([c661ba7](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/c661ba76a592496e6bcff4708c9b5a02b2dea310))
* add search/limit filtering to list tools ([#58](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/58)) ([b689924](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/b68992450216749dca98a2e378ceceb934b1fcc0))
* add server.json for mcp official registry ([#135](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/135)) ([4c86c63](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/4c86c63b3f12a434b0b5c4ddb5b00e34638fea03))
* add severity filter to service logs tool ([#99](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/99)) ([992617f](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/992617fdd10814ec0f0a5f484f6f4854811ba71b))
* add source label to docs search calls ([9837ae7](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/9837ae7d533bf3acf0781eaef49fd4c84a755388))
* add tools scoping to reduce context usage and improve performance ([#60](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/60)) ([8e3fccc](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/8e3fccc19ff3d4240ae19522d146ea40e289e66c))
* add write_allowlist to re-enable specific write tools in read-only mode ([#141](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/141)) ([2120184](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/21201847a91be8bfa307572c92ffa939a3cbb7cf))
* adopt semantic-release for automated versioning and npm publishing ([#67](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/67)) ([f4d0dad](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/f4d0dad2cf9d1b995a9bef9ac2ae966cdcfdb970))
* aiven apps [EVERSQL-1756] ([0dca156](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/0dca1560cad98293f90957f45f4987e25b4021f4))
* aiven apps [EVERSQL-1756] ([0ecfaf0](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/0ecfaf0c70f133b871a5ac86b89c375d5b43b4f7))
* aiven apps vpc ([a335a1f](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/a335a1f8bdac09c8bb6fd85c9ed2c3b05c5f0fbd))
* aiven apps vpc ([1b2b6e5](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/1b2b6e58bc64a8a1775daf9800c06c1906abba92))
* aiven remote mcp ([27f7802](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/27f7802fd691b1517a2ddad6e09557f40848f0e3))
* integrate security scan tool for inputs and outputs ([#131](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/131)) ([093195f](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/093195f70a55984217008b07cae1413664d28812))
* make MCP host URL configurable via MCP_HOST env var ([b210af0](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/b210af0a12a9a1590c6860772116341f92e659aa))
* make MCP host URL configurable via MCP_HOST env var ([951825b](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/951825b90a7ad8939ea5b0bf9ae0cf452d5f7f53))
* mcp maintenance mode ([#85](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/85)) ([45e52cf](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/45e52cf78bcdf0cd5d648a1ba5efd4861ba13cf8))
* mcp metrics headers ([3d5eb97](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/3d5eb9795477d22f48a8b8b8a7da45c9eb6a3d69))
* mcp metrics headers ([412bb28](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/412bb280723df0ef7245824e1e83634d5e11672d))
* mcp.aiven.live host ([92e8d3e](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/92e8d3ec5bea1af1352f8aae76fbb471bcc724da))
* migrate from semantic-release to release-please ([#70](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/70)) ([e6b744a](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/e6b744ae7eb2909e39a0ecf3c98ed1b70f925d12))
* modify destructive tools [EVERSQL-1812] ([#73](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/73)) ([a18593f](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/a18593f912c42b7ff1979f41f1bae02668f6f822))
* move pg read and write to use pg-editor/run-query ([28ef835](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/28ef8351c10ceef1018092efd2769914d37806d6))
* rate limit behind load balancer ([#91](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/91)) ([da32fc3](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/da32fc398e88244fba13ebfe4c6108a2b58129b1))
* **redeploy:** add optional branch param to aiven_application_redeploy ([#89](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/89)) ([ed00551](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/ed005519c2542d1c92015b655d35a75a84765a9e))
* unify build logs into service logs tool via log_type param ([#137](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/137)) ([8812ae0](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/8812ae02e34a4ca2c557ee8cfed56c64dc4756cb))


### Bug Fixes

* add IP-keyed rate limit ([#83](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/83)) ([fe2ef14](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/fe2ef14bbbca189f8c57103493faeda15138b302))
* aiven marketplace urls documentation ([#117](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/117)) ([cc0764c](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/cc0764ce3241b7a7c93377b9678286b5e0e0748b))
* aiven mcp submission to codex ([#147](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/147)) ([b45dd2b](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/b45dd2b08fd3100e9958f040e092b55861216fa8))
* align with openaid review requests ([#148](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/148)) ([8fabdb5](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/8fabdb5dd7909d68f7913df14723973ca00dfd93))
* allow_secrets in stdio mode ([#134](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/134)) ([fa4111a](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/fa4111a79221942e1178cfc361f20e3482610f43))
* bound aiven_service_list fan-out and drop broken pagination ([#130](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/130)) ([fd52727](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/fd5272738655490752993e155ef6e75553e28c19))
* clarify kafka connect list tool does not return runtime state ([752e98f](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/752e98fe543cfa52a16da63793725de612c9cde0))
* clarify kafka connect list tool does not return runtime state ([a1150e9](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/a1150e9492cdc905cffda8e3f3870fde4a064ce1))
* default include_secrets ([#107](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/107)) ([a49d118](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/a49d118c43c6f890f2bb153b19f1f85b89e6240d))
* **descriptions:** correct cross-tool refs, restore plan-gate summaries, ground new descriptions in OpenAPI [EVERSQL-1822] ([#97](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/97)) ([be2df18](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/be2df184309479277590fb472c2dfeb496c5fb5c))
* disable connection info tool in read-only mode ([#126](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/126)) ([f31c3d7](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/f31c3d7c3d8dc3a837f37b4bb3c120fbd55d4032))
* doubled /mcp host ([#119](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/119)) ([2f4a203](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/2f4a2034301bfd74e619efe4e5ed22dfc4591ef6))
* enhance model armor input scanning ([#150](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/150)) ([527c5f3](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/527c5f3d148e8ce47be43b10cf9ec40c97553364))
* fix the 401 error hint [EVERSQL-1792] ([55a8030](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/55a80306e1501f26c5ae6e06400e9d7ff03d80b0))
* fix the 401 error hint [EVERSQL-1792] ([b592c9a](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/b592c9a0974bcf415e600612cf516c6e323eda16))
* improve logging for output trim warnings ([#139](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/139)) ([771f4be](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/771f4be4c046785a010a0b0c5363d0e28d142946))
* increase rate limit ([#133](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/133)) ([936765a](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/936765a559a950497f2d559fdae3bb7b8c538ca0))
* invalid secrets references in release and publish workflows ([#77](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/77)) ([372c474](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/372c47494f6c3a19366fa1e4fe32e6e786c23e40))
* limit large fields max size ([#71](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/71)) ([450e3c1](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/450e3c1539ad2fdbdea75e105ed7de2e0554c2ec))
* log environment variables on server startup ([#161](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/161)) ([c43799a](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/c43799aef6dac32101e18731a168f7bb92b81a97))
* log the registered tool catalog at startup [EVERSQL-2013] ([#164](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/164)) ([61eb15a](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/61eb15a5ed07926c4c1dddffd2c6ac94be943767))
* model armor security scanning tests ([#151](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/151)) ([a04a1fe](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/a04a1fe635dbe147f03de1f1cb5681b194b9e77d))
* move npm publish into release workflow ([#79](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/79)) ([ac220f7](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/ac220f761246d4e8b96d16e293cf8eee9c4022ed))
* parse release-please PR output as JSON for Slack notification ([#76](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/76)) ([24c99d4](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/24c99d405d53da38f4f94e81566cfad45586da40))
* postpone json parsing to after auth ([#72](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/72)) ([71a7040](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/71a7040497a71a7f35fd7d3998d0a109f678e23f))
* prevent default truncation when fetching metrics ([f0feb1a](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/f0feb1a09c2f0903944df402d77a81a913e276e9))
* redact mid-string credential URIs ([#123](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/123)) ([0f14022](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/0f1402208f0fc57875f72c8224a48e2c8b259665))
* redact PII and secrets from reasoning field before egress ([#127](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/127)) ([9a66603](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/9a666032ab28c87f703cdf09ab75283f4431c2b2))
* reflect write_allowlist in read-only mode instructions ([#145](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/145)) ([2e4596c](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/2e4596c1d7ace1c1ec6d3bb2dcee2c726b30310a))
* reject conflicting kafka connector fields when source_service is set ([#111](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/111)) ([64ef013](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/64ef01300f187b275924513a9a0fe73202ba6579))
* release-please workflow failing ([#74](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/74)) ([2eff5c8](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/2eff5c80c3fef389e075c2a37bc6401ece6584db))
* remove assistant-directed instructions from tool descriptions ([#153](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/153)) ([e6d4a8d](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/e6d4a8df7a0486ac248f89580e2fdde312a18312))
* remove invalid cache: false from setup-node ([#81](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/81)) ([7029863](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/70298632fe1b51def9ac4258fad1e76ef88ea9f4))
* remove redundant logs ([#63](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/63)) ([7bfcdf1](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/7bfcdf1c29d9b4ea52ccfc9158493d34f23a8a3f))
* remove stale READ_ONLY_INSTRUCTIONS import causing build failure ([a7a845e](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/a7a845eea6154285c77b5cb86321cd764b35691a))
* return 405 on SSE get request ([cee76a3](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/cee76a310c5d63ff69987e5b7f5d3a1650b6c288))
* return 405 on SSE get request ([8c7f020](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/8c7f020d205bc11af3c00101211fc444b22811f7))
* revert npm version ([#143](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/143)) ([11b33ca](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/11b33ca9fe614f3d72b36b3460057f57b7d01337))
* sanitize X-MCP-Client header to first product token ([#160](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/160)) ([c0ae532](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/c0ae53218eea1c7d11c7868a98f04de8b6b51f24))
* send project_vpc_id null on app deploy unless user requests VPC ([#158](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/158)) ([19b9eb7](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/19b9eb73f3361b937cb7359e0e6af253fadfd19d))
* service list custom tool ([3f0e9ae](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/3f0e9ae430c5075274f6d661440ae9945b797fc1))
* service list custom tool [EVERSQL-1827] ([e1333d3](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/e1333d326743bbbf86cd3bf0f01e838986b683b5))
* set git identity before creating annotated tag ([148c975](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/148c9756b5a005029e9234db3c3ba470aa5fab5f))
* set git identity before creating annotated tag ([ed3da12](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/ed3da122b21ed90fd4351ad85cab08a17b061270))
* support marketplace mcp authorization ([#114](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/114)) ([ad43a06](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/ad43a06f694294abbaa588030b39809e39a588b4))
* trigger application redeploy via the redeploy endpoint ([#166](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/166)) ([76a4666](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/76a4666976ad7eb5a28e3aa1ea49f09041e03580))
* use fileURLToPath for Windows-compatible manifest path resolution ([#110](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/110)) ([4459523](https://github.com/kevinthornodegard-sys/mcp-aiven/commit/4459523aa9a97c51052625b49375bc2056f188e4)), closes [#109](https://github.com/kevinthornodegard-sys/mcp-aiven/issues/109)

## [1.15.3](https://github.com/Aiven-Open/mcp-aiven/compare/v1.15.2...v1.15.3) (2026-08-27)


### Bug Fixes

* trigger application redeploy via the redeploy endpoint ([#166](https://github.com/Aiven-Open/mcp-aiven/issues/166)) ([76a4666](https://github.com/Aiven-Open/mcp-aiven/commit/76a4666976ad7eb5a28e3aa1ea49f09041e03580))

## [1.15.2](https://github.com/Aiven-Open/mcp-aiven/compare/v1.15.1...v1.15.2) (2026-08-09)


### Bug Fixes

* log environment variables on server startup ([#161](https://github.com/Aiven-Open/mcp-aiven/issues/161)) ([c43799a](https://github.com/Aiven-Open/mcp-aiven/commit/c43799aef6dac32101e18731a168f7bb92b81a97))
* log the registered tool catalog at startup [EVERSQL-2013] ([#164](https://github.com/Aiven-Open/mcp-aiven/issues/164)) ([61eb15a](https://github.com/Aiven-Open/mcp-aiven/commit/61eb15a5ed07926c4c1dddffd2c6ac94be943767))

## [1.15.1](https://github.com/Aiven-Open/mcp-aiven/compare/v1.15.0...v1.15.1) (2026-08-04)


### Bug Fixes

* sanitize X-MCP-Client header to first product token ([#160](https://github.com/Aiven-Open/mcp-aiven/issues/160)) ([c0ae532](https://github.com/Aiven-Open/mcp-aiven/commit/c0ae53218eea1c7d11c7868a98f04de8b6b51f24))
* send project_vpc_id null on app deploy unless user requests VPC ([#158](https://github.com/Aiven-Open/mcp-aiven/issues/158)) ([19b9eb7](https://github.com/Aiven-Open/mcp-aiven/commit/19b9eb73f3361b937cb7359e0e6af253fadfd19d))

## [1.15.0](https://github.com/Aiven-Open/mcp-aiven/compare/v1.14.6...v1.15.0) (2026-07-23)


### Features

* move pg read and write to use pg-editor/run-query ([28ef835](https://github.com/Aiven-Open/mcp-aiven/commit/28ef8351c10ceef1018092efd2769914d37806d6))

## [1.14.6](https://github.com/Aiven-Open/mcp-aiven/compare/v1.14.5...v1.14.6) (2026-07-22)


### Bug Fixes

* remove assistant-directed instructions from tool descriptions ([#153](https://github.com/Aiven-Open/mcp-aiven/issues/153)) ([e6d4a8d](https://github.com/Aiven-Open/mcp-aiven/commit/e6d4a8df7a0486ac248f89580e2fdde312a18312))

## [1.14.5](https://github.com/Aiven-Open/mcp-aiven/compare/v1.14.4...v1.14.5) (2026-07-20)


### Bug Fixes

* enhance model armor input scanning ([#150](https://github.com/Aiven-Open/mcp-aiven/issues/150)) ([527c5f3](https://github.com/Aiven-Open/mcp-aiven/commit/527c5f3d148e8ce47be43b10cf9ec40c97553364))
* model armor security scanning tests ([#151](https://github.com/Aiven-Open/mcp-aiven/issues/151)) ([a04a1fe](https://github.com/Aiven-Open/mcp-aiven/commit/a04a1fe635dbe147f03de1f1cb5681b194b9e77d))

## [1.14.4](https://github.com/Aiven-Open/mcp-aiven/compare/v1.14.3...v1.14.4) (2026-07-19)


### Bug Fixes

* align with openaid review requests ([#148](https://github.com/Aiven-Open/mcp-aiven/issues/148)) ([8fabdb5](https://github.com/Aiven-Open/mcp-aiven/commit/8fabdb5dd7909d68f7913df14723973ca00dfd93))

## [1.14.3](https://github.com/Aiven-Open/mcp-aiven/compare/v1.14.2...v1.14.3) (2026-07-14)


### Bug Fixes

* aiven mcp submission to codex ([#147](https://github.com/Aiven-Open/mcp-aiven/issues/147)) ([b45dd2b](https://github.com/Aiven-Open/mcp-aiven/commit/b45dd2b08fd3100e9958f040e092b55861216fa8))
* reflect write_allowlist in read-only mode instructions ([#145](https://github.com/Aiven-Open/mcp-aiven/issues/145)) ([2e4596c](https://github.com/Aiven-Open/mcp-aiven/commit/2e4596c1d7ace1c1ec6d3bb2dcee2c726b30310a))

## [1.14.2](https://github.com/Aiven-Open/mcp-aiven/compare/v1.14.1...v1.14.2) (2026-07-09)


### Bug Fixes

* revert npm version ([#143](https://github.com/Aiven-Open/mcp-aiven/issues/143)) ([11b33ca](https://github.com/Aiven-Open/mcp-aiven/commit/11b33ca9fe614f3d72b36b3460057f57b7d01337))

## [1.14.1](https://github.com/Aiven-Open/mcp-aiven/compare/v1.14.0...v1.14.1) (2026-07-09)


### Bug Fixes

* bound aiven_service_list fan-out and drop broken pagination ([#130](https://github.com/Aiven-Open/mcp-aiven/issues/130)) ([fd52727](https://github.com/Aiven-Open/mcp-aiven/commit/fd5272738655490752993e155ef6e75553e28c19))

## [1.14.0](https://github.com/Aiven-Open/mcp-aiven/compare/v1.13.0...v1.14.0) (2026-07-09)


### Features

* add write_allowlist to re-enable specific write tools in read-only mode ([#141](https://github.com/Aiven-Open/mcp-aiven/issues/141)) ([2120184](https://github.com/Aiven-Open/mcp-aiven/commit/21201847a91be8bfa307572c92ffa939a3cbb7cf))
* integrate security scan tool for inputs and outputs ([#131](https://github.com/Aiven-Open/mcp-aiven/issues/131)) ([093195f](https://github.com/Aiven-Open/mcp-aiven/commit/093195f70a55984217008b07cae1413664d28812))


### Bug Fixes

* improve logging for output trim warnings ([#139](https://github.com/Aiven-Open/mcp-aiven/issues/139)) ([771f4be](https://github.com/Aiven-Open/mcp-aiven/commit/771f4be4c046785a010a0b0c5363d0e28d142946))
* redact PII and secrets from reasoning field before egress ([#127](https://github.com/Aiven-Open/mcp-aiven/issues/127)) ([9a66603](https://github.com/Aiven-Open/mcp-aiven/commit/9a666032ab28c87f703cdf09ab75283f4431c2b2))

## [1.13.0](https://github.com/Aiven-Open/mcp-aiven/compare/v1.12.0...v1.13.0) (2026-06-25)


### Features

* unify build logs into service logs tool via log_type param ([#137](https://github.com/Aiven-Open/mcp-aiven/issues/137)) ([8812ae0](https://github.com/Aiven-Open/mcp-aiven/commit/8812ae02e34a4ca2c557ee8cfed56c64dc4756cb))

## [1.12.0](https://github.com/Aiven-Open/mcp-aiven/compare/v1.11.2...v1.12.0) (2026-06-25)


### Features

* add server.json for mcp official registry ([#135](https://github.com/Aiven-Open/mcp-aiven/issues/135)) ([4c86c63](https://github.com/Aiven-Open/mcp-aiven/commit/4c86c63b3f12a434b0b5c4ddb5b00e34638fea03))

## [1.11.2](https://github.com/Aiven-Open/mcp-aiven/compare/v1.11.1...v1.11.2) (2026-06-24)


### Bug Fixes

* allow_secrets in stdio mode ([#134](https://github.com/Aiven-Open/mcp-aiven/issues/134)) ([fa4111a](https://github.com/Aiven-Open/mcp-aiven/commit/fa4111a79221942e1178cfc361f20e3482610f43))
* disable connection info tool in read-only mode ([#126](https://github.com/Aiven-Open/mcp-aiven/issues/126)) ([f31c3d7](https://github.com/Aiven-Open/mcp-aiven/commit/f31c3d7c3d8dc3a837f37b4bb3c120fbd55d4032))
* increase rate limit ([#133](https://github.com/Aiven-Open/mcp-aiven/issues/133)) ([936765a](https://github.com/Aiven-Open/mcp-aiven/commit/936765a559a950497f2d559fdae3bb7b8c538ca0))

## [1.11.1](https://github.com/Aiven-Open/mcp-aiven/compare/v1.11.0...v1.11.1) (2026-06-21)


### Bug Fixes

* redact mid-string credential URIs ([#123](https://github.com/Aiven-Open/mcp-aiven/issues/123)) ([0f14022](https://github.com/Aiven-Open/mcp-aiven/commit/0f1402208f0fc57875f72c8224a48e2c8b259665))

## [1.11.0](https://github.com/Aiven-Open/mcp-aiven/compare/v1.10.0...v1.11.0) (2026-06-18)


### Features

* add aiven_service_connection_info tool gated by allow_secrets ([#121](https://github.com/Aiven-Open/mcp-aiven/issues/121)) ([73d8d3a](https://github.com/Aiven-Open/mcp-aiven/commit/73d8d3a6ebfcb141ce5955f4fb042c986c7d79af))

## [1.10.0](https://github.com/Aiven-Open/mcp-aiven/compare/v1.9.2...v1.10.0) (2026-06-18)


### Features

* add aiven_application_build_logs_get tool ([#116](https://github.com/Aiven-Open/mcp-aiven/issues/116)) ([0ecde0e](https://github.com/Aiven-Open/mcp-aiven/commit/0ecde0e4a0e305c22684938e819bb1fbe71b4eea))


### Bug Fixes

* aiven marketplace urls documentation ([#117](https://github.com/Aiven-Open/mcp-aiven/issues/117)) ([cc0764c](https://github.com/Aiven-Open/mcp-aiven/commit/cc0764ce3241b7a7c93377b9678286b5e0e0748b))

## [1.9.2](https://github.com/Aiven-Open/mcp-aiven/compare/v1.9.1...v1.9.2) (2026-06-17)


### Bug Fixes

* doubled /mcp host ([#119](https://github.com/Aiven-Open/mcp-aiven/issues/119)) ([2f4a203](https://github.com/Aiven-Open/mcp-aiven/commit/2f4a2034301bfd74e619efe4e5ed22dfc4591ef6))

## [1.9.1](https://github.com/Aiven-Open/mcp-aiven/compare/v1.9.0...v1.9.1) (2026-06-17)


### Bug Fixes

* support marketplace mcp authorization ([#114](https://github.com/Aiven-Open/mcp-aiven/issues/114)) ([ad43a06](https://github.com/Aiven-Open/mcp-aiven/commit/ad43a06f694294abbaa588030b39809e39a588b4))
* use fileURLToPath for Windows-compatible manifest path resolution ([#110](https://github.com/Aiven-Open/mcp-aiven/issues/110)) ([4459523](https://github.com/Aiven-Open/mcp-aiven/commit/4459523aa9a97c51052625b49375bc2056f188e4)), closes [#109](https://github.com/Aiven-Open/mcp-aiven/issues/109)

## [1.9.0](https://github.com/Aiven-Open/mcp-aiven/compare/v1.8.2...v1.9.0) (2026-06-17)


### Features

* adapt to new app service credential integration format ([#98](https://github.com/Aiven-Open/mcp-aiven/issues/98)) ([3f19431](https://github.com/Aiven-Open/mcp-aiven/commit/3f194313b30f957e8e33c9c7bf5d00b3babb6939))

## [1.8.2](https://github.com/Aiven-Open/mcp-aiven/compare/v1.8.1...v1.8.2) (2026-06-14)


### Bug Fixes

* reject conflicting kafka connector fields when source_service is set ([#111](https://github.com/Aiven-Open/mcp-aiven/issues/111)) ([64ef013](https://github.com/Aiven-Open/mcp-aiven/commit/64ef01300f187b275924513a9a0fe73202ba6579))

## [1.8.1](https://github.com/Aiven-Open/mcp-aiven/compare/v1.8.0...v1.8.1) (2026-06-09)


### Bug Fixes

* default include_secrets ([#107](https://github.com/Aiven-Open/mcp-aiven/issues/107)) ([a49d118](https://github.com/Aiven-Open/mcp-aiven/commit/a49d118c43c6f890f2bb153b19f1f85b89e6240d))

## [1.8.0](https://github.com/Aiven-Open/mcp-aiven/compare/v1.7.1...v1.8.0) (2026-06-02)


### Features

* add severity filter to service logs tool ([#99](https://github.com/Aiven-Open/mcp-aiven/issues/99)) ([992617f](https://github.com/Aiven-Open/mcp-aiven/commit/992617fdd10814ec0f0a5f484f6f4854811ba71b))

## [1.7.1](https://github.com/Aiven-Open/mcp-aiven/compare/v1.7.0...v1.7.1) (2026-06-01)


### Bug Fixes

* **descriptions:** correct cross-tool refs, restore plan-gate summaries, ground new descriptions in OpenAPI [EVERSQL-1822] ([#97](https://github.com/Aiven-Open/mcp-aiven/issues/97)) ([be2df18](https://github.com/Aiven-Open/mcp-aiven/commit/be2df184309479277590fb472c2dfeb496c5fb5c))

## [1.7.0](https://github.com/Aiven-Open/mcp-aiven/compare/v1.6.0...v1.7.0) (2026-05-27)


### Features

* add opt-in Sentry integration for error tracking and logging ([#88](https://github.com/Aiven-Open/mcp-aiven/issues/88)) ([1f56fa0](https://github.com/Aiven-Open/mcp-aiven/commit/1f56fa04b22060d03080a764a5f52e46510dc784))

## [1.6.0](https://github.com/Aiven-Open/mcp-aiven/compare/v1.5.0...v1.6.0) (2026-05-25)


### Features

* **redeploy:** add optional branch param to aiven_application_redeploy ([#89](https://github.com/Aiven-Open/mcp-aiven/issues/89)) ([ed00551](https://github.com/Aiven-Open/mcp-aiven/commit/ed005519c2542d1c92015b655d35a75a84765a9e))

## [1.5.0](https://github.com/Aiven-Open/mcp-aiven/compare/v1.4.0...v1.5.0) (2026-05-25)


### Features

* rate limit behind load balancer ([#91](https://github.com/Aiven-Open/mcp-aiven/issues/91)) ([da32fc3](https://github.com/Aiven-Open/mcp-aiven/commit/da32fc398e88244fba13ebfe4c6108a2b58129b1))

## [1.4.0](https://github.com/Aiven-Open/mcp-aiven/compare/v1.3.3...v1.4.0) (2026-05-18)


### Features

* mcp maintenance mode ([#85](https://github.com/Aiven-Open/mcp-aiven/issues/85)) ([45e52cf](https://github.com/Aiven-Open/mcp-aiven/commit/45e52cf78bcdf0cd5d648a1ba5efd4861ba13cf8))


### Bug Fixes

* add IP-keyed rate limit ([#83](https://github.com/Aiven-Open/mcp-aiven/issues/83)) ([fe2ef14](https://github.com/Aiven-Open/mcp-aiven/commit/fe2ef14bbbca189f8c57103493faeda15138b302))

## [1.3.3](https://github.com/Aiven-Open/mcp-aiven/compare/v1.3.2...v1.3.3) (2026-05-17)


### Bug Fixes

* remove invalid cache: false from setup-node ([#81](https://github.com/Aiven-Open/mcp-aiven/issues/81)) ([7029863](https://github.com/Aiven-Open/mcp-aiven/commit/70298632fe1b51def9ac4258fad1e76ef88ea9f4))

## [1.3.2](https://github.com/Aiven-Open/mcp-aiven/compare/v1.3.1...v1.3.2) (2026-05-17)


### Bug Fixes

* move npm publish into release workflow ([#79](https://github.com/Aiven-Open/mcp-aiven/issues/79)) ([ac220f7](https://github.com/Aiven-Open/mcp-aiven/commit/ac220f761246d4e8b96d16e293cf8eee9c4022ed))

## [1.3.1](https://github.com/Aiven-Open/mcp-aiven/compare/v1.3.0...v1.3.1) (2026-05-17)


### Bug Fixes

* invalid secrets references in release and publish workflows ([#77](https://github.com/Aiven-Open/mcp-aiven/issues/77)) ([372c474](https://github.com/Aiven-Open/mcp-aiven/commit/372c47494f6c3a19366fa1e4fe32e6e786c23e40))
* limit large fields max size ([#71](https://github.com/Aiven-Open/mcp-aiven/issues/71)) ([450e3c1](https://github.com/Aiven-Open/mcp-aiven/commit/450e3c1539ad2fdbdea75e105ed7de2e0554c2ec))

## [1.3.0](https://github.com/Aiven-Open/mcp-aiven/compare/v1.2.0...v1.3.0) (2026-05-17)


### Features

* adopt semantic-release for automated versioning and npm publishing ([#67](https://github.com/Aiven-Open/mcp-aiven/issues/67)) ([f4d0dad](https://github.com/Aiven-Open/mcp-aiven/commit/f4d0dad2cf9d1b995a9bef9ac2ae966cdcfdb970))
* migrate from semantic-release to release-please ([#70](https://github.com/Aiven-Open/mcp-aiven/issues/70)) ([e6b744a](https://github.com/Aiven-Open/mcp-aiven/commit/e6b744ae7eb2909e39a0ecf3c98ed1b70f925d12))
* modify destructive tools [EVERSQL-1812] ([#73](https://github.com/Aiven-Open/mcp-aiven/issues/73)) ([a18593f](https://github.com/Aiven-Open/mcp-aiven/commit/a18593f912c42b7ff1979f41f1bae02668f6f822))


### Bug Fixes

* parse release-please PR output as JSON for Slack notification ([#76](https://github.com/Aiven-Open/mcp-aiven/issues/76)) ([24c99d4](https://github.com/Aiven-Open/mcp-aiven/commit/24c99d405d53da38f4f94e81566cfad45586da40))
* postpone json parsing to after auth ([#72](https://github.com/Aiven-Open/mcp-aiven/issues/72)) ([71a7040](https://github.com/Aiven-Open/mcp-aiven/commit/71a7040497a71a7f35fd7d3998d0a109f678e23f))
* release-please workflow failing ([#74](https://github.com/Aiven-Open/mcp-aiven/issues/74)) ([2eff5c8](https://github.com/Aiven-Open/mcp-aiven/commit/2eff5c80c3fef389e075c2a37bc6401ece6584db))
