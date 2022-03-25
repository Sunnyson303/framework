# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 3.1.0 (2022-03-25)


### Bug Fixes

* allow use of nuxt3 in non-wsl windows environment ([#308](https://github.com/nuxt/framework/issues/308)) ([0a3041c](https://github.com/nuxt/framework/commit/0a3041cdf9e3a2a76ee93117557d7be6df1b95e3))
* **app:** separate plugin entrypoints ([#366](https://github.com/nuxt/framework/issues/366)) ([f980ef2](https://github.com/nuxt/framework/commit/f980ef235f5184b36db69bb8b571563727b929d9))
* **bridge:** plugin default detection ([#1847](https://github.com/nuxt/framework/issues/1847)) ([202617b](https://github.com/nuxt/framework/commit/202617bdd1d1509c9bef4c1a089f9e70d78931fb))
* clean up some type issues and add type test suite ([#3199](https://github.com/nuxt/framework/issues/3199)) ([42373e0](https://github.com/nuxt/framework/commit/42373e060d61d47e9c94313c273c297656d3af22))
* issues with externals outside of rootDir ([4e18653](https://github.com/nuxt/framework/commit/4e1865358c1597cb68cc96bef2b30e2811fcd899))
* **nuxt3:** use shared module for dynamic paths ([#3757](https://github.com/nuxt/framework/issues/3757)) ([7458dd1](https://github.com/nuxt/framework/commit/7458dd1aa676cac9c81ad37ce39207ede55c39d7))
* **pkg:** downgrade node version to 14.16.x due to stackblitz issue ([4526af7](https://github.com/nuxt/framework/commit/4526af78a9a64e2b5f08dd80ec5a1725871f52fe))
* **pkg:** downgrade node version to 14.17.x due to codesandbox issue ([8db76fc](https://github.com/nuxt/framework/commit/8db76fcf2ea63218d3a367b8c1719bed69871d44))
* **pkg:** enable declaration for for and webpack ([317fc55](https://github.com/nuxt/framework/commit/317fc5553942d11f30139d790942217bcc102e83))
* **pkg:** support node 17.x  in the engines field ([#1443](https://github.com/nuxt/framework/issues/1443)) ([4f9c87b](https://github.com/nuxt/framework/commit/4f9c87b99a2f9729f868c6580623174350ec4ce6))
* source map for webpack nuxt-setup-loader ([#236](https://github.com/nuxt/framework/issues/236)) ([5832782](https://github.com/nuxt/framework/commit/58327824fb273b8875fb313ad84059b4c3e180e2))
* update ufo ([a436d8e](https://github.com/nuxt/framework/commit/a436d8e0dc1db3eb1b72e1613619632fd3e6dfca))
* **vite, webpack:** add missing dependencies ([#3547](https://github.com/nuxt/framework/issues/3547)) ([d404484](https://github.com/nuxt/framework/commit/d404484c6168f78c4ef35e5bcd0d58ab925a79c7))
* **vite,webpack:** disable async entrypoint by default ([#3375](https://github.com/nuxt/framework/issues/3375)) ([e45a780](https://github.com/nuxt/framework/commit/e45a780714c1ba44807ba6dbce3f2b5209ec0339))
* **webpack:** detect postcss config and show warning ([#1805](https://github.com/nuxt/framework/issues/1805)) ([256d9b1](https://github.com/nuxt/framework/commit/256d9b1424af579a32a91bdfe29640453d8e1362))
* **webpack:** don't inline scoped packages ([0a74f1e](https://github.com/nuxt/framework/commit/0a74f1e2392b45024f3af20f3ded4bb6545911fc))
* **webpack:** enable minimize for client production bundles ([#404](https://github.com/nuxt/framework/issues/404)) ([5a1ccec](https://github.com/nuxt/framework/commit/5a1ccec61f256a0b75fb9bd30b9322409cf07199))
* **webpack:** exclude ! for externals ([daaf02f](https://github.com/nuxt/framework/commit/daaf02f5e4dd19d907d511f4a139f36d11db1b5b))
* **webpack:** exclude assets from webpack externals ([#471](https://github.com/nuxt/framework/issues/471)) ([8aaa1b3](https://github.com/nuxt/framework/commit/8aaa1b3124e932251cad2e040fc4451c532c65a8))
* **webpack:** find asset modules of chunk ([#198](https://github.com/nuxt/framework/issues/198)) ([8740ece](https://github.com/nuxt/framework/commit/8740ece29e8e2dbeac02742685d0e17c5ccf44ca))
* **webpack:** import `esbuild-loader` as commonjs ([#2460](https://github.com/nuxt/framework/issues/2460)) ([c288907](https://github.com/nuxt/framework/commit/c288907f7203cc5638077340d067898231887ccc))
* **webpack:** prevent implicit externalising ([#2829](https://github.com/nuxt/framework/issues/2829)) ([9660cd8](https://github.com/nuxt/framework/commit/9660cd821201163c1de16b63984ceb72ea8cb1e4))
* **webpack:** remove MiniCssExtractPlugin.loader options ([#2217](https://github.com/nuxt/framework/issues/2217)) ([#2218](https://github.com/nuxt/framework/issues/2218)) ([cad09fe](https://github.com/nuxt/framework/commit/cad09fe9b352b5ce5baa6b2c3f565f6dd1ce1e25))
* **webpack:** support jsx syntax in esbuild ([#1014](https://github.com/nuxt/framework/issues/1014)) ([080f497](https://github.com/nuxt/framework/commit/080f497eeeeddf6aa2290d007fc0a389864ef8d7))
* **webpack:** typecheck postcss plugins and add missing `postcss-import` (resolves [#544](https://github.com/nuxt/framework/issues/544)) ([57f435a](https://github.com/nuxt/framework/commit/57f435a59f02b707301c913e96a7fd9497ce479e))
* **webpack:** use cjs for emitted webpack files ([#395](https://github.com/nuxt/framework/issues/395)) ([bb75704](https://github.com/nuxt/framework/commit/bb757045ec1b0f35b5b88b0d08e2381cbcd9eb59))
* windows path issues ([#408](https://github.com/nuxt/framework/issues/408)) ([25e96bb](https://github.com/nuxt/framework/commit/25e96bb8962689103b9b42c09ef37d59397fac0c))
* workaround for `vue/server-renderer` import, close [#563](https://github.com/nuxt/framework/issues/563) ([#566](https://github.com/nuxt/framework/issues/566)) ([c8f8691](https://github.com/nuxt/framework/commit/c8f86914962bbbca900415aea26de95f71653059))
* workaround for `vue` 3.2.18+ esm bundle issue and revert [#566](https://github.com/nuxt/framework/issues/566) ([#578](https://github.com/nuxt/framework/issues/578)) ([#578](https://github.com/nuxt/framework/issues/578)) ([0c14b0a](https://github.com/nuxt/framework/commit/0c14b0a48ba82fbb49dfef3acf3c380a86b4fe49))


### Features

* add hook signatures and basic typings ([#79](https://github.com/nuxt/framework/issues/79)) ([dacde63](https://github.com/nuxt/framework/commit/dacde630634700172ccd54a1e4f1d0469b28bd30))
* **app:** make `asyncData` working with `<script setup nuxt>` ([#220](https://github.com/nuxt/framework/issues/220)) ([11a5a3e](https://github.com/nuxt/framework/commit/11a5a3e14f739761fd4ad65e60290b3abc7a9692))
* **deps:** update all non-major dependencies ([#2252](https://github.com/nuxt/framework/issues/2252)) ([23397e6](https://github.com/nuxt/framework/commit/23397e603c97b3a5b75b035ce72dbc633bbb13a5))
* improve base url options ([#2655](https://github.com/nuxt/framework/issues/2655)) ([d07d572](https://github.com/nuxt/framework/commit/d07d572263b45108e2a98a9924bf0d8dcba902fa))
* initial version of nu cli ([#54](https://github.com/nuxt/framework/issues/54)) ([a030c62](https://github.com/nuxt/framework/commit/a030c62d29ba871f94a7152c7d5fa36d4de1d3b6))
* **nitro, vite:** use native module ([#252](https://github.com/nuxt/framework/issues/252)) ([6318438](https://github.com/nuxt/framework/commit/63184384157adc2688a8b556a0b397dfbf45901e))
* **nuxi:** bundle analyzer ([#701](https://github.com/nuxt/framework/issues/701)) ([f0b9474](https://github.com/nuxt/framework/commit/f0b9474b40312a0c24cf520ffe76db0cdb9094bd))
* **nuxt3:** expose `/app` export paths ([#3323](https://github.com/nuxt/framework/issues/3323)) ([70542a3](https://github.com/nuxt/framework/commit/70542a3af737a18daf0b2f829ecd0e072fd2af24))
* **nuxt3:** middleware type generation improvements ([#2945](https://github.com/nuxt/framework/issues/2945)) ([965f2ab](https://github.com/nuxt/framework/commit/965f2abaeed72ac357710069e5a1567034930d21))
* **nuxt3:** remove `<script setup>` transform and prefer top level await ([#579](https://github.com/nuxt/framework/issues/579)) ([e13baf9](https://github.com/nuxt/framework/commit/e13baf9867cd0d8f9981105de4d051858316a4ea))
* optional pages and refactor nuxt3 ([#142](https://github.com/nuxt/framework/issues/142)) ([6b62d45](https://github.com/nuxt/framework/commit/6b62d456d7fe8c9dd92803a30dcebf0d481f65c7))
* shared logger and silent test logs ([#3259](https://github.com/nuxt/framework/issues/3259)) ([467ab69](https://github.com/nuxt/framework/commit/467ab693b987c57efe3a8f2bcccda2464bd2f27e))
* support `ssr: false` ([#351](https://github.com/nuxt/framework/issues/351)) ([be25577](https://github.com/nuxt/framework/commit/be255772b26cb78398af020a1dbb5d367425218f))
* support reactivity transform ([#3737](https://github.com/nuxt/framework/issues/3737)) ([f69126e](https://github.com/nuxt/framework/commit/f69126e8f4adb71bbed55990c97c6e2f9bdd7dec))
* update vite implementation ([#130](https://github.com/nuxt/framework/issues/130)) ([9732d63](https://github.com/nuxt/framework/commit/9732d63c74b394706150ef35cc06c65d3fb185ad))
* use native esm for all packages ([#539](https://github.com/nuxt/framework/issues/539)) ([6e49637](https://github.com/nuxt/framework/commit/6e496373f3bdffb3416d0c543ad82b0a92891167))
* use virtual filesystem for templates ([#292](https://github.com/nuxt/framework/issues/292)) ([bec2720](https://github.com/nuxt/framework/commit/bec27209303418990e31761f3d6e4f5e8e503abb))
* use webpack esm server build ([#474](https://github.com/nuxt/framework/issues/474)) ([193d7bf](https://github.com/nuxt/framework/commit/193d7bf8bc24618b63e1f67ffcf6d9d0e4e7d10e))
* **webpack:** add `webpack:devMiddleware` and `webpack:hotMiddleware` hooks ([#3606](https://github.com/nuxt/framework/issues/3606)) ([e891ea0](https://github.com/nuxt/framework/commit/e891ea0cca70ba3899b3d9579819c3730cfca065))
* **webpack:** bring back postcss and postcss-loader ([#532](https://github.com/nuxt/framework/issues/532)) ([d05d882](https://github.com/nuxt/framework/commit/d05d8821a0d25d9e203e0fd65ca16ca8f15aa8a5))


### Performance Improvements

* **webpack:** use fs cache by default ([5d5183e](https://github.com/nuxt/framework/commit/5d5183ee82f0d1567934c9cd13160bf84bddd8d3))
