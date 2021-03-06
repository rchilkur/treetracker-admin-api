## [2.12.3](https://github.com/Greenstand/treetracker-admin/compare/v2.12.2...v2.12.3) (2021-02-22)


### Bug Fixes

* don't look for host ip from request headers while auditing ([2dd0af2](https://github.com/Greenstand/treetracker-admin/commit/2dd0af2def7e74efebaf3f4599d785dd2925b368))

## [2.12.2](https://github.com/Greenstand/treetracker-admin/compare/v2.12.1...v2.12.2) (2021-02-18)


### Bug Fixes

* prettier config files for client/server ([#519](https://github.com/Greenstand/treetracker-admin/issues/519)) ([9f233dd](https://github.com/Greenstand/treetracker-admin/commit/9f233dd976a432fb6852f4cf5ee2c2903fe2d533))

## [2.12.1](https://github.com/Greenstand/treetracker-admin/compare/v2.12.0...v2.12.1) (2021-02-17)


### Bug Fixes

* allow users to list organizations ([#511](https://github.com/Greenstand/treetracker-admin/issues/511)) ([f54f992](https://github.com/Greenstand/treetracker-admin/commit/f54f99293386b26e4156dac90754ffe96eafe9d0))

# [2.12.0](https://github.com/Greenstand/treetracker-admin/compare/v2.11.6...v2.12.0) (2021-02-16)


### Features

* fixes based on PR feedback ([1b18a27](https://github.com/Greenstand/treetracker-admin/commit/1b18a27752e458f0d2a1a4efebbc1bad3cd421f1))
* make error handling robust when publishing messages ([df80411](https://github.com/Greenstand/treetracker-admin/commit/df80411be1161fc15840f64c902de157301a14a4))
* propagate rejection reason as part of verificaton event ([9fb6790](https://github.com/Greenstand/treetracker-admin/commit/9fb67904235c146b6df2e4dcaf0562354467e87d))
* raise and publish domainevent on verification ([8f89f3e](https://github.com/Greenstand/treetracker-admin/commit/8f89f3eed285a6a14ba42bb9cd66f90076a5b259))
* remove unused variable ([19b93ab](https://github.com/Greenstand/treetracker-admin/commit/19b93abd4cddb2a04f0d0ee90603bfbd95bbd0b6))
* Use env variable for a config property ([ebc8339](https://github.com/Greenstand/treetracker-admin/commit/ebc8339f3e7649742c4571dc25e5616ba2b069d6))
* use loopback connector transaction using import instead of require ([b213dd9](https://github.com/Greenstand/treetracker-admin/commit/b213dd91b65b9581d07129b073e61ef7efd5470d))
* WIP - publishing verification messages on verify action ([85d0bec](https://github.com/Greenstand/treetracker-admin/commit/85d0becf24cf1a669d3cb53191ea07333c6e17ed))

## [2.11.6](https://github.com/Greenstand/treetracker-admin/compare/v2.11.5...v2.11.6) (2021-02-15)


### Bug Fixes

* correct import syntax for config ([#516](https://github.com/Greenstand/treetracker-admin/issues/516)) ([e713a71](https://github.com/Greenstand/treetracker-admin/commit/e713a71d5370d83fad3841a6cf5fb898513f71b8))

## [2.11.5](https://github.com/Greenstand/treetracker-admin/compare/v2.11.4...v2.11.5) (2021-02-15)


### Bug Fixes

* audit logging ([#501](https://github.com/Greenstand/treetracker-admin/issues/501)) ([de5840a](https://github.com/Greenstand/treetracker-admin/commit/de5840ab0204a4099dde0b2afdca3d8e646fb99e))

## [2.11.4](https://github.com/Greenstand/treetracker-admin/compare/v2.11.3...v2.11.4) (2021-02-15)


### Bug Fixes

* timestamptz datatype spelling mistake ([#513](https://github.com/Greenstand/treetracker-admin/issues/513)) ([09413b2](https://github.com/Greenstand/treetracker-admin/commit/09413b24cab83dc8f7e82cdd6f7de1660541db1c))

## [2.11.3](https://github.com/Greenstand/treetracker-admin/compare/v2.11.2...v2.11.3) (2021-02-13)


### Bug Fixes

* 404 error at /check_session ([#506](https://github.com/Greenstand/treetracker-admin/issues/506)) ([f025de0](https://github.com/Greenstand/treetracker-admin/commit/f025de00d8916c2cd4c68518a330af9d3772b3f0))

## [2.11.2](https://github.com/Greenstand/treetracker-admin/compare/v2.11.1...v2.11.2) (2021-02-13)


### Bug Fixes

* reinstate dev webmap domain ([8915ceb](https://github.com/Greenstand/treetracker-admin/commit/8915ceb2d070a0836c0cf3a6e23f7d9393de31f9))

## [2.11.1](https://github.com/Greenstand/treetracker-admin/compare/v2.11.0...v2.11.1) (2021-02-10)


### Bug Fixes

* point dev client at deployed dev API by default ([#505](https://github.com/Greenstand/treetracker-admin/issues/505)) ([97968a8](https://github.com/Greenstand/treetracker-admin/commit/97968a8a8fff2cca3ad92cfd3317c6ab191fa7fb))

# [2.11.0](https://github.com/Greenstand/treetracker-admin/compare/v2.10.0...v2.11.0) (2021-02-08)


### Features

* add species on /species ([#497](https://github.com/Greenstand/treetracker-admin/issues/497)) ([bbb20a0](https://github.com/Greenstand/treetracker-admin/commit/bbb20a06aafa6f49ce6799d5e45e7a7f9108c1e2))

# [2.10.0](https://github.com/Greenstand/treetracker-admin/compare/v2.9.0...v2.10.0) (2021-02-04)


### Features

* filter by not tagged on /verify ([#496](https://github.com/Greenstand/treetracker-admin/issues/496)) ([2369718](https://github.com/Greenstand/treetracker-admin/commit/236971823232a40c64b2332603d1b6272c62dbe5))

# [2.9.0](https://github.com/Greenstand/treetracker-admin/compare/v2.8.0...v2.9.0) (2021-02-04)


### Features

* edit planter ([#495](https://github.com/Greenstand/treetracker-admin/issues/495)) ([6b03509](https://github.com/Greenstand/treetracker-admin/commit/6b03509027cd126901641d2016e6c589ab56009e))

# [2.8.0](https://github.com/Greenstand/treetracker-admin/compare/v2.7.0...v2.8.0) (2021-02-03)


### Features

* add note to tree dialog on /verify ([#494](https://github.com/Greenstand/treetracker-admin/issues/494)) ([b13d4f3](https://github.com/Greenstand/treetracker-admin/commit/b13d4f3b162435bc14462f7ee6392926bec4e05b))

# [2.7.0](https://github.com/Greenstand/treetracker-admin/compare/v2.6.1...v2.7.0) (2021-02-02)


### Features

* add planter org name ([#493](https://github.com/Greenstand/treetracker-admin/issues/493)) ([0217e48](https://github.com/Greenstand/treetracker-admin/commit/0217e48a1646e0379eb435798fc1a6abf5747250))

## [2.6.1](https://github.com/Greenstand/treetracker-admin/compare/v2.6.0...v2.6.1) (2021-01-17)


### Bug Fixes

* trees page ([#487](https://github.com/Greenstand/treetracker-admin/issues/487)) ([cdf2de5](https://github.com/Greenstand/treetracker-admin/commit/cdf2de5f42c6ca9590a30706ebde96193f822ef8))

# [2.6.0](https://github.com/Greenstand/treetracker-admin/compare/v2.5.0...v2.6.0) (2021-01-09)


### Features

* trying to fix tests on server ([#479](https://github.com/Greenstand/treetracker-admin/issues/479)) ([4b9c8ed](https://github.com/Greenstand/treetracker-admin/commit/4b9c8edfd916664cf6065cc620360daa223acfe4))

# [2.5.0](https://github.com/Greenstand/treetracker-admin/compare/v2.4.4...v2.5.0) (2020-12-22)


### Bug Fixes

* reinstate patch number in version ([aaede69](https://github.com/Greenstand/treetracker-admin/commit/aaede6972e5004256e2fcffc625f99c9e36a5e4a))


### Features

* bump release ([480bec5](https://github.com/Greenstand/treetracker-admin/commit/480bec538eb9ba98765753470d670f72082fa797))
* bump release ([8f9d4e9](https://github.com/Greenstand/treetracker-admin/commit/8f9d4e9688432daba0573fa72dc90dbecd771e61))

## [2.4.4](https://github.com/Greenstand/treetracker-admin/compare/v2.4.3...v2.4.4) (2020-12-10)


### Bug Fixes

* remove duplicate github plugin ([#475](https://github.com/Greenstand/treetracker-admin/issues/475)) ([542f3ea](https://github.com/Greenstand/treetracker-admin/commit/542f3ea7dfda61143a7a5fe06431a5cc29f392ac))

## [2.4.3](https://github.com/Greenstand/treetracker-admin/compare/v2.4.2...v2.4.3) (2020-12-10)


### Bug Fixes

* refactoring to trigger build ([9f6c514](https://github.com/Greenstand/treetracker-admin/commit/9f6c5140c44cdff9d2c5c8a0a4f39857e9ea51a2))
* Set options on github plugin ([7f8bb42](https://github.com/Greenstand/treetracker-admin/commit/7f8bb42e71d7f05a483fec93e55dd28384b31b9d))

## [2.4.2](https://github.com/Greenstand/treetracker-admin/compare/v2.4.1...v2.4.2) (2020-12-10)


### Bug Fixes

* export bumped version as env variable and disable a few semantic-release bot features ([2ecd7ce](https://github.com/Greenstand/treetracker-admin/commit/2ecd7ce2153d843fa83b0f7c02ba96d73b99400f))

## [2.4.1](https://github.com/Greenstand/treetracker-admin/compare/v2.4.0...v2.4.1) (2020-12-10)


### Bug Fixes

* read the root package.json ([8306304](https://github.com/Greenstand/treetracker-admin/commit/8306304ff40b76305e03f37b271e7e1b1b281390))

# [2.4.0](https://github.com/Greenstand/treetracker-admin/compare/v2.3.0...v2.4.0) (2020-12-10)


### Bug Fixes

* Add semver ([#465](https://github.com/Greenstand/treetracker-admin/issues/465)) ([47758e5](https://github.com/Greenstand/treetracker-admin/commit/47758e543dab28c99b79dd42b3b04033a2116dba))
* bug ([#421](https://github.com/Greenstand/treetracker-admin/issues/421)) ([61791ca](https://github.com/Greenstand/treetracker-admin/commit/61791cae0d9f4cfeff4bfbfdc9999170e87bd958))
* error when validate user password ([ad00dd8](https://github.com/Greenstand/treetracker-admin/commit/ad00dd8a426680fdbf0df98a22bd155da2d262f1))
* init ([51106cb](https://github.com/Greenstand/treetracker-admin/commit/51106cb94640b7d6fb82ef6abf0198a71039ea3b))
* merging error ([c6d19b3](https://github.com/Greenstand/treetracker-admin/commit/c6d19b3d13ec27a0fb5e60115db2695c68574039))
* move config to rootDir ([6525e91](https://github.com/Greenstand/treetracker-admin/commit/6525e91527bd68b1f49f4f68de184bea1b65f9fc))
* remove type in url on readme for local dev ([3b6f28e](https://github.com/Greenstand/treetracker-admin/commit/3b6f28e733e7ada5594ae5bf7169f52db7297d19))
* typo ([7e87a50](https://github.com/Greenstand/treetracker-admin/commit/7e87a505d3efc0c312780d214336ca9e013f0a39))
* uncomment ([25a54ae](https://github.com/Greenstand/treetracker-admin/commit/25a54ae77fa5919faae6da17369984a4c6c5487b))


### Features

* add copy ui ([cb042c9](https://github.com/Greenstand/treetracker-admin/commit/cb042c9757b144f418d43f5b31effcee3df234fb))
* add dependency ([9779948](https://github.com/Greenstand/treetracker-admin/commit/9779948925fcb0f8d6485993058cfda10ebba5de))
* add dependency ([c2996db](https://github.com/Greenstand/treetracker-admin/commit/c2996dbf2a62d34b442f2db6c4221eb20c942e7c))
* add env file temporily ([70285a2](https://github.com/Greenstand/treetracker-admin/commit/70285a2f64678cfd2d0612e52406be7d2dd7937e))
* add functionality ([54012fa](https://github.com/Greenstand/treetracker-admin/commit/54012faa9fc8dc295611dd212bbb36d796b564e5))
* add input onChange event ([d9c56a5](https://github.com/Greenstand/treetracker-admin/commit/d9c56a5149962726073c202ea6eef4ddec13ed06))
* add jwt into dotenv ([14870c3](https://github.com/Greenstand/treetracker-admin/commit/14870c3b7bc8c62ef7199ea6c7f39d33106ee370))
* add loading spinner and prevent user click ([ca749cb](https://github.com/Greenstand/treetracker-admin/commit/ca749cb95d892e8573c7b69d18725607cd42c5b9))
* add password strength indicator UI ([715e81d](https://github.com/Greenstand/treetracker-admin/commit/715e81d54c7f01f2fd2e2dbd6c13b04ccdd9913b))
* add radio group for active status ([4212eef](https://github.com/Greenstand/treetracker-admin/commit/4212eeffde5ebd9b066c952642dad6f59c97372a))
* add the UI in place ([d814722](https://github.com/Greenstand/treetracker-admin/commit/d814722ca458d9b1ce1ebf3ac15b124ac338bd3c))
* add user login validation ([1fe644c](https://github.com/Greenstand/treetracker-admin/commit/1fe644c5a2275d0216bbf278171cf776d1beb912))
* added delete user. Auth error persisting on delete user ([9bbd86c](https://github.com/Greenstand/treetracker-admin/commit/9bbd86ca2bebd5302f804ffade8148f4372846ac))
* auto generate pwd ([ceac49f](https://github.com/Greenstand/treetracker-admin/commit/ceac49f8ddc59c6b444cbe8cb0f4a99e1b5c9692))
* check localStorage before painting ([ac207f6](https://github.com/Greenstand/treetracker-admin/commit/ac207f657bcf64290f746e675bf700b2db58e08a))
* empty right selected before close Dialog ([c3abe94](https://github.com/Greenstand/treetracker-admin/commit/c3abe946db97cc674ec0ab086fb351c32ea8a71e))
* empty right selected before close Dialog ([d0b721f](https://github.com/Greenstand/treetracker-admin/commit/d0b721f1a5c7b4e8f3592bec3b211e7b6d748b27))
* exclude sensitave info from login return ([eece41e](https://github.com/Greenstand/treetracker-admin/commit/eece41e56a2a30028949ac7958faa83a6c69df81))
* exclude sensitave info from login return ([f01f25f](https://github.com/Greenstand/treetracker-admin/commit/f01f25f7dba9e8bb4ca338662d6854cc7a6085ed))
* fix node version to 12 in server/client ([#386](https://github.com/Greenstand/treetracker-admin/issues/386)) ([2ac67e9](https://github.com/Greenstand/treetracker-admin/commit/2ac67e9d534fc365348458e265327c227fa66326))
* get policy sent back to client ([4d5939b](https://github.com/Greenstand/treetracker-admin/commit/4d5939be08e3bc7b41f294b3513507237348d7cf))
* get tree count by species ([#391](https://github.com/Greenstand/treetracker-admin/issues/391)) ([a50cd16](https://github.com/Greenstand/treetracker-admin/commit/a50cd169575758a569c7d594fea0e3387af24fbe))
* hash password and add salt into database ([d1ef07e](https://github.com/Greenstand/treetracker-admin/commit/d1ef07ebf3331f21d04a8b8e2724e41ed540b774))
* no space in username allowed ([#348](https://github.com/Greenstand/treetracker-admin/issues/348)) ([4258a3a](https://github.com/Greenstand/treetracker-admin/commit/4258a3a132cc92d52014e585a8db1e130415c388))
* only show error when focus ([21a4180](https://github.com/Greenstand/treetracker-admin/commit/21a418088c21a06c4445c77c10841784fda69386))
* replace role with policu(comments kept) ([73b2f9e](https://github.com/Greenstand/treetracker-admin/commit/73b2f9e2810daf3bd1b4f8eb32e75bb9b199f72c))
* sort users by created time ([991e012](https://github.com/Greenstand/treetracker-admin/commit/991e012bcfebc3bea5097f8e62a0a44fccae9315))
* update login password check to use hashed_pwd instead of raw pwd ([c6ecef4](https://github.com/Greenstand/treetracker-admin/commit/c6ecef4ec595df638ef8f2c0a24e1ca251586070))
* validate 3 input fields and request BE to update pwd ([e366c0f](https://github.com/Greenstand/treetracker-admin/commit/e366c0f1a632ef336e3dd134ab4d5e5af830cfaa))
* validate pwd the same ([5b8314a](https://github.com/Greenstand/treetracker-admin/commit/5b8314a7770396e7be36cd79d85610f1bccc7539))
* write policy into sql db ([ab7c9e5](https://github.com/Greenstand/treetracker-admin/commit/ab7c9e5c8811825b1786649d02ea58ed64076da1))
