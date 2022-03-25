# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 3.1.0 (2022-03-25)


### Bug Fixes

* **autoImports:** dirs option should be string[] ([#2186](https://github.com/nuxt/framework/issues/2186)) ([ad29181](https://github.com/nuxt/framework/commit/ad2918195b18d8606952f2e9d288dc3f2eb424ee))
* **bridge:** replace nuxt 3 auto-imports ([#3850](https://github.com/nuxt/framework/issues/3850)) ([23e7afb](https://github.com/nuxt/framework/commit/23e7afb5eccf50155a5ff775791a0b5d967ffda3))
* clean up some type issues and add type test suite ([#3199](https://github.com/nuxt/framework/issues/3199)) ([42373e0](https://github.com/nuxt/framework/commit/42373e060d61d47e9c94313c273c297656d3af22))
* **config:** add analyze plugin options in bridge mode ([#3292](https://github.com/nuxt/framework/issues/3292)) ([48cc608](https://github.com/nuxt/framework/commit/48cc6086e46fefd23e0d4f3d17b9759a6b8cbbf2))
* **deps:** update dependency c12 to ^0.2.3 ([#3781](https://github.com/nuxt/framework/issues/3781)) ([2ad93eb](https://github.com/nuxt/framework/commit/2ad93eb34db6dc1a1c1b077fa4de20cb3e9c4b2d))
* **kit:** allow `src` for `addPluginTemplate` ([#3542](https://github.com/nuxt/framework/issues/3542)) ([e12d2e9](https://github.com/nuxt/framework/commit/e12d2e9405a877c871418051e496f37dad0510a2))
* **pkg:** add implicit dependencies ([#3682](https://github.com/nuxt/framework/issues/3682)) ([5c9cf9c](https://github.com/nuxt/framework/commit/5c9cf9cf9e308b7556742e69601a6fde3be191c2))
* **schema, nuxt3:** export meta types from schema ([#2103](https://github.com/nuxt/framework/issues/2103)) ([834532b](https://github.com/nuxt/framework/commit/834532bf71439338b179b0a633f5446c58181d9a))
* **schema:** allow strings in plugin config ([#2160](https://github.com/nuxt/framework/issues/2160)) ([c347b6c](https://github.com/nuxt/framework/commit/c347b6cc8afe49068ddc0aaf48aa3cf8c83c4e68))
* **schema:** allow untyped keys in nuxt config ([#3527](https://github.com/nuxt/framework/issues/3527)) ([33ffd8b](https://github.com/nuxt/framework/commit/33ffd8be0a4725d03ee745520f845060ee0e1a22))
* **schema:** extend `NuxtOptions` for nitro & bridge types ([#2131](https://github.com/nuxt/framework/issues/2131)) ([7a78bce](https://github.com/nuxt/framework/commit/7a78bce44965a51942dbfe9d924b4f941c304f33))
* **schema:** fix typo for `import.meta.globEager` ([#2243](https://github.com/nuxt/framework/issues/2243)) ([af6f91e](https://github.com/nuxt/framework/commit/af6f91e8fee2ec0542706bcd2dc661483fafae4f))
* **schema:** handle null/undefined values in `runtimeConfig` ([#2456](https://github.com/nuxt/framework/issues/2456)) ([c824905](https://github.com/nuxt/framework/commit/c824905b99c66af219a6cc2336d4f40adfc4e6de))
* **schema:** make postcss plugins a record type ([#3403](https://github.com/nuxt/framework/issues/3403)) ([720e31d](https://github.com/nuxt/framework/commit/720e31d49889caa2928b51daec4e6aa417184f06))
* **schema:** remove stray `nuxt3` import ([#2105](https://github.com/nuxt/framework/issues/2105)) ([15dad0e](https://github.com/nuxt/framework/commit/15dad0e0394aa889acd862ba98c5e548f4bb1042))
* **schema:** set static alias correctly ([#3614](https://github.com/nuxt/framework/issues/3614)) ([114cbe3](https://github.com/nuxt/framework/commit/114cbe33d05846d33ceed2819a413b9780475bec))
* **schema:** support inline module options ([#2852](https://github.com/nuxt/framework/issues/2852)) ([ed2d26f](https://github.com/nuxt/framework/commit/ed2d26f1b51158ae90b8a6d7f6dca1f24ea38f67))
* **schema:** type `render.compressor` ([#2302](https://github.com/nuxt/framework/issues/2302)) ([0d85c9e](https://github.com/nuxt/framework/commit/0d85c9ef77360fc1e56450039dc8436bd2390c69))
* update ufo ([a436d8e](https://github.com/nuxt/framework/commit/a436d8e0dc1db3eb1b72e1613619632fd3e6dfca))
* **vite-node:** entry path and executing in production ([#3854](https://github.com/nuxt/framework/issues/3854)) ([11c460f](https://github.com/nuxt/framework/commit/11c460fa99a6591a3ec8c1d7a5f062f06d990013))
* **vite,webpack:** disable async entrypoint by default ([#3375](https://github.com/nuxt/framework/issues/3375)) ([e45a780](https://github.com/nuxt/framework/commit/e45a780714c1ba44807ba6dbce3f2b5209ec0339))
* **vite:** improve logs for client vs server ([#3634](https://github.com/nuxt/framework/issues/3634)) ([570016c](https://github.com/nuxt/framework/commit/570016c143d321a78deb1d2fb3abc2238b1b731a))
* **webpack:** support absolute urls in webpack css url/import ([#3743](https://github.com/nuxt/framework/issues/3743)) ([6342e82](https://github.com/nuxt/framework/commit/6342e823a1c373f3ad85f7665cf534b457920b27))


### Features

* `.nuxtignore` support and `isIgnored` kit utility ([#3424](https://github.com/nuxt/framework/issues/3424)) ([754ff0c](https://github.com/nuxt/framework/commit/754ff0c9e7eaf3914090fbe51691b59250571eb4))
* **auto-import:** allow explicit transform exclusion patterns ([#2183](https://github.com/nuxt/framework/issues/2183)) ([ca9761d](https://github.com/nuxt/framework/commit/ca9761df9e22b54207321f1c9b3f997ad331e3c5))
* **deps:** update all non-major dependencies ([#2252](https://github.com/nuxt/framework/issues/2252)) ([23397e6](https://github.com/nuxt/framework/commit/23397e603c97b3a5b75b035ce72dbc633bbb13a5))
* improve base url options ([#2655](https://github.com/nuxt/framework/issues/2655)) ([d07d572](https://github.com/nuxt/framework/commit/d07d572263b45108e2a98a9924bf0d8dcba902fa))
* **kit:** support config `extends` using `unjs/c12` ([#3008](https://github.com/nuxt/framework/issues/3008)) ([1672148](https://github.com/nuxt/framework/commit/1672148a87106591c2af6627f7d1c76f5fa81d2e))
* **nitro, nuxt3:** allow handling otherwise unhandled runtime errors ([#3464](https://github.com/nuxt/framework/issues/3464)) ([5d58ef4](https://github.com/nuxt/framework/commit/5d58ef48afb513564e5ca9ec42007eef56b2461b))
* **nuxi:** add `typecheck` command using `vue-tsc` ([#2132](https://github.com/nuxt/framework/issues/2132)) ([f5307f9](https://github.com/nuxt/framework/commit/f5307f9d1390de851cfba4d57799188cd54dc418))
* **nuxi:** call nuxt `listen` hook for dev ([#2772](https://github.com/nuxt/framework/issues/2772)) ([4bd7ada](https://github.com/nuxt/framework/commit/4bd7adae4a7d43f7b906abec1149688d307954a3))
* **nuxt 3:** support custom router options ([#3485](https://github.com/nuxt/framework/issues/3485)) ([f38cace](https://github.com/nuxt/framework/commit/f38cacec0f7ceba448c6375d4cebd996a6ad42e9))
* **nuxt3,bridge:** add automatic schema augmentation declaration ([#3096](https://github.com/nuxt/framework/issues/3096)) ([7825e2a](https://github.com/nuxt/framework/commit/7825e2aa125a6ce9a02f4353005d02f03854b7bb))
* **nuxt3:** add middleware via route meta ([#2858](https://github.com/nuxt/framework/issues/2858)) ([dccc0c9](https://github.com/nuxt/framework/commit/dccc0c9c6faa86533ef4bcfb0117232ec631f65a))
* **nuxt3:** add support for `definePageMeta` macro ([#2678](https://github.com/nuxt/framework/issues/2678)) ([93ef422](https://github.com/nuxt/framework/commit/93ef422b5d3c86b6fefd6df5ff077f7e98648c3e))
* **nuxt3:** allow disabling vue type shims ([#2773](https://github.com/nuxt/framework/issues/2773)) ([f219f63](https://github.com/nuxt/framework/commit/f219f635adce72ea1158065fd4d6a5d6a7a5243e))
* **nuxt3:** auto generate runtime config type declarations ([#3573](https://github.com/nuxt/framework/issues/3573)) ([20f3171](https://github.com/nuxt/framework/commit/20f31712c1e1e11e57df7d08191459eec2af7e4f))
* **nuxt3:** experimental nitropack support ([#3160](https://github.com/nuxt/framework/issues/3160)) ([aece351](https://github.com/nuxt/framework/commit/aece3518b541663c1731160e42e26e6ac7c79ce8))
* **nuxt3:** middleware type generation improvements ([#2945](https://github.com/nuxt/framework/issues/2945)) ([965f2ab](https://github.com/nuxt/framework/commit/965f2abaeed72ac357710069e5a1567034930d21))
* **nuxt3:** support lazy and custom-resolved components ([#3814](https://github.com/nuxt/framework/issues/3814)) ([29078bb](https://github.com/nuxt/framework/commit/29078bba74987a5febfe769cb3454c1837ea7cff))
* **schema:** expose `RouterOptions` and `RouterConfigOptions` ([#3713](https://github.com/nuxt/framework/issues/3713)) ([3f91d83](https://github.com/nuxt/framework/commit/3f91d83a79bf501a26050acef87c6af4155e14e9))
* shared logger and silent test logs ([#3259](https://github.com/nuxt/framework/issues/3259)) ([467ab69](https://github.com/nuxt/framework/commit/467ab693b987c57efe3a8f2bcccda2464bd2f27e))
* support reactivity transform ([#3737](https://github.com/nuxt/framework/issues/3737)) ([f69126e](https://github.com/nuxt/framework/commit/f69126e8f4adb71bbed55990c97c6e2f9bdd7dec))
* **vite:** experimental `vite-node` support ([#2795](https://github.com/nuxt/framework/issues/2795)) ([ac40c97](https://github.com/nuxt/framework/commit/ac40c9746cc516ab117e9edca1c8260a7fbd83dd))
* **webpack:** add `webpack:devMiddleware` and `webpack:hotMiddleware` hooks ([#3606](https://github.com/nuxt/framework/issues/3606)) ([e891ea0](https://github.com/nuxt/framework/commit/e891ea0cca70ba3899b3d9579819c3730cfca065))
