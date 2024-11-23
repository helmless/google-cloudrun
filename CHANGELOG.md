# Changelog

## [0.2.0](https://github.com/helmless/google-cloudrun-chart/compare/v0.1.0...0.2.0) (2024-11-23)


### Features

* enable e2e tests ([cf1f091](https://github.com/helmless/google-cloudrun-chart/commit/cf1f0913ef567ff18ffdff9faa9d0df88a389b2b))


### Bug Fixes

* remove release pin ([8f1d764](https://github.com/helmless/google-cloudrun-chart/commit/8f1d764e8e2ef4b4f6929370d999c80869eeda13))
* **schema:** update schema ([9cdb5dc](https://github.com/helmless/google-cloudrun-chart/commit/9cdb5dc6d24ba565a3bdf0d676453577565b6b8b))

## 0.1.0 (2024-11-19)


### Features

* add key value env vars to allow overwrite ([76f5664](https://github.com/helmless/google-cloudrun-chart/commit/76f56645b636bc7225d155b5bf7be5649281cea9))
* add release workflows ([96b12e0](https://github.com/helmless/google-cloudrun-chart/commit/96b12e06e4f871f7266dc8b90712252732b47791))
* bootstrap mkdocs site ([987929e](https://github.com/helmless/google-cloudrun-chart/commit/987929e4609a48e8f0e262855fa6ce9948f15120))
* bootstrap terraform and action ([57f6d95](https://github.com/helmless/google-cloudrun-chart/commit/57f6d95d9faa630ffcb8e6dc532fd95b5de47f44))
* create github action to deploy CloudRun Service ([#10](https://github.com/helmless/google-cloudrun-chart/issues/10)) ([082a700](https://github.com/helmless/google-cloudrun-chart/commit/082a7002e5d59207c5a2fa2bed57ed785a7e4f6c))
* initial commit of core cloudrun service chart ([eec9439](https://github.com/helmless/google-cloudrun-chart/commit/eec943995d0de1da3ffcd5ae2d3f06cb8649dd37))
* **release:** add root package release with major and min version tags ([d3e1fef](https://github.com/helmless/google-cloudrun-chart/commit/d3e1fefc55c03e0268b4d42ea1139cf791a73b32))
* split up monorepo into actions and chart ([71d01b4](https://github.com/helmless/google-cloudrun-chart/commit/71d01b419cc51b6494149056b467a65676845f28))


### Bug Fixes

* **chart:** rename chart and publish directly to org ([45301e0](https://github.com/helmless/google-cloudrun-chart/commit/45301e0937e928516739ebd1d3a7315494798c05))
* **ci:** allow to dispatch release ([42bc4f2](https://github.com/helmless/google-cloudrun-chart/commit/42bc4f20c39cfa8079b4df8d778570e9d15f43e4))
* **ci:** do not validate template against k8s ([f34dd49](https://github.com/helmless/google-cloudrun-chart/commit/f34dd49dfad9c4c205f13ed013e454ead6a18802))
* **ci:** only publish chart when chart is released ([72b41b3](https://github.com/helmless/google-cloudrun-chart/commit/72b41b3b84712aa4dcc24d6cb9307d37a0921481))
* **ci:** set concurrency group for e2e tests ([0d39426](https://github.com/helmless/google-cloudrun-chart/commit/0d39426c91340ffbc79917208cf7664fae946885))
* **ci:** trigger follow up workflows using an app token on release ([60490fe](https://github.com/helmless/google-cloudrun-chart/commit/60490fe61f68bba45990fe1afced6d89a91e32f8))
* **ci:** validate chart without k8s ([24da6d8](https://github.com/helmless/google-cloudrun-chart/commit/24da6d8202c9342fb06ba53b5c13ef186827b1d7))
* configure release please for all sub components ([9d1d7d2](https://github.com/helmless/google-cloudrun-chart/commit/9d1d7d2bc8b9b482c3b91f6d9f0f65b7a9644807))
* only release components based on path ([8c3cf37](https://github.com/helmless/google-cloudrun-chart/commit/8c3cf37674caae92a6cbdb344ad3ad5d71731361))
* release ([cb40a00](https://github.com/helmless/google-cloudrun-chart/commit/cb40a00a1c24033a949b86c888a3447ee50d8163))
* **release:** correctly configure release-please ([c9aa289](https://github.com/helmless/google-cloudrun-chart/commit/c9aa2890e452b77dcb6c75ac6424cafa9b8c382d))
* **release:** correctly distinguish between component and root releases ([69fac89](https://github.com/helmless/google-cloudrun-chart/commit/69fac890fe689e2de41f45cc636ae5d55f705118))
* **release:** do not tag major versions ([96d614f](https://github.com/helmless/google-cloudrun-chart/commit/96d614f6cf3aac876590252401cc14f75af75c81))
* **release:** make image public after publish ([eb45e02](https://github.com/helmless/google-cloudrun-chart/commit/eb45e025b3330d233253326c9212f55158e6e70c))
* **release:** reset release ([b8d2fd7](https://github.com/helmless/google-cloudrun-chart/commit/b8d2fd77ae8c14182f6fafd71bbaa2360cac11f7))
* **release:** set release package ([174037b](https://github.com/helmless/google-cloudrun-chart/commit/174037b96392db1f3d465d80b8cac76ebed0ff1b))
* **release:** tag major and minor component tags ([93dacb0](https://github.com/helmless/google-cloudrun-chart/commit/93dacb0c10db6f3ffc3b7eac26a2a7d4d536186e))
* update readme if template changes ([1998288](https://github.com/helmless/google-cloudrun-chart/commit/1998288cd54bdca645159b8f06e57c86156387bf))
