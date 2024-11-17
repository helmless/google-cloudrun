# Changelog

## 0.1.0 (2024-11-17)


### Features

* add key value env vars to allow overwrite ([76f5664](https://github.com/serverless-helm/cloudrun/commit/76f56645b636bc7225d155b5bf7be5649281cea9))
* add release workflows ([96b12e0](https://github.com/serverless-helm/cloudrun/commit/96b12e06e4f871f7266dc8b90712252732b47791))
* bootstrap terraform and action ([57f6d95](https://github.com/serverless-helm/cloudrun/commit/57f6d95d9faa630ffcb8e6dc532fd95b5de47f44))
* create github action to deploy CloudRun Service ([#10](https://github.com/serverless-helm/cloudrun/issues/10)) ([082a700](https://github.com/serverless-helm/cloudrun/commit/082a7002e5d59207c5a2fa2bed57ed785a7e4f6c))
* initial commit of core cloudrun service chart ([eec9439](https://github.com/serverless-helm/cloudrun/commit/eec943995d0de1da3ffcd5ae2d3f06cb8649dd37))
* **release:** add root package release with major and min version tags ([d3e1fef](https://github.com/serverless-helm/cloudrun/commit/d3e1fefc55c03e0268b4d42ea1139cf791a73b32))


### Bug Fixes

* **chart:** rename chart and publish directly to org ([45301e0](https://github.com/serverless-helm/cloudrun/commit/45301e0937e928516739ebd1d3a7315494798c05))
* **ci:** allow to dispatch release ([42bc4f2](https://github.com/serverless-helm/cloudrun/commit/42bc4f20c39cfa8079b4df8d778570e9d15f43e4))
* **ci:** do not validate template against k8s ([f34dd49](https://github.com/serverless-helm/cloudrun/commit/f34dd49dfad9c4c205f13ed013e454ead6a18802))
* **ci:** only publish chart when chart is released ([72b41b3](https://github.com/serverless-helm/cloudrun/commit/72b41b3b84712aa4dcc24d6cb9307d37a0921481))
* **ci:** set concurrency group for e2e tests ([0d39426](https://github.com/serverless-helm/cloudrun/commit/0d39426c91340ffbc79917208cf7664fae946885))
* **ci:** trigger follow up workflows using an app token on release ([60490fe](https://github.com/serverless-helm/cloudrun/commit/60490fe61f68bba45990fe1afced6d89a91e32f8))
* **ci:** validate chart without k8s ([24da6d8](https://github.com/serverless-helm/cloudrun/commit/24da6d8202c9342fb06ba53b5c13ef186827b1d7))
* configure release please for all sub components ([9d1d7d2](https://github.com/serverless-helm/cloudrun/commit/9d1d7d2bc8b9b482c3b91f6d9f0f65b7a9644807))
* only release components based on path ([8c3cf37](https://github.com/serverless-helm/cloudrun/commit/8c3cf37674caae92a6cbdb344ad3ad5d71731361))
* **release:** correctly configure release-please ([c9aa289](https://github.com/serverless-helm/cloudrun/commit/c9aa2890e452b77dcb6c75ac6424cafa9b8c382d))
* **release:** correctly distinguish between component and root releases ([69fac89](https://github.com/serverless-helm/cloudrun/commit/69fac890fe689e2de41f45cc636ae5d55f705118))
* **release:** do not tag major versions ([96d614f](https://github.com/serverless-helm/cloudrun/commit/96d614f6cf3aac876590252401cc14f75af75c81))
* **release:** make image public after publish ([eb45e02](https://github.com/serverless-helm/cloudrun/commit/eb45e025b3330d233253326c9212f55158e6e70c))
* **release:** tag major and minor component tags ([93dacb0](https://github.com/serverless-helm/cloudrun/commit/93dacb0c10db6f3ffc3b7eac26a2a7d4d536186e))
* update readme if template changes ([1998288](https://github.com/serverless-helm/cloudrun/commit/1998288cd54bdca645159b8f06e57c86156387bf))


### Documentation

* add quick instructions to deploy manifest ([b12a660](https://github.com/serverless-helm/cloudrun/commit/b12a660a4cc9e60478d966eb37efe9bc8579981a))
* add quick ref to helm chart in docs ([2d14e75](https://github.com/serverless-helm/cloudrun/commit/2d14e75a90cc6a927294698db5ac1474697fa7e5))
* **cloudrun:** add helm chart documentation ([0b00fca](https://github.com/serverless-helm/cloudrun/commit/0b00fcaf98fcb190078d3597010a00857f50842a))


### Miscellaneous

* cleanup release [skip ci] ([d8bea2c](https://github.com/serverless-helm/cloudrun/commit/d8bea2c8d0dcfd11089dec6d55fe796316e8067b))
* **deps:** bump azure/setup-helm from 3 to 4 ([5fc0d99](https://github.com/serverless-helm/cloudrun/commit/5fc0d998d3242397fb30c2773446c50233e5d5ba))
* **deps:** bump softprops/action-gh-release from 1 to 2 ([a4ae2f1](https://github.com/serverless-helm/cloudrun/commit/a4ae2f155b6c6ee10924e12d7b47fc1f3b353541))
* **main:** release action 0.1.0 ([#5](https://github.com/serverless-helm/cloudrun/issues/5)) ([9d2532f](https://github.com/serverless-helm/cloudrun/commit/9d2532f2a9fa556c7ee1b8acb3e18aa2b7bc77cd))
* **main:** release chart 0.1.0 ([49d7ada](https://github.com/serverless-helm/cloudrun/commit/49d7ada9581efc6e9c8798a04c58a4905fad562b))
* **main:** release chart 0.1.0 ([3ed0b4e](https://github.com/serverless-helm/cloudrun/commit/3ed0b4e0c8738d502bf4cab79c5957b889271af9))
* **main:** release chart 0.1.0 ([4501ce6](https://github.com/serverless-helm/cloudrun/commit/4501ce68601feecc2f1838dfcd20c801eeac8505))
* release-please-config.json ([8c2f5cf](https://github.com/serverless-helm/cloudrun/commit/8c2f5cfd3e98f045580d988f3e239f3c710e3990))
* update gitignore ([3c19d5e](https://github.com/serverless-helm/cloudrun/commit/3c19d5e2feb5fbfa230e3272447429cefcd34b04))
