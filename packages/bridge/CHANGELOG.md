# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 3.1.0 (2022-03-25)


### Bug Fixes

* add main entrypoints for packages ([#629](https://github.com/nuxt/framework/issues/629)) ([0a9342c](https://github.com/nuxt/framework/commit/0a9342c02d2e22873135fb605c81279e28631065))
* **auto-imports:** windows issue with parsing query from path ([#3700](https://github.com/nuxt/framework/issues/3700)) ([cb6a4e9](https://github.com/nuxt/framework/commit/cb6a4e97c1146ab9e35e979837b6d8aa30de8390))
* **bridge:** add `nitro:generate` hook ([#3044](https://github.com/nuxt/framework/issues/3044)) ([5d7f99b](https://github.com/nuxt/framework/commit/5d7f99be1d85692513fd4270284523f3cf71681b))
* **bridge:** add `useState` to auto-imports ([#1087](https://github.com/nuxt/framework/issues/1087)) ([ab7aef8](https://github.com/nuxt/framework/commit/ab7aef8a139ecccb0ad69c2fe9ac0c67f3489d7e))
* **bridge:** add additional vue composition-api resolutions ([#614](https://github.com/nuxt/framework/issues/614)) ([a2da8a0](https://github.com/nuxt/framework/commit/a2da8a0a83d08baebe037e2e90ec14a3176ba48e))
* **bridge:** add docs links and warnings for data composables ([#2010](https://github.com/nuxt/framework/issues/2010)) ([c184211](https://github.com/nuxt/framework/commit/c1842116817323e56127451cbd8ccc78c75e46df))
* **bridge:** add implemented runtime nuxt hooks ([#3872](https://github.com/nuxt/framework/issues/3872)) ([236faf9](https://github.com/nuxt/framework/commit/236faf9cc6b5797a3f8a616e3bbaae43a8532430))
* **bridge:** add implicit dependencies ([4837b92](https://github.com/nuxt/framework/commit/4837b92e57d1b059b0c6c26070a6957065214c73))
* **bridge:** add meta to cjs wrapper (closes [#671](https://github.com/nuxt/framework/issues/671)) ([4572661](https://github.com/nuxt/framework/commit/45726616b2c623c6ae847d604c578e0c6c82621e))
* **bridge:** add missing `globby` and `scule` dependencies ([b421c81](https://github.com/nuxt/framework/commit/b421c81e8490c94710a7f7f56610dcd352d8f29b))
* **bridge:** add missing process flags for vite ([#2736](https://github.com/nuxt/framework/issues/2736)) ([e27a017](https://github.com/nuxt/framework/commit/e27a0173e8a656d8d75c70a580e3145a66f547b1))
* **bridge:** add modules with hooks after all other modules ([#3239](https://github.com/nuxt/framework/issues/3239)) ([7c9b0a3](https://github.com/nuxt/framework/commit/7c9b0a358ddadf8cb2f276c28294dfa346d0fb23))
* **bridge:** add schema.d.ts to nuxt.d.ts ([#3237](https://github.com/nuxt/framework/issues/3237)) ([07c14b8](https://github.com/nuxt/framework/commit/07c14b87045ca94346919a573e40bc6dd7999568))
* **bridge:** add vuex alias ([#1026](https://github.com/nuxt/framework/issues/1026)) ([4a34c2a](https://github.com/nuxt/framework/commit/4a34c2a75be5f7bbe4c48451456fcaab274ddd67))
* **bridge:** alias direct references to vue files ([#847](https://github.com/nuxt/framework/issues/847)) ([d5127e9](https://github.com/nuxt/framework/commit/d5127e95acfe1e4b124bf022c0949a793565b495))
* **bridge:** always add `components.d.ts` reference ([#2246](https://github.com/nuxt/framework/issues/2246)) ([6e719d6](https://github.com/nuxt/framework/commit/6e719d69774d2c2214ac789eb6f79d340816dfe1))
* **bridge:** automatically transpile all modules (and sanitize transpiles) ([#677](https://github.com/nuxt/framework/issues/677)) ([0aa6fbf](https://github.com/nuxt/framework/commit/0aa6fbf5ef4b447561035703e4afcd07fe6fa0c1))
* **bridge:** build fails with SSR turned off ([#2708](https://github.com/nuxt/framework/issues/2708)) ([2b86345](https://github.com/nuxt/framework/commit/2b86345e9e4bc4dbac88a8001eac73f4a73e50a9))
* **bridge:** can't enable vite mode ([#1505](https://github.com/nuxt/framework/issues/1505)) ([7ede9b1](https://github.com/nuxt/framework/commit/7ede9b14d9ebd0c59845a43599f07819d97a3515))
* **bridge:** default export detection ([#1774](https://github.com/nuxt/framework/issues/1774)) ([39db33d](https://github.com/nuxt/framework/commit/39db33d625f39c9684adfacf66d541e078ce591d))
* **bridge:** define `head` with `vue-meta` type ([#784](https://github.com/nuxt/framework/issues/784)) ([2a0afbd](https://github.com/nuxt/framework/commit/2a0afbd09296cd65d30c5ef5a5324d64149bc3fe))
* **bridge:** detect conflict with `@nuxt/typescript-build` usage ([#672](https://github.com/nuxt/framework/issues/672)) ([ac16127](https://github.com/nuxt/framework/commit/ac16127a13e8282d7a7b5fa3e56b8fbf9cc64b1b))
* **bridge:** detect existence of `@nuxt/bridge-edge` ([#1575](https://github.com/nuxt/framework/issues/1575)) ([f60f461](https://github.com/nuxt/framework/commit/f60f4614103385aeb22c4337221e807264a9bd9b))
* **bridge:** disable legacy fetch polyfills ([#1866](https://github.com/nuxt/framework/issues/1866)) ([850ef69](https://github.com/nuxt/framework/commit/850ef69a878294bb2854fdfe07d1d8bc71d0d52d))
* **bridge:** do not resolve esm babel helpers ([#1158](https://github.com/nuxt/framework/issues/1158)) ([adf4970](https://github.com/nuxt/framework/commit/adf497046b38ddd917a7bb0e18ea94eaf8fb2dd2))
* **bridge:** don't error with `defineNuxtMiddleware` ([#676](https://github.com/nuxt/framework/issues/676)) ([2fc0829](https://github.com/nuxt/framework/commit/2fc0829dd23d9e10e88123de20970eeb7e612924))
* **bridge:** don't instantiate vite builder if only preparing types ([#3050](https://github.com/nuxt/framework/issues/3050)) ([8edd481](https://github.com/nuxt/framework/commit/8edd4819c967a9c6c3cdbcb7dd1a03a90126b056))
* **bridge:** don't override existing `baseURL` property ([#2827](https://github.com/nuxt/framework/issues/2827)) ([beaa369](https://github.com/nuxt/framework/commit/beaa369892c62b23ef9a1f03aa846821a00e8a49))
* **bridge:** don't rely on auto-imports in internal plugin ([#700](https://github.com/nuxt/framework/issues/700)) ([8df2967](https://github.com/nuxt/framework/commit/8df29679ce477fa2d045ff451f24e02a31ada5b9))
* **bridge:** downgrade estree-walker dependency ([#600](https://github.com/nuxt/framework/issues/600)) ([041b60f](https://github.com/nuxt/framework/commit/041b60f48e0d08329267ab9d9e1edf2ee64581e6))
* **bridge:** emit types for module ([#660](https://github.com/nuxt/framework/issues/660)) ([0213adc](https://github.com/nuxt/framework/commit/0213adcd20ceecd06a55154c8805e8ab45cf080b))
* **bridge:** enable vite build by default ([#1709](https://github.com/nuxt/framework/issues/1709)) ([91b428e](https://github.com/nuxt/framework/commit/91b428eeea2c86ffbf7d13a102da9e7c84bf71d6))
* **bridge:** ensure `vue` ts alias points to original vue ([#1924](https://github.com/nuxt/framework/issues/1924)) ([4b367a1](https://github.com/nuxt/framework/commit/4b367a1959f11db2e9b8681f82ff4f8bb2035c05))
* **bridge:** execute metaInfo function ([#3258](https://github.com/nuxt/framework/issues/3258)) ([289d54e](https://github.com/nuxt/framework/commit/289d54eb24d1d8885ac834dccabd3d6d8f83b3aa))
* **bridge:** expose `nuxi` command ([#1599](https://github.com/nuxt/framework/issues/1599)) ([b49c62b](https://github.com/nuxt/framework/commit/b49c62b3353843dfcfb57a1e9cea2c320430aa05))
* **bridge:** fix fouc on vite ([#1515](https://github.com/nuxt/framework/issues/1515)) ([0f329ea](https://github.com/nuxt/framework/commit/0f329ea8710079b7b2da4fb318f6ffcd6fa2ec58))
* **bridge:** fixed reactivity on csr of useState reactive payload ([#2134](https://github.com/nuxt/framework/issues/2134)) ([ae80e5b](https://github.com/nuxt/framework/commit/ae80e5bdc804b8d1bc1e586b774be3a75a886da3))
* **bridge:** generate `dist/runtime` ([9c14b88](https://github.com/nuxt/framework/commit/9c14b886e8c28945611d730135ee7121c15e584c))
* **bridge:** handle `ssr: false` ([#489](https://github.com/nuxt/framework/issues/489)) ([3304f75](https://github.com/nuxt/framework/commit/3304f75b50479a8f1861aea31266037882901ec2))
* **bridge:** handle static nested vite dirs ([#3565](https://github.com/nuxt/framework/issues/3565)) ([ef38147](https://github.com/nuxt/framework/commit/ef38147e52656e80f5ae8ba733558bed2c67addf))
* **bridge:** import nuxt3 src from relative path ([eb03321](https://github.com/nuxt/framework/commit/eb0332126e07bf93a38a77175a96e68c0d6c528a))
* **bridge:** improve warnings for `@nuxtjs/composition-api` migration ([#1237](https://github.com/nuxt/framework/issues/1237)) ([2256b2b](https://github.com/nuxt/framework/commit/2256b2b86ad7248cac6859114ba609c6d0954413))
* **bridge:** install bridge module at the end ([#2611](https://github.com/nuxt/framework/issues/2611)) ([8fff48b](https://github.com/nuxt/framework/commit/8fff48b8dfc347915cea1107247a2d6a5ec41144))
* **bridge:** mark `defineNuxtMiddleware` as unsupprted ([b332462](https://github.com/nuxt/framework/commit/b332462b2ae7fb323cfad6a5e318f02f48264dbb)), closes [#1317](https://github.com/nuxt/framework/issues/1317)
* **bridge:** normalize strings in vite middleware template ([#2319](https://github.com/nuxt/framework/issues/2319)) ([3e82f0f](https://github.com/nuxt/framework/commit/3e82f0f2cb0c815af898ad78118104a476ee1f8e))
* **bridge:** plugin default detection ([#1847](https://github.com/nuxt/framework/issues/1847)) ([202617b](https://github.com/nuxt/framework/commit/202617bdd1d1509c9bef4c1a089f9e70d78931fb))
* **bridge:** port nested `_nuxt` dir fix to bridge vite ([#3538](https://github.com/nuxt/framework/issues/3538)) ([919db5b](https://github.com/nuxt/framework/commit/919db5b51449b4332b0898623d5529317d585198))
* **bridge:** remove circular reference ([#844](https://github.com/nuxt/framework/issues/844)) ([b6065a2](https://github.com/nuxt/framework/commit/b6065a2edf05ca7a9d54560c1c442d2dd3b543fa))
* **bridge:** remove duplicated log ([#2087](https://github.com/nuxt/framework/issues/2087)) ([a12df69](https://github.com/nuxt/framework/commit/a12df6977892b14564a6a87385db440d64a2396f))
* **bridge:** remove falsy values from `created` and `mounted` ([#2182](https://github.com/nuxt/framework/issues/2182)) ([ae6f095](https://github.com/nuxt/framework/commit/ae6f095ee88110852f5e6ba9e1f11d97769a54e4))
* **bridge:** replace nuxt 3 auto-imports ([#3850](https://github.com/nuxt/framework/issues/3850)) ([23e7afb](https://github.com/nuxt/framework/commit/23e7afb5eccf50155a5ff775791a0b5d967ffda3))
* **bridge:** resolve `browser` condition above `main` for client ([#641](https://github.com/nuxt/framework/issues/641)) ([d51ed1e](https://github.com/nuxt/framework/commit/d51ed1e6aaa4d30540f805e5a5381bd6e3c1e629))
* **bridge:** respect `--fail-on-error` in generation ([#3134](https://github.com/nuxt/framework/issues/3134)) ([c02e368](https://github.com/nuxt/framework/commit/c02e3683eb98214e33a55a1f838cb9e3595f30de))
* **bridge:** respect custom `app.html` ([#2339](https://github.com/nuxt/framework/issues/2339)) ([279bfdc](https://github.com/nuxt/framework/commit/279bfdc5b3682e8b301c0f808c0d6e8e40fde2b0))
* **bridge:** revert optimization exclusion for `vue-demi` ([#1932](https://github.com/nuxt/framework/issues/1932)) ([fb2e8cc](https://github.com/nuxt/framework/commit/fb2e8ccba5a2aab8279616ac5b2d289195cf874a))
* **bridge:** set `app.basePath` ([#2808](https://github.com/nuxt/framework/issues/2808)) ([6abf75d](https://github.com/nuxt/framework/commit/6abf75d40ab2e3a62f2f590db6ec01482e5607c3))
* **bridge:** set webpack as implicit external ([0b3271d](https://github.com/nuxt/framework/commit/0b3271d2751a78f8a16faf22767da658b8569ec9))
* **bridge:** support newer js targets with webpack ([#3131](https://github.com/nuxt/framework/issues/3131)) ([a9ba1ca](https://github.com/nuxt/framework/commit/a9ba1ca90757d9dbe9a9cd1f8e2082488dd77c83))
* **bridge:** type `useNuxtApp()` ([#3057](https://github.com/nuxt/framework/issues/3057)) ([c82d353](https://github.com/nuxt/framework/commit/c82d3533bcc8a8977e6bfd3d1fd5854f60570227))
* **bridge:** typo fix ([#1168](https://github.com/nuxt/framework/issues/1168)) ([0c93733](https://github.com/nuxt/framework/commit/0c937339b95e44886b6d0fce7e91041e95c3971f))
* **bridge:** update `useContext` ([#1871](https://github.com/nuxt/framework/issues/1871)) ([7cc526c](https://github.com/nuxt/framework/commit/7cc526ce69a541782f16023deb5104dc51068615))
* **bridge:** use esm  for `unplugin-vue2-script-setup` ([#690](https://github.com/nuxt/framework/issues/690)) ([a4e903e](https://github.com/nuxt/framework/commit/a4e903e55eb512a5615636a01af434624927cba0))
* **bridge:** use typescript directory entry ([#3365](https://github.com/nuxt/framework/issues/3365)) ([c806d05](https://github.com/nuxt/framework/commit/c806d05b7a6dc13c34c6b2029094a7bbb148323e))
* **bridge:** use vue server build ([#3515](https://github.com/nuxt/framework/issues/3515)) ([a5e19b1](https://github.com/nuxt/framework/commit/a5e19b1c576d80eb80891a057efd95e370dd808b))
* **config:** add analyze plugin options in bridge mode ([#3292](https://github.com/nuxt/framework/issues/3292)) ([48cc608](https://github.com/nuxt/framework/commit/48cc6086e46fefd23e0d4f3d17b9759a6b8cbbf2))
* ensure debounced/async handlers run in order ([#3656](https://github.com/nuxt/framework/issues/3656)) ([14b3225](https://github.com/nuxt/framework/commit/14b32258e8bae9722a905efdaa5306d5f8ef4c7d))
* **nitro, nuxi:** add runtimeConfig types (for `#config` and `useRuntimeConfig()`) ([#1783](https://github.com/nuxt/framework/issues/1783)) ([13a8e2b](https://github.com/nuxt/framework/commit/13a8e2b163684f2b2517c534e4da447c4bc16e5b))
* **nuxi,nuxt3,bridge:** generate all templates with `nuxi prepare` ([#2409](https://github.com/nuxt/framework/issues/2409)) ([03cc191](https://github.com/nuxt/framework/commit/03cc1913a357b11428b7636757a679fed27b9cf0))
* **nuxi:** ignore static check with `prepare` command ([#1971](https://github.com/nuxt/framework/issues/1971)) ([496ea09](https://github.com/nuxt/framework/commit/496ea0977702c2e0e5c0c3d89e55ee2ce36cbed6))
* **nuxt3,bridge:** correctly reference router from client-side helper ([#3281](https://github.com/nuxt/framework/issues/3281)) ([56aabd6](https://github.com/nuxt/framework/commit/56aabd606d341989c214de30f9cb5f28a22f9fbc))
* **nuxt3:** add missing auto imports ([#1735](https://github.com/nuxt/framework/issues/1735)) ([5b8e10f](https://github.com/nuxt/framework/commit/5b8e10f28ec0ec70fdabc222de3d79169ed0aff3))
* **nuxt3:** include `error` and `pending` values in asyncData state ([#2130](https://github.com/nuxt/framework/issues/2130)) ([955fa36](https://github.com/nuxt/framework/commit/955fa364faec39bd09555704082f435aa3ff3d52))
* **nuxt3:** prevent removing and re-adding tags before mount ([#3212](https://github.com/nuxt/framework/issues/3212)) ([ef69e74](https://github.com/nuxt/framework/commit/ef69e746d2a4a03dc391d7e5efca8f125988b7a6))
* **nuxt3:** share scanned components with loader ([#3396](https://github.com/nuxt/framework/issues/3396)) ([52d22fe](https://github.com/nuxt/framework/commit/52d22feaea6008392ed42f4dd43c63e4da21d87e))
* **pkg:** add implicit dependencies ([#3682](https://github.com/nuxt/framework/issues/3682)) ([5c9cf9c](https://github.com/nuxt/framework/commit/5c9cf9cf9e308b7556742e69601a6fde3be191c2))
* **pkg:** downgrade node version to 14.16.x due to stackblitz issue ([4526af7](https://github.com/nuxt/framework/commit/4526af78a9a64e2b5f08dd80ec5a1725871f52fe))
* **pkg:** downgrade node version to 14.17.x due to codesandbox issue ([8db76fc](https://github.com/nuxt/framework/commit/8db76fcf2ea63218d3a367b8c1719bed69871d44))
* **pkg:** support node 17.x  in the engines field ([#1443](https://github.com/nuxt/framework/issues/1443)) ([4f9c87b](https://github.com/nuxt/framework/commit/4f9c87b99a2f9729f868c6580623174350ec4ce6))
* sanitize import filenames in generated imports ([#2216](https://github.com/nuxt/framework/issues/2216)) ([29171bd](https://github.com/nuxt/framework/commit/29171bd1053e24132b3ab23ac50535edde6b2323))
* **schema:** extend `NuxtOptions` for nitro & bridge types ([#2131](https://github.com/nuxt/framework/issues/2131)) ([7a78bce](https://github.com/nuxt/framework/commit/7a78bce44965a51942dbfe9d924b4f941c304f33))
* update ufo ([a436d8e](https://github.com/nuxt/framework/commit/a436d8e0dc1db3eb1b72e1613619632fd3e6dfca))
* upgrade vite to 2.7.12 ([#2716](https://github.com/nuxt/framework/issues/2716)) ([33ebb01](https://github.com/nuxt/framework/commit/33ebb01d7f0c25b5b89b767d9a0749084b0946c4))
* use `cookie-es` ([8994b5a](https://github.com/nuxt/framework/commit/8994b5a3682054ce1aed42b6bc14856db750ae46))
* use `perfect-debounce` to handle trailing run of promise ([#3679](https://github.com/nuxt/framework/issues/3679)) ([ff88d91](https://github.com/nuxt/framework/commit/ff88d91baea8ea24c301f674a8ffeba569e9ea48))
* **vite, bridge:** avoid vite resolving `tsconfig.json` ([#1677](https://github.com/nuxt/framework/issues/1677)) ([85f3985](https://github.com/nuxt/framework/commit/85f39858e5ee7e5c714479acb3e5f177066a7e07))
* **vite:** don't replace `process.env` ([#1543](https://github.com/nuxt/framework/issues/1543)) ([f5aea9f](https://github.com/nuxt/framework/commit/f5aea9f742eadad8b917843d343741fc6e4fa50e))
* **vite:** improve external checks for dev-bundler ([#1538](https://github.com/nuxt/framework/issues/1538)) ([bdbfa36](https://github.com/nuxt/framework/commit/bdbfa3698790e9dc655954ab5f985790ca408075))
* **vite:** include dynamic css (revert [#2067](https://github.com/nuxt/framework/issues/2067)) ([#2227](https://github.com/nuxt/framework/issues/2227)) ([29a2eb3](https://github.com/nuxt/framework/commit/29a2eb3dc11968893b6c5faed33e1248d1498367))
* **vite:** invalidate virtual modules when templates are regenerated ([#2725](https://github.com/nuxt/framework/issues/2725)) ([4728fd5](https://github.com/nuxt/framework/commit/4728fd545e46f4af81f2db302b7a5b37ffdbab39))
* **vite:** remove `global` replacement ([#1835](https://github.com/nuxt/framework/issues/1835)) ([6eb4040](https://github.com/nuxt/framework/commit/6eb4040b23e1346047791056ef536c0e61b119d2))
* **vite:** remove conflicting vite aliases ([#1624](https://github.com/nuxt/framework/issues/1624)) ([eb67eb9](https://github.com/nuxt/framework/commit/eb67eb919e5eda969eb7b317e35c0c8c2419513c))
* **vite:** respect users config ([#2395](https://github.com/nuxt/framework/issues/2395)) ([737f1bf](https://github.com/nuxt/framework/commit/737f1bf80c69746f1d1778ff9da2c262a241981c))
* **vite:** separate dynamic deps in dev-bundler ([#2067](https://github.com/nuxt/framework/issues/2067)) ([a149225](https://github.com/nuxt/framework/commit/a149225e6362c3ca90f017671e97898b0697417d))
* **vite:** swap `<link>` style on dev ssr ([#1712](https://github.com/nuxt/framework/issues/1712)) ([85d173d](https://github.com/nuxt/framework/commit/85d173d6530a683d573e08ffe951e21800983158))


### Features

* `useState` composable ([#719](https://github.com/nuxt/framework/issues/719)) ([666b7f1](https://github.com/nuxt/framework/commit/666b7f1ba8db6c24f4d5c0fbe7e8fbf3ee6e03d9))
* **auto-imports:** allow extending with config and hooks ([#1167](https://github.com/nuxt/framework/issues/1167)) ([0ab477c](https://github.com/nuxt/framework/commit/0ab477cad05e74a92d2c23f1002e54f4d6930242))
* **bridge, nuxt3:** expose equivalent `useRoute` and `useRouter` com… ([#615](https://github.com/nuxt/framework/issues/615)) ([71e71d1](https://github.com/nuxt/framework/commit/71e71d13273c604b12bde55fc53f1cde92adf62d))
* **bridge, nuxt3:** mock vue-demi ([#1849](https://github.com/nuxt/framework/issues/1849)) ([f298386](https://github.com/nuxt/framework/commit/f298386795ffdd19dcead9b044c1fb4cb2b7c639))
* **bridge:** add `useNuxt2Meta()` composable ([#1789](https://github.com/nuxt/framework/issues/1789)) ([29599f0](https://github.com/nuxt/framework/commit/29599f06a1e5a88001f88181785e066a87c7b3e5))
* **bridge:** add `useNuxtApp` and `defineNuxtPlugin` composables ([#576](https://github.com/nuxt/framework/issues/576)) ([3bf8568](https://github.com/nuxt/framework/commit/3bf856830ba28ef48f7f28df7949562324fb191c))
* **bridge:** add support for `<script setup>` ([#678](https://github.com/nuxt/framework/issues/678)) ([11490cd](https://github.com/nuxt/framework/commit/11490cdd7da54699068ec0d3cea54b4a2c2ce23e))
* **bridge:** add support for `useNuxt2Meta` in plugins ([#3187](https://github.com/nuxt/framework/issues/3187)) ([d046c96](https://github.com/nuxt/framework/commit/d046c9620b3a25fba7ba08351e2cebe58da3b626))
* **bridge:** add support for legacy composition api helpers ([#584](https://github.com/nuxt/framework/issues/584)) ([ad9d2d1](https://github.com/nuxt/framework/commit/ad9d2d190659f9f560d198a9dfecdb9142c48e83))
* **bridge:** allow accessing injections from `useNuxtApp` ([#1623](https://github.com/nuxt/framework/issues/1623)) ([5aa33b8](https://github.com/nuxt/framework/commit/5aa33b807cddccb35ec559f8223495ea1e0f96d3))
* **bridge:** allow user-defined `scriptSetup` options ([#2185](https://github.com/nuxt/framework/issues/2185)) ([ac98373](https://github.com/nuxt/framework/commit/ac98373b4c606078a93e50b7b69e4451af6a6ad1))
* **bridge:** auto-inject based on `provide` key from plugins ([#3536](https://github.com/nuxt/framework/issues/3536)) ([856c01a](https://github.com/nuxt/framework/commit/856c01ab42391a747e2bf2ba5ad88c78caac2c3a))
* **bridge:** better resolution within wp4 (with fallback) ([#608](https://github.com/nuxt/framework/issues/608)) ([2b51af7](https://github.com/nuxt/framework/commit/2b51af76d8330f7fa60e798ca7ced49390aea5f4))
* **bridge:** enable automatic global imports for nuxt2 ([#609](https://github.com/nuxt/framework/issues/609)) ([b712de9](https://github.com/nuxt/framework/commit/b712de9aa28fed5ae014c4bc9542e2deff39d91d))
* **bridge:** enable composition-api ([#551](https://github.com/nuxt/framework/issues/551)) ([fc019b8](https://github.com/nuxt/framework/commit/fc019b88169fe1ad47bf962f966c0976f83cc907))
* **bridge:** generate components declarations ([#2174](https://github.com/nuxt/framework/issues/2174)) ([8a6db58](https://github.com/nuxt/framework/commit/8a6db589fec7323bdd2932755326f3bc42e7ba39))
* **bridge:** init function for `useState` ([#773](https://github.com/nuxt/framework/issues/773)) ([2fb58ae](https://github.com/nuxt/framework/commit/2fb58ae2bec264c559a851d5b8807cd21d8b0aef))
* **bridge:** support `addRouteMiddleware`, `navigateTo` and `abortNavigation` ([#3193](https://github.com/nuxt/framework/issues/3193)) ([3c563fa](https://github.com/nuxt/framework/commit/3c563fa48f2c580aabe5130b44aecf1191bcca59))
* **bridge:** upgrade unplugin-vue2-script-setup ([#2687](https://github.com/nuxt/framework/issues/2687)) ([baa0853](https://github.com/nuxt/framework/commit/baa0853afa230ca9c4bdabb7db2b98275f59fcc8))
* **bridge:** use `useMeta` in bridge projects ([#664](https://github.com/nuxt/framework/issues/664)) ([a07b67c](https://github.com/nuxt/framework/commit/a07b67ce577f37dc2356c02b1c078ecf6a8aab82))
* define nitro `#storage` and `#assets` types ([#1377](https://github.com/nuxt/framework/issues/1377)) ([281790e](https://github.com/nuxt/framework/commit/281790e0366d8bcc1bf8da01b68d33f41270ed7c))
* **deps:** update all non-major dependencies ([#2252](https://github.com/nuxt/framework/issues/2252)) ([23397e6](https://github.com/nuxt/framework/commit/23397e603c97b3a5b75b035ce72dbc633bbb13a5))
* export `defineNuxtConfig` from `nuxt3` and `@nuxt/bridge` ([#669](https://github.com/nuxt/framework/issues/669)) ([dd73a8b](https://github.com/nuxt/framework/commit/dd73a8bcad8d61d8a1ed20cac7dfdacdb2fc3663))
* improve base url options ([#2655](https://github.com/nuxt/framework/issues/2655)) ([d07d572](https://github.com/nuxt/framework/commit/d07d572263b45108e2a98a9924bf0d8dcba902fa))
* **kit, bridge:**  version constraint utils and checks ([#442](https://github.com/nuxt/framework/issues/442)) ([9503d62](https://github.com/nuxt/framework/commit/9503d6260740d77d0be428247473804e3cc89c3d))
* **nitro, nuxt3:** allow handling otherwise unhandled runtime errors ([#3464](https://github.com/nuxt/framework/issues/3464)) ([5d58ef4](https://github.com/nuxt/framework/commit/5d58ef48afb513564e5ca9ec42007eef56b2461b))
* **nitro:** automatically type middleware/api routes ([#708](https://github.com/nuxt/framework/issues/708)) ([b005b24](https://github.com/nuxt/framework/commit/b005b2403fae51ea5a70070a9f09f6b5e5f85be2))
* **nitro:** update dependencies for node-fetch 3.x support ([#1373](https://github.com/nuxt/framework/issues/1373)) ([c803536](https://github.com/nuxt/framework/commit/c80353637e423af7612a5b9bfe802246ec3a71df))
* nuxt bridge ([#459](https://github.com/nuxt/framework/issues/459)) ([44458fc](https://github.com/nuxt/framework/commit/44458fcbbba8adde7068f8c71372b7c2f16e3ac2))
* **nuxt3, bridge:**  `useCookie` universal composable ([#2085](https://github.com/nuxt/framework/issues/2085)) ([9920181](https://github.com/nuxt/framework/commit/9920181df3798cb6a54e0a353b8676c48d5fc1de))
* **nuxt3, bridge:** `useReqHeaders` composable ([#2173](https://github.com/nuxt/framework/issues/2173)) ([5ab1816](https://github.com/nuxt/framework/commit/5ab18162ddb5a91cb43c0e6e7a2c529f6e9247f3))
* **nuxt3, bridge:** add `vue:setup` hook ([#2408](https://github.com/nuxt/framework/issues/2408)) ([e674d0f](https://github.com/nuxt/framework/commit/e674d0f60d52e26122ce54f6c82a5723f8fc8e23))
* **nuxt3, bridge:** add lazy helpers (`useLazyAsyncData` and `useLazyFetch`) ([#1861](https://github.com/nuxt/framework/issues/1861)) ([f011a60](https://github.com/nuxt/framework/commit/f011a60daea24e94336fcc3cc40c18a2c9a5362e))
* **nuxt3, bridge:** useRuntimeConfig ([#625](https://github.com/nuxt/framework/issues/625)) ([45b4946](https://github.com/nuxt/framework/commit/45b494602634156bf1188be714709898f3b01cea))
* **nuxt3,bridge:** add automatic schema augmentation declaration ([#3096](https://github.com/nuxt/framework/issues/3096)) ([7825e2a](https://github.com/nuxt/framework/commit/7825e2aa125a6ce9a02f4353005d02f03854b7bb))
* **nuxt3:** `useFetch` ([#721](https://github.com/nuxt/framework/issues/721)) ([54c57e3](https://github.com/nuxt/framework/commit/54c57e3987f87aa2be0d6ad15995302bf907baa7))
* **nuxt3:** `useFetch` with dynamic reactive request ([#3731](https://github.com/nuxt/framework/issues/3731)) ([fb15082](https://github.com/nuxt/framework/commit/fb150825ceebbffddd49b312962bef9e6f3ed1b5))
* **nuxt3:** add universal routing utilities ([#3274](https://github.com/nuxt/framework/issues/3274)) ([dbab979](https://github.com/nuxt/framework/commit/dbab979a2ed28b8f3d02044079f6b9039114d5ff))
* **nuxt3:** auto generate runtime config type declarations ([#3573](https://github.com/nuxt/framework/issues/3573)) ([20f3171](https://github.com/nuxt/framework/commit/20f31712c1e1e11e57df7d08191459eec2af7e4f))
* **nuxt3:** expose `/app` export paths ([#3323](https://github.com/nuxt/framework/issues/3323)) ([70542a3](https://github.com/nuxt/framework/commit/70542a3af737a18daf0b2f829ecd0e072fd2af24))
* **nuxt:** add wrapped `useRoute` and `useRouter` composables ([#2406](https://github.com/nuxt/framework/issues/2406)) ([6c1cb11](https://github.com/nuxt/framework/commit/6c1cb11b9522e22c6d4e4791506420ca7a572761))
* **router:** add proper server side redirection to navigateTo ([#3684](https://github.com/nuxt/framework/issues/3684)) ([99705f7](https://github.com/nuxt/framework/commit/99705f77c0ac814bc4c326631f419ff70fc0bfb6))
* shared logger and silent test logs ([#3259](https://github.com/nuxt/framework/issues/3259)) ([467ab69](https://github.com/nuxt/framework/commit/467ab693b987c57efe3a8f2bcccda2464bd2f27e))
* use native esm for all packages ([#539](https://github.com/nuxt/framework/issues/539)) ([6e49637](https://github.com/nuxt/framework/commit/6e496373f3bdffb3416d0c543ad82b0a92891167))


### Performance Improvements

* **bridge:** allow skipping legacy composition api support ([#2388](https://github.com/nuxt/framework/issues/2388)) ([daec432](https://github.com/nuxt/framework/commit/daec4323bb69072e0a7e0c907de8d844a1a8f8c2))
* **ssr:** disable vite's pre-trasnfroming to improve perf ([#2574](https://github.com/nuxt/framework/issues/2574)) ([e9128f3](https://github.com/nuxt/framework/commit/e9128f39a2be278f9ef3021a47ec7b8ead3933bf))
