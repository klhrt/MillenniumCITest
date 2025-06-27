# 1.0.0 (2025-06-27)


### Bug Fixes

* (Linux) Fix python binary paths ([76b40ff](https://github.com/klhrt/MillenniumCITest/commit/76b40ffaaec77eccf99ce85a2e30cf9fe05d85b6))
* (Linux) Permission & bug fixes ([56af75f](https://github.com/klhrt/MillenniumCITest/commit/56af75f8cee7bfd33d78badadfb3aa63cc5605ea))
* Accidentally linked client to webkit in dev build ([844fd0b](https://github.com/klhrt/MillenniumCITest/commit/844fd0ba4aff617ab2865054403e61f2a101d052))
* Actually fix the CI. ([6051ee2](https://github.com/klhrt/MillenniumCITest/commit/6051ee2fa4e307633cd143fced91c2507a39bf24))
* Add file description and details to help prevent false positives. ([0fd35ad](https://github.com/klhrt/MillenniumCITest/commit/0fd35ad6e91f84b2e0119cad9e478de79eb050f1))
* Add proxy support for web requests within Steam. ([71dabc6](https://github.com/klhrt/MillenniumCITest/commit/71dabc6c5299de1f3b5dd2053dad5f3d4a8856a7))
* Add start script support for non-arch based distros. ([cda3843](https://github.com/klhrt/MillenniumCITest/commit/cda3843693a18e44ae7fdc1bfe9d0c3b6340fa4a))
* add time to logger module ([80da7fb](https://github.com/klhrt/MillenniumCITest/commit/80da7fba4cf03b44bef70994ded5141fce659d9c))
* allow frontend function to send booleans & numbers to backend ([#198](https://github.com/klhrt/MillenniumCITest/issues/198)) ([aa4f054](https://github.com/klhrt/MillenniumCITest/commit/aa4f0547ca68ed3f3480a401de9b81c7e28f26bb))
* Allow importing raw files like fonts, images, etc. from the webkit. ([fd82cd1](https://github.com/klhrt/MillenniumCITest/commit/fd82cd1ad9fae9c8e956d53b3e627164659a88bb))
* **bug:** fix socket disconnect ([84439b3](https://github.com/klhrt/MillenniumCITest/commit/84439b3cb0e8508d83ea899cd5205e2381ab13d1))
* Catch installer socket being used instead of crashing. ([8817735](https://github.com/klhrt/MillenniumCITest/commit/88177355d74b53ad7671e35831f6c050f842172c))
* Check if a queried plugin is already loaded before starting it ([5fa6d99](https://github.com/klhrt/MillenniumCITest/commit/5fa6d998b5938c410689dbeb9bb6461425813c87))
* Check if jq is installed ([#109](https://github.com/klhrt/MillenniumCITest/issues/109)) ([319c814](https://github.com/klhrt/MillenniumCITest/commit/319c81453331370ca63bc3ed8cf8227fef4712d7))
* **CI:** Fix asset processor ([bdedd20](https://github.com/klhrt/MillenniumCITest/commit/bdedd20abea101f09afc512c7196466b71974356))
* **CI:** Fix CI ([b897b49](https://github.com/klhrt/MillenniumCITest/commit/b897b4901fa53ba8a76860c368a30b240ff129e6))
* **CI:** Fix CI ([914df34](https://github.com/klhrt/MillenniumCITest/commit/914df34aef0f8b531f01e9c7dde8be5dd6543a3d))
* **CI:** Fix dependency issue on linux ([7e91f54](https://github.com/klhrt/MillenniumCITest/commit/7e91f54d19c4b4735e5dd15fdf43ee13013865a5))
* **CI:** use pnpm instead of npm and cache vcpkg properly ([d58e2a8](https://github.com/klhrt/MillenniumCITest/commit/d58e2a859fd2739bf0787824a28b30e9e77a341c))
* Close installer after successful install ([cfd961c](https://github.com/klhrt/MillenniumCITest/commit/cfd961c54b59808b625a9dfbe077ae29940998b5))
* Closes [#159](https://github.com/klhrt/MillenniumCITest/issues/159) ([2f43350](https://github.com/klhrt/MillenniumCITest/commit/2f433503b506bf3c1366df1bec6abfe4eef5cfa4))
* Create debugger flag from installer instead of Millennium ([652945d](https://github.com/klhrt/MillenniumCITest/commit/652945d0bd377e34cfef4ee7be127c74db515f5f))
* de-increment version ([de72207](https://github.com/klhrt/MillenniumCITest/commit/de72207047dd3a02cbdb14ca4a4262aaf2ebe682))
* Decrease release binary size on linux ([dd0600a](https://github.com/klhrt/MillenniumCITest/commit/dd0600ac8906d81ffc281566ea4ec839f54a2a64))
* **deps:** add pnpm to deps in pkgbuild ([5a081f7](https://github.com/klhrt/MillenniumCITest/commit/5a081f77c1fc27ee16e477eb30741bc43fd04bb1))
* Disable theme updater for compatibility until further notice ([6861a45](https://github.com/klhrt/MillenniumCITest/commit/6861a456bf868113af201f817646b075ac1c083b))
* Enable automatic proxy detection on Windows ([#219](https://github.com/klhrt/MillenniumCITest/issues/219)) ([f15c932](https://github.com/klhrt/MillenniumCITest/commit/f15c9324fe8187c6acdf35ae176f6d9814f9cc18))
* Error in Swedish localization fixed ([71211ca](https://github.com/klhrt/MillenniumCITest/commit/71211ca5150f88f87854155076f422649165a03f))
* Fix "object not found" error from package manager. ([bb01e9c](https://github.com/klhrt/MillenniumCITest/commit/bb01e9cc201e5af74170033ac935586d0054d9ec))
* Fix [#253](https://github.com/klhrt/MillenniumCITest/issues/253) [#159](https://github.com/klhrt/MillenniumCITest/issues/159) [#148](https://github.com/klhrt/MillenniumCITest/issues/148) ?? ([bebdfb5](https://github.com/klhrt/MillenniumCITest/commit/bebdfb5b08f183e0793e80204accf90ab5c6ee6e))
* Fix all issues with steam re-opening unskinned, and the UI freezing ([6f5cd67](https://github.com/klhrt/MillenniumCITest/commit/6f5cd6715b6c7201c9b246ec8d887a893917d753))
* fix AUR package build ([e6156d5](https://github.com/klhrt/MillenniumCITest/commit/e6156d5e8e274d4491c524f37d500bc126b5d7e3))
* Fix AUR PKGBUILD ([3badb80](https://github.com/klhrt/MillenniumCITest/commit/3badb80b5c687a21e636d2871dda480a3365e67c))
* Fix Brazilian localization ([a2dd9f5](https://github.com/klhrt/MillenniumCITest/commit/a2dd9f534e7bff838ec61ef7e36299d6105654b4))
* Fix Brazilian Portuguese locales ([2596ffb](https://github.com/klhrt/MillenniumCITest/commit/2596ffba381e5084e115a3ee80aa886b38f446ea))
* fix build structure on windows ([88236a8](https://github.com/klhrt/MillenniumCITest/commit/88236a861cf319c4ca43783e546154143d59d830))
* Fix CI ([997747d](https://github.com/klhrt/MillenniumCITest/commit/997747dabdca59c87268b56356f1540651ecb275))
* Fix CI ([0465205](https://github.com/klhrt/MillenniumCITest/commit/0465205991313d833ef9321fcb0c0e136d05a26d))
* Fix CI ([6704435](https://github.com/klhrt/MillenniumCITest/commit/6704435d1a000ec84e53ea0892b91031060caa05))
* Fix CI ([966fc22](https://github.com/klhrt/MillenniumCITest/commit/966fc22422e1b38c6f09c81984f57b53c8445ba7))
* Fix CI ([c952fbf](https://github.com/klhrt/MillenniumCITest/commit/c952fbf10f0af532e86430bbc8b37c99fff44aa8))
* Fix CI asset packer ([47cf6c6](https://github.com/klhrt/MillenniumCITest/commit/47cf6c66409ae94b4c00f1a29f4889c564378c71))
* Fix CI not building Millennium API properly ([9564eb2](https://github.com/klhrt/MillenniumCITest/commit/9564eb2d075f950b939442624441d24a8a62e95a))
* Fix CI output paths ([9bf0b09](https://github.com/klhrt/MillenniumCITest/commit/9bf0b09e3ed3c8b8c160e5f30198f86b66b9e967))
* Fix CLI paths to use updated refs ([59b91dd](https://github.com/klhrt/MillenniumCITest/commit/59b91ddd70e8593f55e3731850ce16d0eb392a48))
* Fix color analyzer not properly parsing color name and description. ([8f8893b](https://github.com/klhrt/MillenniumCITest/commit/8f8893bf752ff813b59f18f5c184a4a0ac55b3a5))
* Fix config paths on linux ([07576b9](https://github.com/klhrt/MillenniumCITest/commit/07576b9ea51af006eecb050039a16ccedbf6240b))
* Fix crashes on Steam close ([4d09aa6](https://github.com/klhrt/MillenniumCITest/commit/4d09aa688dd31758a222f5a9d44761fcb4086e14))
* Fix crashing on new installs ([9b7e1e5](https://github.com/klhrt/MillenniumCITest/commit/9b7e1e52b21556c6935112b92233ea75b52b69ba))
* Fix custom accent color using RGBA instead of RGB. closes [#229](https://github.com/klhrt/MillenniumCITest/issues/229) ([4b095d6](https://github.com/klhrt/MillenniumCITest/commit/4b095d68693d18575ebde21a9b29c3bd8b6f9c28))
* Fix debugger port reporting error when the port was not being used. ([00d1b89](https://github.com/klhrt/MillenniumCITest/commit/00d1b89dd54581d4b618a67564e417caee6cf3df))
* Fix edge case SEGV ([b17146d](https://github.com/klhrt/MillenniumCITest/commit/b17146d3febe448c577bf19ac9107f931e93144b))
* Fix encoding issue when calling a JS method from the backend. ([d03134c](https://github.com/klhrt/MillenniumCITest/commit/d03134ce679dfc7dfe4e5c77a3e4462e577011b0))
* Fix FFI propagating backend call on plugins with no backend. ([cbb873d](https://github.com/klhrt/MillenniumCITest/commit/cbb873dd06d3afddf4dee7b283a8a2262915e101))
* Fix German locales ([f9b4347](https://github.com/klhrt/MillenniumCITest/commit/f9b4347fcfd7f5dff3d8a31d61266a7c7ba66365))
* Fix install script failing if the username is 'user'. closes [#343](https://github.com/klhrt/MillenniumCITest/issues/343) ([e3c04c6](https://github.com/klhrt/MillenniumCITest/commit/e3c04c67422d1fe4c4b016736320f0bbed869b43))
* Fix installer crashes (again) ([bfafcb7](https://github.com/klhrt/MillenniumCITest/commit/bfafcb79253fb0fb3475b35e87229dfa11c2471a))
* Fix installer extracting ghost files ([96e238e](https://github.com/klhrt/MillenniumCITest/commit/96e238e86d2bc4ba35d550f40a54c8d3322f3c41))
* Fix installer script ([fb4053d](https://github.com/klhrt/MillenniumCITest/commit/fb4053dcb299311daac5df20dcca3409d3298af7))
* Fix issues where target port is "taken" when it's actually open and usable. [#122](https://github.com/klhrt/MillenniumCITest/issues/122) ([ffce333](https://github.com/klhrt/MillenniumCITest/commit/ffce333834b8e255c815def3b2d68d5bf4045310))
* Fix issues with the plugin example crashing. ([8624fab](https://github.com/klhrt/MillenniumCITest/commit/8624fab5942c684291edc1c0b8a090731dcd91c0))
* Fix libcurl & confusing logs ([c997a8c](https://github.com/klhrt/MillenniumCITest/commit/c997a8c549ab3f7c8cf9097e5137ee00eb8d664e))
* Fix linux startup issues [#75](https://github.com/klhrt/MillenniumCITest/issues/75) ([dad87ba](https://github.com/klhrt/MillenniumCITest/commit/dad87ba8ba76f4df4ff033f14f68d2c53651a85f))
* Fix Mac OS support. ([6b9997b](https://github.com/klhrt/MillenniumCITest/commit/6b9997be621223c0fb1ce64c4c09aa8fc7d68f93))
* fix macos build. note: no macos release is being actively developed. this is simply a build fix; nothing more. ([560245f](https://github.com/klhrt/MillenniumCITest/commit/560245fd3b6192bb69b827304f14012a77dd2713))
* Fix Millennium breaking certain webpages, and prevented it from interacting with sensitive URLs like PayPal. ([106b286](https://github.com/klhrt/MillenniumCITest/commit/106b286fcd2a4000eafccaa0b54ee8dbfd069c46))
* Fix Millennium button not showing on some languages. ([b1c107c](https://github.com/klhrt/MillenniumCITest/commit/b1c107c9b92d5f1aafd411dd674ce8f12cc10764))
* fix Millennium finding incorrect API modules. ([906e6a4](https://github.com/klhrt/MillenniumCITest/commit/906e6a456f951e992a7bfbc2a505c6e84adfaa1f))
* Fix Millennium freezing if a plugin makes an FFI call to a backend that can't acquire the GIL. ([a7e3e1c](https://github.com/klhrt/MillenniumCITest/commit/a7e3e1c3d9d476d9078d238c45750cef4b34bf04))
* Fix millennium not evaluating symlinks properly ([46e34f7](https://github.com/klhrt/MillenniumCITest/commit/46e34f7d2b0cb0fc4370f4c9221af0ff76b99c96))
* Fix Millennium not shutting down properly & improved developer warnings on potential issues ([b960bfe](https://github.com/klhrt/MillenniumCITest/commit/b960bfe070effe26a5e55d80202089fe77155798))
* Fix Millennium on Linux ([30f400d](https://github.com/klhrt/MillenniumCITest/commit/30f400de02c56fd394d1b9c42d492298cf36c571))
* Fix Millennium showing updates when none are actually available ([ee26150](https://github.com/klhrt/MillenniumCITest/commit/ee2615032b3c0b2b1c093cc60368c9b83f02644c))
* Fix Millennium trying to inject CSS as JS ([4e1cc7f](https://github.com/klhrt/MillenniumCITest/commit/4e1cc7f01476847716760602a231dbe179b8b0b1))
* Fix Millennium trying to update to an older version if you're on a beta/alpha release. ([328aedd](https://github.com/klhrt/MillenniumCITest/commit/328aedd06b9b2a1b79bebbb4c04de7f2a0ac13ce))
* Fix OpenSSL issues ([78f8fa4](https://github.com/klhrt/MillenniumCITest/commit/78f8fa4276bd897bff5c838858e8ca1f3a74e0cb))
* Fix overlay browser not loading on pages without a response phrase. ([7d0fbcf](https://github.com/klhrt/MillenniumCITest/commit/7d0fbcf365f0d6a7f3d163a3f265c1cf45c595ec))
* Fix package manager to maintain backwards compatibility with old requirements.txt format ([aee4361](https://github.com/klhrt/MillenniumCITest/commit/aee4361bae99dbee8088ff2ad58fffaa3ec27e82))
* Fix PKGBUILD to use arch based FS ([b9c78f8](https://github.com/klhrt/MillenniumCITest/commit/b9c78f80c57211a88490d6c5580bf7082eaeb73f))
* Fix plugin downloader on linux ([f1c8f51](https://github.com/klhrt/MillenniumCITest/commit/f1c8f5194bbbdd75b3531999b9ee8c32ba2dd90f))
* fix plugin installer popping out of main window. ([3058d43](https://github.com/klhrt/MillenniumCITest/commit/3058d43b69775b85c8cf4fa6d87147cc674b8b6f))
* Fix plugin JS being removed from webkit when a new theme is selected. ([a29c7df](https://github.com/klhrt/MillenniumCITest/commit/a29c7df0aeb1114bfb0c1c515231ce5fa7faf5fb))
* Fix plugin shutdowns to an extent ([738919c](https://github.com/klhrt/MillenniumCITest/commit/738919c789dab9b99df186febb910311fc264e68))
* Fix plugin updater sometimes extracting to wrong path, updating while plugin is running, and fixed backend memory management issues., ([7c47e88](https://github.com/klhrt/MillenniumCITest/commit/7c47e887a948c2f83d51ba5108814f35e0ff62d0))
* Fix plugin webkit shims not injecting after plugin enable. ([3c6de9f](https://github.com/klhrt/MillenniumCITest/commit/3c6de9fdfbd6913e43de0582d99c0dc52ea99e50))
* fix plugins installing to wrong folder ([20a9ad7](https://github.com/klhrt/MillenniumCITest/commit/20a9ad7c76a6211613dcf4a341e02ac328418da1))
* fix Quick Access Menu being empty when no plugins are configurable. ([c37b200](https://github.com/klhrt/MillenniumCITest/commit/c37b20048ceb6f45c54ae3d2727d1046dcf4bc2b))
* Fix race condition causing boot loop ([f3c9e88](https://github.com/klhrt/MillenniumCITest/commit/f3c9e881eca3642885eb953801dc6dcc4bcd0058))
* Fix race condition causing Millennium to get stuck on "Notifying frontend of backend load..." ([63973b2](https://github.com/klhrt/MillenniumCITest/commit/63973b293cfb22f6f1803cc3e46eee8353f4b5cb))
* Fix race condition on startup ([b4131ef](https://github.com/klhrt/MillenniumCITest/commit/b4131efa0650e480ee064782e9f5b27ec4875eb2))
* Fix README.md code line stats ([afafdf7](https://github.com/klhrt/MillenniumCITest/commit/afafdf7f24aa920ededb16dfdd9c9a53e8595bbd))
* Fix Semantic Release docs ([1f1a36c](https://github.com/klhrt/MillenniumCITest/commit/1f1a36ce0ab10d967269055108bcded0f0a9bb7f))
* Fix semantic release version stubs ([7b436d7](https://github.com/klhrt/MillenniumCITest/commit/7b436d783c35c6637bfd045f5989822497867f96))
* Fix settings icons not being centered and plugin settings button not having propper styling ([#184](https://github.com/klhrt/MillenniumCITest/issues/184)) ([5fddc2d](https://github.com/klhrt/MillenniumCITest/commit/5fddc2db498d84a1da321c1301fafa1baac106fc))
* Fix setup tools not updating before installing required packages. ([cf6b67b](https://github.com/klhrt/MillenniumCITest/commit/cf6b67b43c6160f491a06b3671d15db215fe8d24))
* Fix SharedJSContext being missed on certain edge cases ([364e1c0](https://github.com/klhrt/MillenniumCITest/commit/364e1c087f3e1f17e842c283f1ea2bda349ec6b6))
* Fix SharedJSContext not connecting when debugging Steam. ([1095977](https://github.com/klhrt/MillenniumCITest/commit/10959772484d8f255a12337c65fd54ccf75f5123))
* Fix simplified chinese locales ([d061953](https://github.com/klhrt/MillenniumCITest/commit/d061953b65022e9ccb0c0c63ae1f3848d36aaa35))
* Fix simultaneous backend calls crashing python interpreter. ([1272230](https://github.com/klhrt/MillenniumCITest/commit/12722306c3112fdd73d3928b9e1d7d1ca52647e6))
* Fix skin not applying after BPM exit [#96](https://github.com/klhrt/MillenniumCITest/issues/96) ([ba9e001](https://github.com/klhrt/MillenniumCITest/commit/ba9e001c92f24e0d5420e41ae696789601b0285f))
* fix some browser css & js not removing properly when unloading a theme. closes [#356](https://github.com/klhrt/MillenniumCITest/issues/356) ([677e6cc](https://github.com/klhrt/MillenniumCITest/commit/677e6ccc9126ccd2227cef90a182556716409c6e))
* Fix Spanish locales ([57de823](https://github.com/klhrt/MillenniumCITest/commit/57de823c89084c9cc36d67754c5c897d069f1c53))
* Fix spanish localization ([594b7d1](https://github.com/klhrt/MillenniumCITest/commit/594b7d1aef34d910f29ff32ed7a6706903984bde))
* Fix startup bugs on Windows [#76](https://github.com/klhrt/MillenniumCITest/issues/76) ([b86c537](https://github.com/klhrt/MillenniumCITest/commit/b86c537b42ae5e11bf9793b2d7ab696e9fedcd96))
* Fix startup crashes ([b00dd37](https://github.com/klhrt/MillenniumCITest/commit/b00dd378e63daa976ae5e1fa0770a1133b742ee3))
* Fix startup crashes [#153](https://github.com/klhrt/MillenniumCITest/issues/153) ([256bc77](https://github.com/klhrt/MillenniumCITest/commit/256bc778d47e2b2428c5366310ddd725334f4bb1))
* Fix startup issues on Linux ([9fcf293](https://github.com/klhrt/MillenniumCITest/commit/9fcf29307737bee8b1ca9473548b3958756f474d))
* Fix startup issues on windows [#76](https://github.com/klhrt/MillenniumCITest/issues/76) ([aa2ade2](https://github.com/klhrt/MillenniumCITest/commit/aa2ade25f58da642c68b8305778d8b2619253369))
* Fix std::future_error by mutex ([75dd852](https://github.com/klhrt/MillenniumCITest/commit/75dd852d1991e17c0aa17c34a80ad41d9036ac1a))
* Fix Steam freezing after PC sleep ([8c3dcbd](https://github.com/klhrt/MillenniumCITest/commit/8c3dcbd6c7d474a59fc299a975eefccd9f32f53b))
* Fix Steam UI not showing on launch. ([52ad028](https://github.com/klhrt/MillenniumCITest/commit/52ad0289042de64d16b35a8429c610a96ae55667))
* Fix Steam webhelper hanging it by force crashing it, instead of relying on CEF reload. ([df65b37](https://github.com/klhrt/MillenniumCITest/commit/df65b37a7d7cbfbe00fe21a11c056108c9c88186))
* Fix system accent color not working on some startups ([2eb7a94](https://github.com/klhrt/MillenniumCITest/commit/2eb7a943a951fe965d5e749c6b04b0573918d1d8))
* Fix system error message box ([8751660](https://github.com/klhrt/MillenniumCITest/commit/8751660b3ffb1db36d4f7b3d065c0870343ee856))
* Fix the "Bug Reports" tab not working 🤦‍♂️ ([236b68e](https://github.com/klhrt/MillenniumCITest/commit/236b68e8bbab34f768d7f63aaf376aced20afbac))
* Fix the artifact CI ([3faf711](https://github.com/klhrt/MillenniumCITest/commit/3faf7111cbecab18d6351abc9a8d55746c88085e))
* Fix the AUR PKGBUILD (hopefully) ([3fbacbf](https://github.com/klhrt/MillenniumCITest/commit/3fbacbf2484227de78c02442f75b92808de08a4a))
* Fix the CI ([f416425](https://github.com/klhrt/MillenniumCITest/commit/f4164253ee85991907b93ad54bfb16e9025af504))
* Fix the CI ([7c29d23](https://github.com/klhrt/MillenniumCITest/commit/7c29d23fecaf2f3f6b760bf95f5d368db87e2a3f))
* Fix the CI building against the wrong version of Millennium. ([e12f160](https://github.com/klhrt/MillenniumCITest/commit/e12f1609e681a11b676515a67cc4df264ecb53e4))
* Fix the Linux build ([8936dcf](https://github.com/klhrt/MillenniumCITest/commit/8936dcf6fdfd34caa0b889b9d4b267fa0cfc2449))
* Fix theme editor. ([6446ebe](https://github.com/klhrt/MillenniumCITest/commit/6446ebe8b7d60dce828ce318a83009f9d1634a0b))
* Fix theme installer not working ([559ae66](https://github.com/klhrt/MillenniumCITest/commit/559ae6617d79f2772bace63d3df1b4f049b764c2))
* Fix threaded race condition ([08ab88d](https://github.com/klhrt/MillenniumCITest/commit/08ab88dc37a614c965b1b6f4d83d7953a7c688a6))
* Fix typo in install.sh ([#178](https://github.com/klhrt/MillenniumCITest/issues/178)) ([76349b3](https://github.com/klhrt/MillenniumCITest/commit/76349b3aa7374a67b408fad9583b0073164abb8d)), closes [#4](https://github.com/klhrt/MillenniumCITest/issues/4)
* Fix typo in welcome modal. ([e06c3c1](https://github.com/klhrt/MillenniumCITest/commit/e06c3c163f4e6bb1ed17fc44ddcec7f09e411651))
* Fix typo on themes page [#168](https://github.com/klhrt/MillenniumCITest/issues/168) ([e05ec19](https://github.com/klhrt/MillenniumCITest/commit/e05ec1962999e57a4662b8391a0b379e3a2c82ee))
* Fix uninstaller bugs and improve cleanup ([a923e2a](https://github.com/klhrt/MillenniumCITest/commit/a923e2aca843c44ff8063db5169f33be8bce8ef7))
* Fix uninstaller core ([cd5c5e3](https://github.com/klhrt/MillenniumCITest/commit/cd5c5e3aff4efc95516442b609d3fc4cc99fbf22))
* Fix unix pathing ([07dc66c](https://github.com/klhrt/MillenniumCITest/commit/07dc66cc0d707153e976d52b3fe981694c1fa5b3))
* Fix Unix start script paths ([f4f2bb7](https://github.com/klhrt/MillenniumCITest/commit/f4f2bb7675e5e3a0ead907f69385683624624d63))
* Fix updater bug. ([acb0437](https://github.com/klhrt/MillenniumCITest/commit/acb0437367736cecbd5d65123e08620ed043f24b))
* Fix updater not restarting steam properly ([2ece336](https://github.com/klhrt/MillenniumCITest/commit/2ece33607904656847ac1594f6e3b8a7094e5a2f))
* Fix version number ([0581521](https://github.com/klhrt/MillenniumCITest/commit/05815210ffbf5d9f60c9d6108113ecbef3ca715c))
* Fix watchdog threading errors ([cd0531b](https://github.com/klhrt/MillenniumCITest/commit/cd0531b44826ccb781f9286d4cb6734a5cba7844))
* Fix webkit and CSP related issues. closes [#197](https://github.com/klhrt/MillenniumCITest/issues/197), [#196](https://github.com/klhrt/MillenniumCITest/issues/196), [#194](https://github.com/klhrt/MillenniumCITest/issues/194) ([e2cd49d](https://github.com/klhrt/MillenniumCITest/commit/e2cd49dd7b4911ededf5d16c5446f0221de35d4e))
* Fix webkit issues, Close [#194](https://github.com/klhrt/MillenniumCITest/issues/194), [#196](https://github.com/klhrt/MillenniumCITest/issues/196) ([2c91a95](https://github.com/klhrt/MillenniumCITest/commit/2c91a9517bbe662e5227304c63dafdbfabee7ac9))
* Fix webkit patcher edge cases on redirects ([2573215](https://github.com/klhrt/MillenniumCITest/commit/25732155fc5c4cb8a2d1b036b63a404b495eae94))
* Fix webkit patcher skipping non-secure requests. ([b9a6d0d](https://github.com/klhrt/MillenniumCITest/commit/b9a6d0d0fef4f66f5bf0bd027dd45e98f710ff21))
* Fix welcome modal not highlighting Millennium properly ([703e9d3](https://github.com/klhrt/MillenniumCITest/commit/703e9d376b748e2b878859d81e4169eaba8c0e24))
* fix windows build not working. ([5b63615](https://github.com/klhrt/MillenniumCITest/commit/5b63615e182b55982ed9a53cd6077c0e7edee915))
* Fix workshop pages not rendering HTML. ([4614cc8](https://github.com/klhrt/MillenniumCITest/commit/4614cc81776ed0731d5324723a0466a2a74537d0))
* Fix wrong Millennium version being put as the developer console title. ([41cfeef](https://github.com/klhrt/MillenniumCITest/commit/41cfeef5f4174337c293a5950fc0329433f8302d))
* Fully fix plugin hot reloadability. Plugins can now be loaded/unloaded at any time, in any order ([af651b5](https://github.com/klhrt/MillenniumCITest/commit/af651b5482044be0128b302131a2a6f31c5638ac))
* Generic bug fixes ([82a0b11](https://github.com/klhrt/MillenniumCITest/commit/82a0b11664d2f8949064ccdc421cae39f86ce433))
* Grammer correction and Swedish localization ([#289](https://github.com/klhrt/MillenniumCITest/issues/289)) ([d4f433c](https://github.com/klhrt/MillenniumCITest/commit/d4f433cb9e993b6ba131d81334946aa5b403a343))
* Hopefully help prevent false positives ([d448ab1](https://github.com/klhrt/MillenniumCITest/commit/d448ab12ed0b8bda10a17ced92123b91a2ef06ad))
* Improve error recovery steps. ([11cde53](https://github.com/klhrt/MillenniumCITest/commit/11cde53b7baa5bc09a0a276c66e4e00a504f36f7))
* Install @semantic-release/changelog ([61d6356](https://github.com/klhrt/MillenniumCITest/commit/61d6356c29ea9fd279c069b5da86072eb4df1ec1))
* Install @semantic-release/git ([9e483e8](https://github.com/klhrt/MillenniumCITest/commit/9e483e8adb4193b6db34cd9b859f46c0bc4b86d4))
* **installer:** More verbose prompts ([4e9af5b](https://github.com/klhrt/MillenniumCITest/commit/4e9af5b5653559404b1726b20fed75bb3bfcac0e))
* Issues where Steam would show prematurely ([486e892](https://github.com/klhrt/MillenniumCITest/commit/486e89232140ebe0512ce921f3a32b324d8f00ea))
* Linux compatibility fixes. ([dd4c227](https://github.com/klhrt/MillenniumCITest/commit/dd4c227cdeee58af7b415307743fffada37511d0))
* **Linux:** Arch removed "-runtime" suffix. ([cf39193](https://github.com/klhrt/MillenniumCITest/commit/cf39193a3999bb86563fed5d993df5ff1adcab47))
* **Linux:** Fix hang on shutdown [#142](https://github.com/klhrt/MillenniumCITest/issues/142) ([e8e9790](https://github.com/klhrt/MillenniumCITest/commit/e8e9790099c50ef804301995d56a21ade8b7295d))
* Only add CLI to PATH if its not already there ([9d794ce](https://github.com/klhrt/MillenniumCITest/commit/9d794ce1e0838cbfb67f705b9ae6f302e64bd426))
* Only show "Reset" on system accent color if its not the original accent color. ([4266b17](https://github.com/klhrt/MillenniumCITest/commit/4266b1746a21391ffc984af7c087668893e99c21))
* Optimize semantic release ([685cce3](https://github.com/klhrt/MillenniumCITest/commit/685cce311de6437e2e9db715172a6a1b892a054a))
* Pipe stdout to Millennium logger. ([8db49ac](https://github.com/klhrt/MillenniumCITest/commit/8db49ac70d873cc4476fa293b72a8d71526e5447))
* Platform bug fixes ([2b63f68](https://github.com/klhrt/MillenniumCITest/commit/2b63f682c9e5b5d969251a2ed0b39c2d7a1f098c))
* Plugins not loading on UNIX ([58bc696](https://github.com/klhrt/MillenniumCITest/commit/58bc696d4d219da1e1f91bd606ab714820f4d488))
* Prevent debug info from growing insanely large [#176](https://github.com/klhrt/MillenniumCITest/issues/176) ([d23bec9](https://github.com/klhrt/MillenniumCITest/commit/d23bec9832d8dbe9888a95d765f36d0cf9e6a5b4))
* Prevent logs files from getting too large ([e2aa7fd](https://github.com/klhrt/MillenniumCITest/commit/e2aa7fd1927e1caf78628e97b25e8b1aa05ff8fc))
* prevent memory leak ([4a9977e](https://github.com/klhrt/MillenniumCITest/commit/4a9977e7d9f156c968c91bc6f02ed527f86f7f7f))
* Prevent the updater modal showing every time the UI reloaded, like from changing themes. ([0ef02bf](https://github.com/klhrt/MillenniumCITest/commit/0ef02bf5e4978d3bd71e7fe22e8d228fefcfa083))
* Properly handle theme config with invalid props. ([d25461d](https://github.com/klhrt/MillenniumCITest/commit/d25461d34f6e9790d18cc667395268a32508fb2a))
* Properly log terminal colors in the installer ([892a7c8](https://github.com/klhrt/MillenniumCITest/commit/892a7c81c82df827c139352938c3a17f5750ec4e))
* Properly segment install path and Steam path ([41f8ca8](https://github.com/klhrt/MillenniumCITest/commit/41f8ca8e4b96a06a1c7bf0286bd677f492b8d766))
* Properly set python home directory ([904ad08](https://github.com/klhrt/MillenniumCITest/commit/904ad0814d4bbcca2b4ae08247514616c9b01fb0))
* Properly ship python libraries ([92ec03c](https://github.com/klhrt/MillenniumCITest/commit/92ec03c5843fb65222cf952142fe2890f9ccaa93))
* Properly whitelist the default skin in the CLI ([1d8faef](https://github.com/klhrt/MillenniumCITest/commit/1d8faef57bde9ca8b08578e08be0f3685f719c3c))
* **python:** fix py home mismatch ([a253678](https://github.com/klhrt/MillenniumCITest/commit/a25367869024ae9d631991de32ff6af77cf0cf18))
* Remove boxer on unix to prevent unneeded deps ([6b9953a](https://github.com/klhrt/MillenniumCITest/commit/6b9953a81e5eac96fb7d0a1cc26c17a2f0b7d488))
* Remove confusing log ([cf19708](https://github.com/klhrt/MillenniumCITest/commit/cf197085e648b4244997ab60824c662d71ad9487))
* Remove leading "v" in pkgver ([#279](https://github.com/klhrt/MillenniumCITest/issues/279)) ([1fb9920](https://github.com/klhrt/MillenniumCITest/commit/1fb99205ac82451579f2e87b58c09e36fe9c4738))
* remove stdout patch as it causes too many issues ([75e5d08](https://github.com/klhrt/MillenniumCITest/commit/75e5d0838b128e819be02edcc60cee2a3d48f9d4))
* Remove test error ([f965201](https://github.com/klhrt/MillenniumCITest/commit/f965201dd6f503a1ab846f7eb9d43bd403bb2e63))
* Remove unused code ([0606641](https://github.com/klhrt/MillenniumCITest/commit/0606641248428d6a85dcb20838cf497eff7b9755))
* Remove vcpkg cache from CI ([dd3d74d](https://github.com/klhrt/MillenniumCITest/commit/dd3d74d9eac5a29cad773d2eeb5bc46de7b2dfd1))
* Remove write permission from PIPX module ([f9d9931](https://github.com/klhrt/MillenniumCITest/commit/f9d9931622bdcce9d64cdb6783edafdbcf1826c7))
* Revert [#66](https://github.com/klhrt/MillenniumCITest/issues/66) ([07bb1d6](https://github.com/klhrt/MillenniumCITest/commit/07bb1d6318589aa3882ead1456dccaa0b3c9ca26))
* Revert shallow clone opts until further notice ([63da377](https://github.com/klhrt/MillenniumCITest/commit/63da3777ded625f110e3da8e8755c2c37f5eea2f))
* revert vcpkg baseline ([a8fe40d](https://github.com/klhrt/MillenniumCITest/commit/a8fe40dea4e89c9dbe39a54d6162d18538cc5063))
* revert version bump ([3aac426](https://github.com/klhrt/MillenniumCITest/commit/3aac42625af7e3c19e62cec5eeb7569c00a27006))
* revert version bump ([27ba757](https://github.com/klhrt/MillenniumCITest/commit/27ba757bb2ab614e67dc63be278827ebb16632e7))
* **scripts:** Bug fixes for Installers ([51bc183](https://github.com/klhrt/MillenniumCITest/commit/51bc183b05b3622750978eb17bd7498f6ad3e553))
* **security:** Fix a vulnerability where any website could connect to Millennium and install themes. ([47639c3](https://github.com/klhrt/MillenniumCITest/commit/47639c30aebb6e398537661a2c30a089c60912e3))
* **security:** Prevent FFI from directly executing raw python code. ([d338e25](https://github.com/klhrt/MillenniumCITest/commit/d338e2529d4a6235e0e11ba31555cfa8b2b63cf0))
* Show that no plugins are configurable instead of rendering empty quick access menu. ([5a4236e](https://github.com/klhrt/MillenniumCITest/commit/5a4236e61ddd271f785bd6f3d7eb909bc38ccfb1))
* Show the Steam UI after all plugins are finished loading instead of when the SharedJSContext connects ([b5730a3](https://github.com/klhrt/MillenniumCITest/commit/b5730a325b5790a3cb9cdc60c6bbf3f9d6b0adcb))
* Simpler less verbose logs ([0c3e90a](https://github.com/klhrt/MillenniumCITest/commit/0c3e90aeea94061f443cd37be69ff2fd43981900))
* Small fixes to Italian locales.  ([541aeb0](https://github.com/klhrt/MillenniumCITest/commit/541aeb0786a3ea19d4b48ba15b42aba7074754f7))
* Some UNIX bug fixes ([d6d8c9c](https://github.com/klhrt/MillenniumCITest/commit/d6d8c9c292635bccc0a294c88a970477347daac8))
* Staging plugin hot reload ([7d1972a](https://github.com/klhrt/MillenniumCITest/commit/7d1972ab2ccdce3f348360b64c2af8bfb7b56032))
* Suppress connection errors when steam isn't loaded (Linux) ([34b5e91](https://github.com/klhrt/MillenniumCITest/commit/34b5e91d2ffcdeec9d6762759e56602f645e8a7c))
* Temporarily disable 'steam://open/millennium as it broke "View Profile" button on friends list. ([d329f7a](https://github.com/klhrt/MillenniumCITest/commit/d329f7adb306eaba4a9659807ef538ad5f363614))
* Temporarily disable CLI support for Millennium on windows. ([02d9a76](https://github.com/klhrt/MillenniumCITest/commit/02d9a76e92498b52a59c1212a04d7d42a5232ebc))
* typo from bd ([6a847ce](https://github.com/klhrt/MillenniumCITest/commit/6a847cebab427de41612501d57256b91a41063a9))
* **uninstaller:** Check for corrupt installation ([f65d5eb](https://github.com/klhrt/MillenniumCITest/commit/f65d5eb51dfefb7e933f4e9f4c94a62f7c5a029d))
* Unix build bug fixes ([0745446](https://github.com/klhrt/MillenniumCITest/commit/0745446a6596b0a2435ad76d0e248686eb5dcfd7))
* **Unix:** Fix LD_PRELOAD variable interfering with Steam games. ([cbfd653](https://github.com/klhrt/MillenniumCITest/commit/cbfd653b3980d42dd529fc4c84028271e0c6d4e2))
* Update german localization ([#276](https://github.com/klhrt/MillenniumCITest/issues/276)) ([d528b57](https://github.com/klhrt/MillenniumCITest/commit/d528b5745a45f3b824ca1d99a3ace3c13c4ba425))
* Update installed themes in the dropdown without having to close and open settings ([e7303c1](https://github.com/klhrt/MillenniumCITest/commit/e7303c174eb6fb2f0974a6fe3a014ab60c839b08))
* Update theme dialog dropdown content on the fly. ([1944410](https://github.com/klhrt/MillenniumCITest/commit/194441091a7dfa13fd0bd2d6eadbb85a98a55dc6))
* Use correct classes for Field ([#189](https://github.com/klhrt/MillenniumCITest/issues/189)) ([4ce6b5d](https://github.com/klhrt/MillenniumCITest/commit/4ce6b5d084eb5dfce022e5a4bcc7e68833f3a902))
* Use Ninja on unix for faster build ([70d4a5d](https://github.com/klhrt/MillenniumCITest/commit/70d4a5df2d787ad1e0e5473781d576e3536d382c))
* use powershell syntax 🤦 ([eb1b75b](https://github.com/klhrt/MillenniumCITest/commit/eb1b75b9ac5f9d0009625898ba8b8c6a930ad5c9))
* Use the proper queued shim path ([ddddbb4](https://github.com/klhrt/MillenniumCITest/commit/ddddbb43b42981917491206ee6c597cb845b0546))
* Use XDG base directory variables ([b2dc64d](https://github.com/klhrt/MillenniumCITest/commit/b2dc64d54c4a728d03f564aef65d275e65193305))
* Whoops, didn't mean to commit those. closes [#249](https://github.com/klhrt/MillenniumCITest/issues/249) ([ef2f0fa](https://github.com/klhrt/MillenniumCITest/commit/ef2f0fa2bb973ddc58acf3d788c528ffcdf1491c))


### Features

* Ability to enable/disable multiple plugins before reloading. Closes [#281](https://github.com/klhrt/MillenniumCITest/issues/281) ([5858811](https://github.com/klhrt/MillenniumCITest/commit/5858811c4127501c24b8aa6e745b5b28f7975bc7))
* Ability to override system accent color ([a850936](https://github.com/klhrt/MillenniumCITest/commit/a850936e40688345a90646d92600cd6e506ea623))
* add "useBackend" capability for plugin ([86c1943](https://github.com/klhrt/MillenniumCITest/commit/86c1943a9ba34e306dc6dfac3176a9ea22588690))
* Add "webkitCSS" && "webkitJS" options ([019565e](https://github.com/klhrt/MillenniumCITest/commit/019565e60f68d51a45a20acf8a67255cd50f8ad2))
* Add `constSysfsExpr`,a way to embed assets into plugin bundle at compile time. ([4a8d1d0](https://github.com/klhrt/MillenniumCITest/commit/4a8d1d0bd43e44abdb309d4f125b8e019e62b867))
* Add authentication to IPC, and block external apps from connecting to it. ([2f58684](https://github.com/klhrt/MillenniumCITest/commit/2f586844921df29155a6b5f9692e3e06d02e1b84))
* Add auto theme installer ([b732bc9](https://github.com/klhrt/MillenniumCITest/commit/b732bc93684753b1164154a1f4bc2ee605d4357e))
* Add automatic AUR helper detection ([c8d20be](https://github.com/klhrt/MillenniumCITest/commit/c8d20bea1b13476c44dcb65616d4796286e8decf))
* Add better webkit support for plugins ([33b6cde](https://github.com/klhrt/MillenniumCITest/commit/33b6cde0091dab72761ebb4e0b051471d20b94ca))
* Add embedded updater ([24de43b](https://github.com/klhrt/MillenniumCITest/commit/24de43b8a22f116922c05b12e5538f7045370130))
* Add enabled plugin names to <html> element to make CSS styling easier. [#258](https://github.com/klhrt/MillenniumCITest/issues/258) ([938bb82](https://github.com/klhrt/MillenniumCITest/commit/938bb82c06a82f1d916bf9c28947e5c37f22bdfa))
* Add french localization.  ([54114e5](https://github.com/klhrt/MillenniumCITest/commit/54114e5727b64d4ef6196e73a5cc094dc38e7987))
* Add install script for linux ([950ffa8](https://github.com/klhrt/MillenniumCITest/commit/950ffa8eccd131d35e101f4e195a1594ecb68d3a))
* Add Italian localization ([#209](https://github.com/klhrt/MillenniumCITest/issues/209)) ([de5a9d2](https://github.com/klhrt/MillenniumCITest/commit/de5a9d238062366fcc1b1e9e379ffd980223541d))
* Add linux build inside docker container ([#262](https://github.com/klhrt/MillenniumCITest/issues/262)) ([dbf913c](https://github.com/klhrt/MillenniumCITest/commit/dbf913ccc9ec6416228d381a44711181b331b690))
* Add Millennium CLI to PATH ([05c5fa5](https://github.com/klhrt/MillenniumCITest/commit/05c5fa5e9746ade1b8cce9e6cbd15dbbffaceb60))
* Add more info to plugins page ([1e3a955](https://github.com/klhrt/MillenniumCITest/commit/1e3a955b2a84532cb46a044a6001fcae46a260bd))
* Add plugin settings [#183](https://github.com/klhrt/MillenniumCITest/issues/183) ([643c1a0](https://github.com/klhrt/MillenniumCITest/commit/643c1a0c695b89a65f4e637c1f5229135b42915f))
* Add plugin updater. ([5c28c7e](https://github.com/klhrt/MillenniumCITest/commit/5c28c7ef96e576ace25a6be111535c6fa0768cdf))
* Add quick access menu to Millennium ([b22f3c7](https://github.com/klhrt/MillenniumCITest/commit/b22f3c7b6782a24a31ac5fe10b354f94544b233c))
* Add regex support for webkit patching ([#147](https://github.com/klhrt/MillenniumCITest/issues/147)) ([0c87da1](https://github.com/klhrt/MillenniumCITest/commit/0c87da152c1e8a5a00bc787978214ba4839efe70)), closes [#127](https://github.com/klhrt/MillenniumCITest/issues/127) [#140](https://github.com/klhrt/MillenniumCITest/issues/140)
* add semantic release ([ec8699a](https://github.com/klhrt/MillenniumCITest/commit/ec8699a164269a294550724fe33b8ee5316f31cb))
* Add semantic release ([66490fb](https://github.com/klhrt/MillenniumCITest/commit/66490fbb9033a8e0616677de731dc9ba8cee534f))
* Add steam://open/millennium URL to open settings ([7bcc7e2](https://github.com/klhrt/MillenniumCITest/commit/7bcc7e2aeebfa2750fbe0b1cc8d25ceccea9e074))
* Add Swedish localization. ([#180](https://github.com/klhrt/MillenniumCITest/issues/180)) ([0d9e8b4](https://github.com/klhrt/MillenniumCITest/commit/0d9e8b49cbfac3950e6a0bb280ca3cc6d22739c4))
* Add system accent color to webkit ([af602c3](https://github.com/klhrt/MillenniumCITest/commit/af602c30e140a1588d901417d9b6d83a590ed4f6))
* add Vietnamese localization ([#208](https://github.com/klhrt/MillenniumCITest/issues/208)) ([3e83de5](https://github.com/klhrt/MillenniumCITest/commit/3e83de5c5434fd2d71cc40c28024513859cda0be))
* Add webkit JS option in skin.json ([3d360a4](https://github.com/klhrt/MillenniumCITest/commit/3d360a4d4a98bc366b807fcd46248980a092f21a))
* Added CPS bypass & Added Millennium API to webkit modules ([eda0f54](https://github.com/klhrt/MillenniumCITest/commit/eda0f5460061075e0e389c9cacbd270a97c18739))
* Added danish locales ([8b93e91](https://github.com/klhrt/MillenniumCITest/commit/8b93e911f5daff1899ad8feac34a211a47cc80bc))
* Ask users if they want auto updates, or to review updates, or to disable updates entirely. ([62553cf](https://github.com/klhrt/MillenniumCITest/commit/62553cf11599a532cec605cc6b61e68476c495c8))
* Better error logging for plugin backends ([45433c0](https://github.com/klhrt/MillenniumCITest/commit/45433c03842227c80c9482d649b9aff2641c55d0))
* Better error stack tracing ([e3518c3](https://github.com/klhrt/MillenniumCITest/commit/e3518c3cb32bcde50089ab449b80babc5f513b09))
* Better UNIX system folder heirarchy ([#247](https://github.com/klhrt/MillenniumCITest/issues/247)) ([cbe1fa1](https://github.com/klhrt/MillenniumCITest/commit/cbe1fa16e3c08cc6a39e83822b5456a4f4016585)), closes [#230](https://github.com/klhrt/MillenniumCITest/issues/230) [#234](https://github.com/klhrt/MillenniumCITest/issues/234)
* Better, easier to view installer for linux ([fd27c80](https://github.com/klhrt/MillenniumCITest/commit/fd27c802b49c150cd8ef6f701297041a810faeea))
* Binary stripping on release modules to drastically reduce binary size ([45734f2](https://github.com/klhrt/MillenniumCITest/commit/45734f2be936a2ed58072f96d52c5d68945d6e71))
* Completely virtual FTP and IPC making them inaccessible outside of Steam. ([a5ede25](https://github.com/klhrt/MillenniumCITest/commit/a5ede254cd524ece3474604ae1bb6e943dda54a3))
* Conditional webkit patching based on URL with regex [#127](https://github.com/klhrt/MillenniumCITest/issues/127) ([bf36bd5](https://github.com/klhrt/MillenniumCITest/commit/bf36bd537c19ae5c5a10fdc6b3e86db3947dd862))
* **core:** disable backend hot reload ([1700b7d](https://github.com/klhrt/MillenniumCITest/commit/1700b7dab2cc46a676ef687926bd6b2901a0273e))
* CTRL+2 to open Millennium quick access ([0b06a10](https://github.com/klhrt/MillenniumCITest/commit/0b06a1001c905e921cbd4a0385de6b5db24ac286))
* Fix and re-implement steam://millennium URL support ([5198a6a](https://github.com/klhrt/MillenniumCITest/commit/5198a6aa8e189edb9f321fc4aad84379b53b1198))
* Fix platform arch for 32 bit LD_PRELOAD-able binary ([515cb9e](https://github.com/klhrt/MillenniumCITest/commit/515cb9eb966c9d2adf9e5b3b2f51614b43bacabb))
* Hot reload for plugins ([cdacaba](https://github.com/klhrt/MillenniumCITest/commit/cdacaba73197fd8a985ff96aaa19a8b122f5c652))
* Improved Installer ([134cce5](https://github.com/klhrt/MillenniumCITest/commit/134cce5fc01cfb86250e8ee5bc22342443dbe6b8))
* **license:** update copyright date ([ed1cffb](https://github.com/klhrt/MillenniumCITest/commit/ed1cffb2464f30b77d82de3ba0ccd3ca15407d19))
* **log:** fix log init ([48bf3b5](https://github.com/klhrt/MillenniumCITest/commit/48bf3b596321e56a379f43beb51934ae1ad43e8e))
* Open Steam developer tools by running `steam://millennium/devtools/open` ([b2d6aae](https://github.com/klhrt/MillenniumCITest/commit/b2d6aae6f1bd26215726e9a429f0149436e02668))
* Overhauled Swedish translation. ([013763a](https://github.com/klhrt/MillenniumCITest/commit/013763a28aa26d58fda827cfa63772898e796ce2))
* Properly use Steam's internal components to create Millennium's Settings window. ([c2a4285](https://github.com/klhrt/MillenniumCITest/commit/c2a4285df72630fb6a41ff645afc4f75c19e297d))
* Remove CLI tool, most likely revamping it. ([83c0a56](https://github.com/klhrt/MillenniumCITest/commit/83c0a568ac17d8ab8ad0707a6562d5fa2e627d19))
* Remove LibGit2 and rely on CI assets ([5db0ebd](https://github.com/klhrt/MillenniumCITest/commit/5db0ebd6f571007b0fa3ea66c958a67dd93e64dd))
* **Security:** Blacklist certain pages, like the checkout, from being injected into by plugins. ([54edc4c](https://github.com/klhrt/MillenniumCITest/commit/54edc4c6f82f6f6b41fed29ce7f0e7b01ba200c9))
* Show theme version in "About Theme" [#87](https://github.com/klhrt/MillenniumCITest/issues/87) ([f99046e](https://github.com/klhrt/MillenniumCITest/commit/f99046e053e6a4503564b74b2e71e93c9185bd0f))
* Show welcome modal to new users ([7ea8358](https://github.com/klhrt/MillenniumCITest/commit/7ea8358649270044a35c4bf1e091f7b4bead894e))
* Slightly Better Russian Translation ([#187](https://github.com/klhrt/MillenniumCITest/issues/187)) ([639390d](https://github.com/klhrt/MillenniumCITest/commit/639390dab1c9367cc72a3bff98dc454fa55ccbb0))
* Softer and better crash detection. ([fc5e756](https://github.com/klhrt/MillenniumCITest/commit/fc5e7568757f72e020cfa3def59cb9c6026284d2))
* Stage fully hot reloadable plugins ([79d4a27](https://github.com/klhrt/MillenniumCITest/commit/79d4a2744fb89a2b5836f013223fc2c439f82453))
* Staging CLI support ([f5cda3d](https://github.com/klhrt/MillenniumCITest/commit/f5cda3dde657fb8cc1ebe535ff83d27589cc5b80))
* steam://millennium URL support ([bb69d19](https://github.com/klhrt/MillenniumCITest/commit/bb69d1900a42252de44ccf3c54114071d297e180))
* switch socket pipes to 1 wire ([53e6978](https://github.com/klhrt/MillenniumCITest/commit/53e6978abf6789bb4eb5c8a93f353710e5ca4e60))
* Theme option tabs ([#94](https://github.com/klhrt/MillenniumCITest/issues/94)) ([cc6e339](https://github.com/klhrt/MillenniumCITest/commit/cc6e339ef454478c9945a8512851ff79a3a12c1b))
* **Unix:** Add theme auto installer & update manager ([2a8a880](https://github.com/klhrt/MillenniumCITest/commit/2a8a8803a160f5abfd503c2a84be8371c7f13e81))
* Update italian localization. ([5856765](https://github.com/klhrt/MillenniumCITest/commit/585676535ab58778d0f95244363135d1129948bd))
* Update to libgit2@1.8.0 for git_clone_options ([6feced6](https://github.com/klhrt/MillenniumCITest/commit/6feced638ce16a4ceccf9cc5ac478355b54ee480))
* Updated plugin support for better webkit modding. ([1a8daf0](https://github.com/klhrt/MillenniumCITest/commit/1a8daf048515c8c01b8ce703838c7da6efb40771))
* Warn users of incompatible Steam.cfg files. ([197e574](https://github.com/klhrt/MillenniumCITest/commit/197e5742e9c3862cd9d395405f315d1db345ef81))
* Warn users when no themes were found instead of showing empty dropdown. ([6731867](https://github.com/klhrt/MillenniumCITest/commit/6731867ff83505e6302369349957c3e53983eecc))


### Performance Improvements

* Improve shutdown speed on Linux ([b0a026f](https://github.com/klhrt/MillenniumCITest/commit/b0a026fd388cb8a706a8971312583e80c50ec072))
* improved webkit load performance by ~350ms ([f0100c4](https://github.com/klhrt/MillenniumCITest/commit/f0100c4fd0e6dda71d2a65d5f23da5d379756f6e))
* Startup performance improvements ([6a138d3](https://github.com/klhrt/MillenniumCITest/commit/6a138d39b44e37e16a81c8b8a0be89591885e8aa))

# [2.26.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.25.1...v2.26.0) (2025-06-23)


### Bug Fixes

* **CI:** use pnpm instead of npm and cache vcpkg properly ([d58e2a8](https://github.com/SteamClientHomebrew/Millennium/commit/d58e2a859fd2739bf0787824a28b30e9e77a341c))
* fix build structure on windows ([88236a8](https://github.com/SteamClientHomebrew/Millennium/commit/88236a861cf319c4ca43783e546154143d59d830))
* Fix CI ([997747d](https://github.com/SteamClientHomebrew/Millennium/commit/997747dabdca59c87268b56356f1540651ecb275))
* Fix CI ([0465205](https://github.com/SteamClientHomebrew/Millennium/commit/0465205991313d833ef9321fcb0c0e136d05a26d))
* Fix CI ([6704435](https://github.com/SteamClientHomebrew/Millennium/commit/6704435d1a000ec84e53ea0892b91031060caa05))
* Fix CI not building Millennium API properly ([9564eb2](https://github.com/SteamClientHomebrew/Millennium/commit/9564eb2d075f950b939442624441d24a8a62e95a))
* Fix encoding issue when calling a JS method from the backend. ([d03134c](https://github.com/SteamClientHomebrew/Millennium/commit/d03134ce679dfc7dfe4e5c77a3e4462e577011b0))
* Fix FFI propagating backend call on plugins with no backend. ([cbb873d](https://github.com/SteamClientHomebrew/Millennium/commit/cbb873dd06d3afddf4dee7b283a8a2262915e101))
* Fix install script failing if the username is 'user'. closes [#343](https://github.com/SteamClientHomebrew/Millennium/issues/343) ([e3c04c6](https://github.com/SteamClientHomebrew/Millennium/commit/e3c04c67422d1fe4c4b016736320f0bbed869b43))
* fix Millennium finding incorrect API modules. ([906e6a4](https://github.com/SteamClientHomebrew/Millennium/commit/906e6a456f951e992a7bfbc2a505c6e84adfaa1f))
* Fix Millennium showing updates when none are actually available ([ee26150](https://github.com/SteamClientHomebrew/Millennium/commit/ee2615032b3c0b2b1c093cc60368c9b83f02644c))
* Fix OpenSSL issues ([78f8fa4](https://github.com/SteamClientHomebrew/Millennium/commit/78f8fa4276bd897bff5c838858e8ca1f3a74e0cb))
* Fix plugin downloader on linux ([f1c8f51](https://github.com/SteamClientHomebrew/Millennium/commit/f1c8f5194bbbdd75b3531999b9ee8c32ba2dd90f))
* fix plugin installer popping out of main window. ([3058d43](https://github.com/SteamClientHomebrew/Millennium/commit/3058d43b69775b85c8cf4fa6d87147cc674b8b6f))
* Fix plugin updater sometimes extracting to wrong path, updating while plugin is running, and fixed backend memory management issues., ([7c47e88](https://github.com/SteamClientHomebrew/Millennium/commit/7c47e887a948c2f83d51ba5108814f35e0ff62d0))
* fix plugins installing to wrong folder ([20a9ad7](https://github.com/SteamClientHomebrew/Millennium/commit/20a9ad7c76a6211613dcf4a341e02ac328418da1))
* fix Quick Access Menu being empty when no plugins are configurable. ([c37b200](https://github.com/SteamClientHomebrew/Millennium/commit/c37b20048ceb6f45c54ae3d2727d1046dcf4bc2b))
* Fix simultaneous backend calls crashing python interpreter. ([1272230](https://github.com/SteamClientHomebrew/Millennium/commit/12722306c3112fdd73d3928b9e1d7d1ca52647e6))
* fix windows build not working. ([5b63615](https://github.com/SteamClientHomebrew/Millennium/commit/5b63615e182b55982ed9a53cd6077c0e7edee915))
* Only show "Reset" on system accent color if its not the original accent color. ([4266b17](https://github.com/SteamClientHomebrew/Millennium/commit/4266b1746a21391ffc984af7c087668893e99c21))
* remove stdout patch as it causes too many issues ([75e5d08](https://github.com/SteamClientHomebrew/Millennium/commit/75e5d0838b128e819be02edcc60cee2a3d48f9d4))
* Remove vcpkg cache from CI ([dd3d74d](https://github.com/SteamClientHomebrew/Millennium/commit/dd3d74d9eac5a29cad773d2eeb5bc46de7b2dfd1))
* **security:** Prevent FFI from directly executing raw python code. ([d338e25](https://github.com/SteamClientHomebrew/Millennium/commit/d338e2529d4a6235e0e11ba31555cfa8b2b63cf0))
* Show that no plugins are configurable instead of rendering empty quick access menu. ([5a4236e](https://github.com/SteamClientHomebrew/Millennium/commit/5a4236e61ddd271f785bd6f3d7eb909bc38ccfb1))


### Features

* Add `constSysfsExpr`,a way to embed assets into plugin bundle at compile time. ([4a8d1d0](https://github.com/SteamClientHomebrew/Millennium/commit/4a8d1d0bd43e44abdb309d4f125b8e019e62b867))
* Add authentication to IPC, and block external apps from connecting to it. ([2f58684](https://github.com/SteamClientHomebrew/Millennium/commit/2f586844921df29155a6b5f9692e3e06d02e1b84))
* Add plugin settings [#183](https://github.com/SteamClientHomebrew/Millennium/issues/183) ([643c1a0](https://github.com/SteamClientHomebrew/Millennium/commit/643c1a0c695b89a65f4e637c1f5229135b42915f))
* Add plugin updater. ([5c28c7e](https://github.com/SteamClientHomebrew/Millennium/commit/5c28c7ef96e576ace25a6be111535c6fa0768cdf))
* Add quick access menu to Millennium ([b22f3c7](https://github.com/SteamClientHomebrew/Millennium/commit/b22f3c7b6782a24a31ac5fe10b354f94544b233c))
* Completely virtual FTP and IPC making them inaccessible outside of Steam. ([a5ede25](https://github.com/SteamClientHomebrew/Millennium/commit/a5ede254cd524ece3474604ae1bb6e943dda54a3))
* CTRL+2 to open Millennium quick access ([0b06a10](https://github.com/SteamClientHomebrew/Millennium/commit/0b06a1001c905e921cbd4a0385de6b5db24ac286))
* Overhauled Swedish translation. ([013763a](https://github.com/SteamClientHomebrew/Millennium/commit/013763a28aa26d58fda827cfa63772898e796ce2))
* Properly use Steam's internal components to create Millennium's Settings window. ([c2a4285](https://github.com/SteamClientHomebrew/Millennium/commit/c2a4285df72630fb6a41ff645afc4f75c19e297d))


### Performance Improvements

* improved webkit load performance by ~350ms ([f0100c4](https://github.com/SteamClientHomebrew/Millennium/commit/f0100c4fd0e6dda71d2a65d5f23da5d379756f6e))

# [2.26.0-beta.11](https://github.com/SteamClientHomebrew/Millennium/compare/v2.26.0-beta.10...v2.26.0-beta.11) (2025-06-23)


### Bug Fixes

* Fix CI not building Millennium API properly ([9564eb2](https://github.com/SteamClientHomebrew/Millennium/commit/9564eb2d075f950b939442624441d24a8a62e95a))

# [2.26.0-beta.10](https://github.com/SteamClientHomebrew/Millennium/compare/v2.26.0-beta.9...v2.26.0-beta.10) (2025-06-22)


### Bug Fixes

* fix plugin installer popping out of main window. ([3058d43](https://github.com/SteamClientHomebrew/Millennium/commit/3058d43b69775b85c8cf4fa6d87147cc674b8b6f))
* fix windows build not working. ([5b63615](https://github.com/SteamClientHomebrew/Millennium/commit/5b63615e182b55982ed9a53cd6077c0e7edee915))

# [2.26.0-beta.9](https://github.com/SteamClientHomebrew/Millennium/compare/v2.26.0-beta.8...v2.26.0-beta.9) (2025-06-22)


### Bug Fixes

* **CI:** use pnpm instead of npm and cache vcpkg properly ([d58e2a8](https://github.com/SteamClientHomebrew/Millennium/commit/d58e2a859fd2739bf0787824a28b30e9e77a341c))
* fix Quick Access Menu being empty when no plugins are configurable. ([c37b200](https://github.com/SteamClientHomebrew/Millennium/commit/c37b20048ceb6f45c54ae3d2727d1046dcf4bc2b))
* remove stdout patch as it causes too many issues ([75e5d08](https://github.com/SteamClientHomebrew/Millennium/commit/75e5d0838b128e819be02edcc60cee2a3d48f9d4))

# [2.26.0-beta.8](https://github.com/SteamClientHomebrew/Millennium/compare/v2.26.0-beta.7...v2.26.0-beta.8) (2025-06-22)


### Bug Fixes

* fix plugins installing to wrong folder ([20a9ad7](https://github.com/SteamClientHomebrew/Millennium/commit/20a9ad7c76a6211613dcf4a341e02ac328418da1))

# [2.26.0-beta.7](https://github.com/SteamClientHomebrew/Millennium/compare/v2.26.0-beta.6...v2.26.0-beta.7) (2025-06-22)


### Bug Fixes

* Fix simultaneous backend calls crashing python interpreter. ([1272230](https://github.com/SteamClientHomebrew/Millennium/commit/12722306c3112fdd73d3928b9e1d7d1ca52647e6))

# [2.26.0-beta.6](https://github.com/SteamClientHomebrew/Millennium/compare/v2.26.0-beta.5...v2.26.0-beta.6) (2025-06-21)


### Bug Fixes

* fix build structure on windows ([88236a8](https://github.com/SteamClientHomebrew/Millennium/commit/88236a861cf319c4ca43783e546154143d59d830))
* fix Millennium finding incorrect API modules. ([906e6a4](https://github.com/SteamClientHomebrew/Millennium/commit/906e6a456f951e992a7bfbc2a505c6e84adfaa1f))
* Fix plugin downloader on linux ([f1c8f51](https://github.com/SteamClientHomebrew/Millennium/commit/f1c8f5194bbbdd75b3531999b9ee8c32ba2dd90f))
* Show that no plugins are configurable instead of rendering empty quick access menu. ([5a4236e](https://github.com/SteamClientHomebrew/Millennium/commit/5a4236e61ddd271f785bd6f3d7eb909bc38ccfb1))

# [2.26.0-beta.5](https://github.com/SteamClientHomebrew/Millennium/compare/v2.26.0-beta.4...v2.26.0-beta.5) (2025-06-21)


### Bug Fixes

* Remove vcpkg cache from CI ([dd3d74d](https://github.com/SteamClientHomebrew/Millennium/commit/dd3d74d9eac5a29cad773d2eeb5bc46de7b2dfd1))
* **security:** Prevent FFI from directly executing raw python code. ([d338e25](https://github.com/SteamClientHomebrew/Millennium/commit/d338e2529d4a6235e0e11ba31555cfa8b2b63cf0))


### Features

* Add authentication to IPC, and block external apps from connecting to it. ([2f58684](https://github.com/SteamClientHomebrew/Millennium/commit/2f586844921df29155a6b5f9692e3e06d02e1b84))
* Completely virtual FTP and IPC making them inaccessible outside of Steam. ([a5ede25](https://github.com/SteamClientHomebrew/Millennium/commit/a5ede254cd524ece3474604ae1bb6e943dda54a3))

# [2.26.0-beta.4](https://github.com/SteamClientHomebrew/Millennium/compare/v2.26.0-beta.3...v2.26.0-beta.4) (2025-06-13)


### Bug Fixes

* Fix CI ([997747d](https://github.com/SteamClientHomebrew/Millennium/commit/997747dabdca59c87268b56356f1540651ecb275))
* Fix CI ([0465205](https://github.com/SteamClientHomebrew/Millennium/commit/0465205991313d833ef9321fcb0c0e136d05a26d))
* Fix CI ([6704435](https://github.com/SteamClientHomebrew/Millennium/commit/6704435d1a000ec84e53ea0892b91031060caa05))
* Fix encoding issue when calling a JS method from the backend. ([d03134c](https://github.com/SteamClientHomebrew/Millennium/commit/d03134ce679dfc7dfe4e5c77a3e4462e577011b0))
* Fix FFI propagating backend call on plugins with no backend. ([cbb873d](https://github.com/SteamClientHomebrew/Millennium/commit/cbb873dd06d3afddf4dee7b283a8a2262915e101))
* Fix install script failing if the username is 'user'. closes [#343](https://github.com/SteamClientHomebrew/Millennium/issues/343) ([e3c04c6](https://github.com/SteamClientHomebrew/Millennium/commit/e3c04c67422d1fe4c4b016736320f0bbed869b43))
* Fix Millennium showing updates when none are actually available ([ee26150](https://github.com/SteamClientHomebrew/Millennium/commit/ee2615032b3c0b2b1c093cc60368c9b83f02644c))
* Fix OpenSSL issues ([78f8fa4](https://github.com/SteamClientHomebrew/Millennium/commit/78f8fa4276bd897bff5c838858e8ca1f3a74e0cb))


### Features

* Add `constSysfsExpr`,a way to embed assets into plugin bundle at compile time. ([4a8d1d0](https://github.com/SteamClientHomebrew/Millennium/commit/4a8d1d0bd43e44abdb309d4f125b8e019e62b867))
* Add plugin settings [#183](https://github.com/SteamClientHomebrew/Millennium/issues/183) ([643c1a0](https://github.com/SteamClientHomebrew/Millennium/commit/643c1a0c695b89a65f4e637c1f5229135b42915f))
* Add quick access menu to Millennium ([b22f3c7](https://github.com/SteamClientHomebrew/Millennium/commit/b22f3c7b6782a24a31ac5fe10b354f94544b233c))
* CTRL+2 to open Millennium quick access ([0b06a10](https://github.com/SteamClientHomebrew/Millennium/commit/0b06a1001c905e921cbd4a0385de6b5db24ac286))
* Overhauled Swedish translation. ([013763a](https://github.com/SteamClientHomebrew/Millennium/commit/013763a28aa26d58fda827cfa63772898e796ce2))
* Properly use Steam's internal components to create Millennium's Settings window. ([c2a4285](https://github.com/SteamClientHomebrew/Millennium/commit/c2a4285df72630fb6a41ff645afc4f75c19e297d))


### Performance Improvements

* improved webkit load performance by ~350ms ([f0100c4](https://github.com/SteamClientHomebrew/Millennium/commit/f0100c4fd0e6dda71d2a65d5f23da5d379756f6e))

# [2.26.0-beta.3](https://github.com/SteamClientHomebrew/Millennium/compare/v2.26.0-beta.2...v2.26.0-beta.3) (2025-04-18)

### Bug Fixes

-   Only show "Reset" on system accent color if its not the original accent color. ([4266b17](https://github.com/SteamClientHomebrew/Millennium/commit/4266b1746a21391ffc984af7c087668893e99c21))

# [2.26.0-beta.2](https://github.com/SteamClientHomebrew/Millennium/compare/v2.26.0-beta.1...v2.26.0-beta.2) (2025-04-14)

### Bug Fixes

-   Fix plugin updater sometimes extracting to wrong path, updating while plugin is running, and fixed backend memory management issues., ([7c47e88](https://github.com/SteamClientHomebrew/Millennium/commit/7c47e887a948c2f83d51ba5108814f35e0ff62d0))

# [2.26.0-beta.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.25.1...v2.26.0-beta.1) (2025-04-13)

### Features

-   Add plugin updater. ([5c28c7e](https://github.com/SteamClientHomebrew/Millennium/commit/5c28c7ef96e576ace25a6be111535c6fa0768cdf))

## [2.25.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.25.0...v2.25.1) (2025-04-12)

### Bug Fixes

-   Fix millennium not evaluating symlinks properly ([46e34f7](https://github.com/SteamClientHomebrew/Millennium/commit/46e34f7d2b0cb0fc4370f4c9221af0ff76b99c96))

# [2.25.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.24.0...v2.25.0) (2025-04-12)

### Bug Fixes

-   Add start script support for non-arch based distros. ([cda3843](https://github.com/SteamClientHomebrew/Millennium/commit/cda3843693a18e44ae7fdc1bfe9d0c3b6340fa4a))
-   Fix Millennium on Linux ([30f400d](https://github.com/SteamClientHomebrew/Millennium/commit/30f400de02c56fd394d1b9c42d492298cf36c571))

### Features

-   Add automatic AUR helper detection ([c8d20be](https://github.com/SteamClientHomebrew/Millennium/commit/c8d20bea1b13476c44dcb65616d4796286e8decf))

# [2.24.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.23.0...v2.24.0) (2025-04-10)

### Bug Fixes

-   Fix Steam UI not showing on launch. ([52ad028](https://github.com/SteamClientHomebrew/Millennium/commit/52ad0289042de64d16b35a8429c610a96ae55667))
-   Fix Steam webhelper hanging it by force crashing it, instead of relying on CEF reload. ([df65b37](https://github.com/SteamClientHomebrew/Millennium/commit/df65b37a7d7cbfbe00fe21a11c056108c9c88186))
-   Fix the AUR PKGBUILD (hopefully) ([3fbacbf](https://github.com/SteamClientHomebrew/Millennium/commit/3fbacbf2484227de78c02442f75b92808de08a4a))
-   Improve error recovery steps. ([11cde53](https://github.com/SteamClientHomebrew/Millennium/commit/11cde53b7baa5bc09a0a276c66e4e00a504f36f7))
-   Remove test error ([f965201](https://github.com/SteamClientHomebrew/Millennium/commit/f965201dd6f503a1ab846f7eb9d43bd403bb2e63))
-   Remove write permission from PIPX module ([f9d9931](https://github.com/SteamClientHomebrew/Millennium/commit/f9d9931622bdcce9d64cdb6783edafdbcf1826c7))

### Features

-   Better error stack tracing ([e3518c3](https://github.com/SteamClientHomebrew/Millennium/commit/e3518c3cb32bcde50089ab449b80babc5f513b09))

# [2.24.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.23.0...v2.24.0) (2025-04-10)

### Bug Fixes

-   Fix Steam webhelper hanging it by force crashing it, instead of relying on CEF reload. ([df65b37](https://github.com/SteamClientHomebrew/Millennium/commit/df65b37a7d7cbfbe00fe21a11c056108c9c88186))
-   Fix the AUR PKGBUILD (hopefully) ([3fbacbf](https://github.com/SteamClientHomebrew/Millennium/commit/3fbacbf2484227de78c02442f75b92808de08a4a))
-   Improve error recovery steps. ([11cde53](https://github.com/SteamClientHomebrew/Millennium/commit/11cde53b7baa5bc09a0a276c66e4e00a504f36f7))
-   Remove test error ([f965201](https://github.com/SteamClientHomebrew/Millennium/commit/f965201dd6f503a1ab846f7eb9d43bd403bb2e63))
-   Remove write permission from PIPX module ([f9d9931](https://github.com/SteamClientHomebrew/Millennium/commit/f9d9931622bdcce9d64cdb6783edafdbcf1826c7))

### Features

-   Better error stack tracing ([e3518c3](https://github.com/SteamClientHomebrew/Millennium/commit/e3518c3cb32bcde50089ab449b80babc5f513b09))

# [2.24.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.23.0...v2.24.0) (2025-04-10)

### Bug Fixes

-   Fix Steam webhelper hanging it by force crashing it, instead of relying on CEF reload. ([df65b37](https://github.com/SteamClientHomebrew/Millennium/commit/df65b37a7d7cbfbe00fe21a11c056108c9c88186))
-   Fix the AUR PKGBUILD (hopefully) ([3fbacbf](https://github.com/SteamClientHomebrew/Millennium/commit/3fbacbf2484227de78c02442f75b92808de08a4a))
-   Improve error recovery steps. ([11cde53](https://github.com/SteamClientHomebrew/Millennium/commit/11cde53b7baa5bc09a0a276c66e4e00a504f36f7))
-   Remove write permission from PIPX module ([f9d9931](https://github.com/SteamClientHomebrew/Millennium/commit/f9d9931622bdcce9d64cdb6783edafdbcf1826c7))

### Features

-   Better error stack tracing ([e3518c3](https://github.com/SteamClientHomebrew/Millennium/commit/e3518c3cb32bcde50089ab449b80babc5f513b09))

## [2.23.1-beta.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.23.0...v2.23.1-beta.1) (2025-04-08)

### Bug Fixes

-   Fix Steam webhelper hanging it by force crashing it, instead of relying on CEF reload. ([df65b37](https://github.com/SteamClientHomebrew/Millennium/commit/df65b37a7d7cbfbe00fe21a11c056108c9c88186))
-   Remove write permission from PIPX module ([f9d9931](https://github.com/SteamClientHomebrew/Millennium/commit/f9d9931622bdcce9d64cdb6783edafdbcf1826c7))

# [2.23.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.22.0...v2.23.0) (2025-04-08)

### Bug Fixes

-   Fix system error message box ([8751660](https://github.com/SteamClientHomebrew/Millennium/commit/8751660b3ffb1db36d4f7b3d065c0870343ee856))

### Features

-   Added danish locales ([8b93e91](https://github.com/SteamClientHomebrew/Millennium/commit/8b93e911f5daff1899ad8feac34a211a47cc80bc))

# [2.22.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.21.0...v2.22.0) (2025-04-06)

### Bug Fixes

-   Fix color analyzer not properly parsing color name and description. ([8f8893b](https://github.com/SteamClientHomebrew/Millennium/commit/8f8893bf752ff813b59f18f5c184a4a0ac55b3a5))
-   Fix simplified chinese locales ([d061953](https://github.com/SteamClientHomebrew/Millennium/commit/d061953b65022e9ccb0c0c63ae1f3848d36aaa35))
-   Fix Spanish locales ([57de823](https://github.com/SteamClientHomebrew/Millennium/commit/57de823c89084c9cc36d67754c5c897d069f1c53))
-   Fix spanish localization ([594b7d1](https://github.com/SteamClientHomebrew/Millennium/commit/594b7d1aef34d910f29ff32ed7a6706903984bde))
-   **Linux:** Arch removed "-runtime" suffix. ([cf39193](https://github.com/SteamClientHomebrew/Millennium/commit/cf39193a3999bb86563fed5d993df5ff1adcab47))

### Features

-   Add french localization. ([54114e5](https://github.com/SteamClientHomebrew/Millennium/commit/54114e5727b64d4ef6196e73a5cc094dc38e7987))
-   Open Steam developer tools by running `steam://millennium/devtools/open` ([b2d6aae](https://github.com/SteamClientHomebrew/Millennium/commit/b2d6aae6f1bd26215726e9a429f0149436e02668))

# [2.21.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.20.1...v2.21.0) (2025-03-30)

### Bug Fixes

-   Error in Swedish localization fixed ([71211ca](https://github.com/SteamClientHomebrew/Millennium/commit/71211ca5150f88f87854155076f422649165a03f))
-   Fix Brazilian localization ([a2dd9f5](https://github.com/SteamClientHomebrew/Millennium/commit/a2dd9f534e7bff838ec61ef7e36299d6105654b4))
-   Fix the "Bug Reports" tab not working 🤦‍♂️ ([236b68e](https://github.com/SteamClientHomebrew/Millennium/commit/236b68e8bbab34f768d7f63aaf376aced20afbac))
-   Fix the Linux build ([8936dcf](https://github.com/SteamClientHomebrew/Millennium/commit/8936dcf6fdfd34caa0b889b9d4b267fa0cfc2449))

### Features

-   Fix and re-implement steam://millennium URL support ([5198a6a](https://github.com/SteamClientHomebrew/Millennium/commit/5198a6aa8e189edb9f321fc4aad84379b53b1198))
-   steam://millennium URL support ([bb69d19](https://github.com/SteamClientHomebrew/Millennium/commit/bb69d1900a42252de44ccf3c54114071d297e180))

## [2.20.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.20.0...v2.20.1) (2025-03-30)

### Bug Fixes

-   Fix Brazilian Portuguese locales ([2596ffb](https://github.com/SteamClientHomebrew/Millennium/commit/2596ffba381e5084e115a3ee80aa886b38f446ea))
-   Fix German locales ([f9b4347](https://github.com/SteamClientHomebrew/Millennium/commit/f9b4347fcfd7f5dff3d8a31d61266a7c7ba66365))
-   Fix Millennium breaking certain webpages, and prevented it from interacting with sensitive URLs like PayPal. ([106b286](https://github.com/SteamClientHomebrew/Millennium/commit/106b286fcd2a4000eafccaa0b54ee8dbfd069c46))
-   Small fixes to Italian locales. ([541aeb0](https://github.com/SteamClientHomebrew/Millennium/commit/541aeb0786a3ea19d4b48ba15b42aba7074754f7))

# [2.20.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.19.5...v2.20.0) (2025-03-29)

### Bug Fixes

-   Prevent the updater modal showing every time the UI reloaded, like from changing themes. ([0ef02bf](https://github.com/SteamClientHomebrew/Millennium/commit/0ef02bf5e4978d3bd71e7fe22e8d228fefcfa083))

### Features

-   Update italian localization. ([5856765](https://github.com/SteamClientHomebrew/Millennium/commit/585676535ab58778d0f95244363135d1129948bd))

## [2.19.5](https://github.com/SteamClientHomebrew/Millennium/compare/v2.19.4...v2.19.5) (2025-03-29)

### Bug Fixes

-   Grammer correction and Swedish localization ([#289](https://github.com/SteamClientHomebrew/Millennium/issues/289)) ([d4f433c](https://github.com/SteamClientHomebrew/Millennium/commit/d4f433cb9e993b6ba131d81334946aa5b403a343))

## [2.19.4](https://github.com/SteamClientHomebrew/Millennium/compare/v2.19.3...v2.19.4) (2025-03-29)

### Bug Fixes

-   Fix Millennium button not showing on some languages. ([b1c107c](https://github.com/SteamClientHomebrew/Millennium/commit/b1c107c9b92d5f1aafd411dd674ce8f12cc10764))

## [2.19.3](https://github.com/SteamClientHomebrew/Millennium/compare/v2.19.2...v2.19.3) (2025-03-28)

### Bug Fixes

-   Fix wrong Millennium version being put as the developer console title. ([41cfeef](https://github.com/SteamClientHomebrew/Millennium/commit/41cfeef5f4174337c293a5950fc0329433f8302d))

## [2.19.2](https://github.com/SteamClientHomebrew/Millennium/compare/v2.19.1...v2.19.2) (2025-03-28)

### Bug Fixes

-   Fix setup tools not updating before installing required packages. ([cf6b67b](https://github.com/SteamClientHomebrew/Millennium/commit/cf6b67b43c6160f491a06b3671d15db215fe8d24))
-   Temporarily disable 'steam://open/millennium as it broke "View Profile" button on friends list. ([d329f7a](https://github.com/SteamClientHomebrew/Millennium/commit/d329f7adb306eaba4a9659807ef538ad5f363614))

## [2.19.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.19.0...v2.19.1) (2025-03-28)

### Bug Fixes

-   Fix the CI ([f416425](https://github.com/SteamClientHomebrew/Millennium/commit/f4164253ee85991907b93ad54bfb16e9025af504))
-   Fix the CI building against the wrong version of Millennium. ([e12f160](https://github.com/SteamClientHomebrew/Millennium/commit/e12f1609e681a11b676515a67cc4df264ecb53e4))
-   Fix typo in welcome modal. ([e06c3c1](https://github.com/SteamClientHomebrew/Millennium/commit/e06c3c163f4e6bb1ed17fc44ddcec7f09e411651))

# [2.19.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.18.0...v2.19.0) (2025-03-28)

### Bug Fixes

-   Use the proper queued shim path ([ddddbb4](https://github.com/SteamClientHomebrew/Millennium/commit/ddddbb43b42981917491206ee6c597cb845b0546))

### Features

-   Add steam://open/millennium URL to open settings ([7bcc7e2](https://github.com/SteamClientHomebrew/Millennium/commit/7bcc7e2aeebfa2750fbe0b1cc8d25ceccea9e074))

# [2.19.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.18.0...v2.19.0) (2025-03-28)

### Features

-   Add steam://open/millennium URL to open settings ([7bcc7e2](https://github.com/SteamClientHomebrew/Millennium/commit/7bcc7e2aeebfa2750fbe0b1cc8d25ceccea9e074))

# [2.19.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.18.0...v2.19.0) (2025-03-28)

### Features

-   Add steam://open/millennium URL to open settings ([7bcc7e2](https://github.com/SteamClientHomebrew/Millennium/commit/7bcc7e2aeebfa2750fbe0b1cc8d25ceccea9e074))

# [2.18.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.17.2...v2.18.0) (2025-03-28)

### Bug Fixes

-   allow frontend function to send booleans & numbers to backend ([#198](https://github.com/SteamClientHomebrew/Millennium/issues/198)) ([aa4f054](https://github.com/SteamClientHomebrew/Millennium/commit/aa4f0547ca68ed3f3480a401de9b81c7e28f26bb))
-   Allow importing raw files like fonts, images, etc. from the webkit. ([fd82cd1](https://github.com/SteamClientHomebrew/Millennium/commit/fd82cd1ad9fae9c8e956d53b3e627164659a88bb))
-   Closes [#159](https://github.com/SteamClientHomebrew/Millennium/issues/159) ([2f43350](https://github.com/SteamClientHomebrew/Millennium/commit/2f433503b506bf3c1366df1bec6abfe4eef5cfa4))
-   Enable automatic proxy detection on Windows ([#219](https://github.com/SteamClientHomebrew/Millennium/issues/219)) ([f15c932](https://github.com/SteamClientHomebrew/Millennium/commit/f15c9324fe8187c6acdf35ae176f6d9814f9cc18))
-   Fix [#253](https://github.com/SteamClientHomebrew/Millennium/issues/253) [#159](https://github.com/SteamClientHomebrew/Millennium/issues/159) [#148](https://github.com/SteamClientHomebrew/Millennium/issues/148) ?? ([bebdfb5](https://github.com/SteamClientHomebrew/Millennium/commit/bebdfb5b08f183e0793e80204accf90ab5c6ee6e))
-   Fix AUR PKGBUILD ([3badb80](https://github.com/SteamClientHomebrew/Millennium/commit/3badb80b5c687a21e636d2871dda480a3365e67c))
-   Fix custom accent color using RGBA instead of RGB. closes [#229](https://github.com/SteamClientHomebrew/Millennium/issues/229) ([4b095d6](https://github.com/SteamClientHomebrew/Millennium/commit/4b095d68693d18575ebde21a9b29c3bd8b6f9c28))
-   Fix debugger port reporting error when the port was not being used. ([00d1b89](https://github.com/SteamClientHomebrew/Millennium/commit/00d1b89dd54581d4b618a67564e417caee6cf3df))
-   Fix Millennium freezing if a plugin makes an FFI call to a backend that can't acquire the GIL. ([a7e3e1c](https://github.com/SteamClientHomebrew/Millennium/commit/a7e3e1c3d9d476d9078d238c45750cef4b34bf04))
-   Fix Millennium not shutting down properly & improved developer warnings on potential issues ([b960bfe](https://github.com/SteamClientHomebrew/Millennium/commit/b960bfe070effe26a5e55d80202089fe77155798))
-   Fix Millennium trying to inject CSS as JS ([4e1cc7f](https://github.com/SteamClientHomebrew/Millennium/commit/4e1cc7f01476847716760602a231dbe179b8b0b1))
-   Fix Millennium trying to update to an older version if you're on a beta/alpha release. ([328aedd](https://github.com/SteamClientHomebrew/Millennium/commit/328aedd06b9b2a1b79bebbb4c04de7f2a0ac13ce))
-   Fix package manager to maintain backwards compatibility with old requirements.txt format ([aee4361](https://github.com/SteamClientHomebrew/Millennium/commit/aee4361bae99dbee8088ff2ad58fffaa3ec27e82))
-   Fix PKGBUILD to use arch based FS ([b9c78f8](https://github.com/SteamClientHomebrew/Millennium/commit/b9c78f80c57211a88490d6c5580bf7082eaeb73f))
-   Fix plugin webkit shims not injecting after plugin enable. ([3c6de9f](https://github.com/SteamClientHomebrew/Millennium/commit/3c6de9fdfbd6913e43de0582d99c0dc52ea99e50))
-   Fix README.md code line stats ([afafdf7](https://github.com/SteamClientHomebrew/Millennium/commit/afafdf7f24aa920ededb16dfdd9c9a53e8595bbd))
-   Fix welcome modal not highlighting Millennium properly ([703e9d3](https://github.com/SteamClientHomebrew/Millennium/commit/703e9d376b748e2b878859d81e4169eaba8c0e24))
-   Generic bug fixes ([82a0b11](https://github.com/SteamClientHomebrew/Millennium/commit/82a0b11664d2f8949064ccdc421cae39f86ce433))
-   Pipe stdout to Millennium logger. ([8db49ac](https://github.com/SteamClientHomebrew/Millennium/commit/8db49ac70d873cc4476fa293b72a8d71526e5447))
-   Plugins not loading on UNIX ([58bc696](https://github.com/SteamClientHomebrew/Millennium/commit/58bc696d4d219da1e1f91bd606ab714820f4d488))
-   Properly set python home directory ([904ad08](https://github.com/SteamClientHomebrew/Millennium/commit/904ad0814d4bbcca2b4ae08247514616c9b01fb0))
-   Remove leading "v" in pkgver ([#279](https://github.com/SteamClientHomebrew/Millennium/issues/279)) ([1fb9920](https://github.com/SteamClientHomebrew/Millennium/commit/1fb99205ac82451579f2e87b58c09e36fe9c4738))
-   **security:** Fix a vulnerability where any website could connect to Millennium and install themes. ([47639c3](https://github.com/SteamClientHomebrew/Millennium/commit/47639c30aebb6e398537661a2c30a089c60912e3))
-   Show the Steam UI after all plugins are finished loading instead of when the SharedJSContext connects ([b5730a3](https://github.com/SteamClientHomebrew/Millennium/commit/b5730a325b5790a3cb9cdc60c6bbf3f9d6b0adcb))
-   Some UNIX bug fixes ([d6d8c9c](https://github.com/SteamClientHomebrew/Millennium/commit/d6d8c9c292635bccc0a294c88a970477347daac8))
-   Update german localization ([#276](https://github.com/SteamClientHomebrew/Millennium/issues/276)) ([d528b57](https://github.com/SteamClientHomebrew/Millennium/commit/d528b5745a45f3b824ca1d99a3ace3c13c4ba425))
-   Use XDG base directory variables ([b2dc64d](https://github.com/SteamClientHomebrew/Millennium/commit/b2dc64d54c4a728d03f564aef65d275e65193305))
-   Whoops, didn't mean to commit those. closes [#249](https://github.com/SteamClientHomebrew/Millennium/issues/249) ([ef2f0fa](https://github.com/SteamClientHomebrew/Millennium/commit/ef2f0fa2bb973ddc58acf3d788c528ffcdf1491c))

### Features

-   Ability to enable/disable multiple plugins before reloading. Closes [#281](https://github.com/SteamClientHomebrew/Millennium/issues/281) ([5858811](https://github.com/SteamClientHomebrew/Millennium/commit/5858811c4127501c24b8aa6e745b5b28f7975bc7))
-   Add embedded updater ([24de43b](https://github.com/SteamClientHomebrew/Millennium/commit/24de43b8a22f116922c05b12e5538f7045370130))
-   Add enabled plugin names to <html> element to make CSS styling easier. [#258](https://github.com/SteamClientHomebrew/Millennium/issues/258) ([938bb82](https://github.com/SteamClientHomebrew/Millennium/commit/938bb82c06a82f1d916bf9c28947e5c37f22bdfa))
-   Add Italian localization ([#209](https://github.com/SteamClientHomebrew/Millennium/issues/209)) ([de5a9d2](https://github.com/SteamClientHomebrew/Millennium/commit/de5a9d238062366fcc1b1e9e379ffd980223541d))
-   Add linux build inside docker container ([#262](https://github.com/SteamClientHomebrew/Millennium/issues/262)) ([dbf913c](https://github.com/SteamClientHomebrew/Millennium/commit/dbf913ccc9ec6416228d381a44711181b331b690))
-   Add more info to plugins page ([1e3a955](https://github.com/SteamClientHomebrew/Millennium/commit/1e3a955b2a84532cb46a044a6001fcae46a260bd))
-   add Vietnamese localization ([#208](https://github.com/SteamClientHomebrew/Millennium/issues/208)) ([3e83de5](https://github.com/SteamClientHomebrew/Millennium/commit/3e83de5c5434fd2d71cc40c28024513859cda0be))
-   Ask users if they want auto updates, or to review updates, or to disable updates entirely. ([62553cf](https://github.com/SteamClientHomebrew/Millennium/commit/62553cf11599a532cec605cc6b61e68476c495c8))
-   Better UNIX system folder heirarchy ([#247](https://github.com/SteamClientHomebrew/Millennium/issues/247)) ([cbe1fa1](https://github.com/SteamClientHomebrew/Millennium/commit/cbe1fa16e3c08cc6a39e83822b5456a4f4016585)), closes [#230](https://github.com/SteamClientHomebrew/Millennium/issues/230) [#234](https://github.com/SteamClientHomebrew/Millennium/issues/234)
-   Remove CLI tool, most likely revamping it. ([83c0a56](https://github.com/SteamClientHomebrew/Millennium/commit/83c0a568ac17d8ab8ad0707a6562d5fa2e627d19))
-   Show welcome modal to new users ([7ea8358](https://github.com/SteamClientHomebrew/Millennium/commit/7ea8358649270044a35c4bf1e091f7b4bead894e))
-   Warn users of incompatible Steam.cfg files. ([197e574](https://github.com/SteamClientHomebrew/Millennium/commit/197e5742e9c3862cd9d395405f315d1db345ef81))
-   Warn users when no themes were found instead of showing empty dropdown. ([6731867](https://github.com/SteamClientHomebrew/Millennium/commit/6731867ff83505e6302369349957c3e53983eecc))

# [2.18.0-beta.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.17.2...v2.18.0-beta.1) (2025-03-21)

### Bug Fixes

-   allow frontend function to send booleans & numbers to backend ([#198](https://github.com/SteamClientHomebrew/Millennium/issues/198)) ([aa4f054](https://github.com/SteamClientHomebrew/Millennium/commit/aa4f0547ca68ed3f3480a401de9b81c7e28f26bb))
-   Allow importing raw files like fonts, images, etc. from the webkit. ([fd82cd1](https://github.com/SteamClientHomebrew/Millennium/commit/fd82cd1ad9fae9c8e956d53b3e627164659a88bb))
-   Closes [#159](https://github.com/SteamClientHomebrew/Millennium/issues/159) ([2f43350](https://github.com/SteamClientHomebrew/Millennium/commit/2f433503b506bf3c1366df1bec6abfe4eef5cfa4))
-   Enable automatic proxy detection on Windows ([#219](https://github.com/SteamClientHomebrew/Millennium/issues/219)) ([f15c932](https://github.com/SteamClientHomebrew/Millennium/commit/f15c9324fe8187c6acdf35ae176f6d9814f9cc18))
-   Fix [#253](https://github.com/SteamClientHomebrew/Millennium/issues/253) [#159](https://github.com/SteamClientHomebrew/Millennium/issues/159) [#148](https://github.com/SteamClientHomebrew/Millennium/issues/148) ?? ([bebdfb5](https://github.com/SteamClientHomebrew/Millennium/commit/bebdfb5b08f183e0793e80204accf90ab5c6ee6e))
-   Fix AUR PKGBUILD ([3badb80](https://github.com/SteamClientHomebrew/Millennium/commit/3badb80b5c687a21e636d2871dda480a3365e67c))
-   Fix custom accent color using RGBA instead of RGB. closes [#229](https://github.com/SteamClientHomebrew/Millennium/issues/229) ([4b095d6](https://github.com/SteamClientHomebrew/Millennium/commit/4b095d68693d18575ebde21a9b29c3bd8b6f9c28))
-   Fix debugger port reporting error when the port was not being used. ([00d1b89](https://github.com/SteamClientHomebrew/Millennium/commit/00d1b89dd54581d4b618a67564e417caee6cf3df))
-   Fix Millennium freezing if a plugin makes an FFI call to a backend that can't acquire the GIL. ([a7e3e1c](https://github.com/SteamClientHomebrew/Millennium/commit/a7e3e1c3d9d476d9078d238c45750cef4b34bf04))
-   Fix Millennium not shutting down properly & improved developer warnings on potential issues ([b960bfe](https://github.com/SteamClientHomebrew/Millennium/commit/b960bfe070effe26a5e55d80202089fe77155798))
-   Fix Millennium trying to inject CSS as JS ([4e1cc7f](https://github.com/SteamClientHomebrew/Millennium/commit/4e1cc7f01476847716760602a231dbe179b8b0b1))
-   Fix package manager to maintain backwards compatibility with old requirements.txt format ([aee4361](https://github.com/SteamClientHomebrew/Millennium/commit/aee4361bae99dbee8088ff2ad58fffaa3ec27e82))
-   Fix PKGBUILD to use arch based FS ([b9c78f8](https://github.com/SteamClientHomebrew/Millennium/commit/b9c78f80c57211a88490d6c5580bf7082eaeb73f))
-   Fix plugin webkit shims not injecting after plugin enable. ([3c6de9f](https://github.com/SteamClientHomebrew/Millennium/commit/3c6de9fdfbd6913e43de0582d99c0dc52ea99e50))
-   Fix README.md code line stats ([afafdf7](https://github.com/SteamClientHomebrew/Millennium/commit/afafdf7f24aa920ededb16dfdd9c9a53e8595bbd))
-   Generic bug fixes ([82a0b11](https://github.com/SteamClientHomebrew/Millennium/commit/82a0b11664d2f8949064ccdc421cae39f86ce433))
-   Pipe stdout to Millennium logger. ([8db49ac](https://github.com/SteamClientHomebrew/Millennium/commit/8db49ac70d873cc4476fa293b72a8d71526e5447))
-   Plugins not loading on UNIX ([58bc696](https://github.com/SteamClientHomebrew/Millennium/commit/58bc696d4d219da1e1f91bd606ab714820f4d488))
-   Properly set python home directory ([904ad08](https://github.com/SteamClientHomebrew/Millennium/commit/904ad0814d4bbcca2b4ae08247514616c9b01fb0))
-   **security:** Fix a vulnerability where any website could connect to Millennium and install themes. ([47639c3](https://github.com/SteamClientHomebrew/Millennium/commit/47639c30aebb6e398537661a2c30a089c60912e3))
-   Show the Steam UI after all plugins are finished loading instead of when the SharedJSContext connects ([b5730a3](https://github.com/SteamClientHomebrew/Millennium/commit/b5730a325b5790a3cb9cdc60c6bbf3f9d6b0adcb))
-   Some UNIX bug fixes ([d6d8c9c](https://github.com/SteamClientHomebrew/Millennium/commit/d6d8c9c292635bccc0a294c88a970477347daac8))
-   Whoops, didn't mean to commit those. closes [#249](https://github.com/SteamClientHomebrew/Millennium/issues/249) ([ef2f0fa](https://github.com/SteamClientHomebrew/Millennium/commit/ef2f0fa2bb973ddc58acf3d788c528ffcdf1491c))

### Features

-   Add embedded updater ([24de43b](https://github.com/SteamClientHomebrew/Millennium/commit/24de43b8a22f116922c05b12e5538f7045370130))
-   Add enabled plugin names to <html> element to make CSS styling easier. [#258](https://github.com/SteamClientHomebrew/Millennium/issues/258) ([938bb82](https://github.com/SteamClientHomebrew/Millennium/commit/938bb82c06a82f1d916bf9c28947e5c37f22bdfa))
-   Add Italian localization ([#209](https://github.com/SteamClientHomebrew/Millennium/issues/209)) ([de5a9d2](https://github.com/SteamClientHomebrew/Millennium/commit/de5a9d238062366fcc1b1e9e379ffd980223541d))
-   Add more info to plugins page ([1e3a955](https://github.com/SteamClientHomebrew/Millennium/commit/1e3a955b2a84532cb46a044a6001fcae46a260bd))
-   add Vietnamese localization ([#208](https://github.com/SteamClientHomebrew/Millennium/issues/208)) ([3e83de5](https://github.com/SteamClientHomebrew/Millennium/commit/3e83de5c5434fd2d71cc40c28024513859cda0be))
-   Ask users if they want auto updates, or to review updates, or to disable updates entirely. ([62553cf](https://github.com/SteamClientHomebrew/Millennium/commit/62553cf11599a532cec605cc6b61e68476c495c8))
-   Better UNIX system folder heirarchy ([#247](https://github.com/SteamClientHomebrew/Millennium/issues/247)) ([cbe1fa1](https://github.com/SteamClientHomebrew/Millennium/commit/cbe1fa16e3c08cc6a39e83822b5456a4f4016585)), closes [#230](https://github.com/SteamClientHomebrew/Millennium/issues/230) [#234](https://github.com/SteamClientHomebrew/Millennium/issues/234)
-   Remove CLI tool, most likely revamping it. ([83c0a56](https://github.com/SteamClientHomebrew/Millennium/commit/83c0a568ac17d8ab8ad0707a6562d5fa2e627d19))
-   Show welcome modal to new users ([7ea8358](https://github.com/SteamClientHomebrew/Millennium/commit/7ea8358649270044a35c4bf1e091f7b4bead894e))
-   Warn users of incompatible Steam.cfg files. ([197e574](https://github.com/SteamClientHomebrew/Millennium/commit/197e5742e9c3862cd9d395405f315d1db345ef81))
-   Warn users when no themes were found instead of showing empty dropdown. ([6731867](https://github.com/SteamClientHomebrew/Millennium/commit/6731867ff83505e6302369349957c3e53983eecc))

## [2.17.2](https://github.com/SteamClientHomebrew/Millennium/compare/v2.17.1...v2.17.2) (2024-12-29)

### Bug Fixes

-   Fix overlay browser not loading on pages without a response phrase. ([7d0fbcf](https://github.com/SteamClientHomebrew/Millennium/commit/7d0fbcf365f0d6a7f3d163a3f265c1cf45c595ec))

## [2.17.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.17.0...v2.17.1) (2024-12-29)

### Bug Fixes

-   Fix workshop pages not rendering HTML. ([4614cc8](https://github.com/SteamClientHomebrew/Millennium/commit/4614cc81776ed0731d5324723a0466a2a74537d0))

# [2.17.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.16.2...v2.17.0) (2024-12-29)

### Bug Fixes

-   Add proxy support for web requests within Steam. ([71dabc6](https://github.com/SteamClientHomebrew/Millennium/commit/71dabc6c5299de1f3b5dd2053dad5f3d4a8856a7))
-   Fix installer script ([fb4053d](https://github.com/SteamClientHomebrew/Millennium/commit/fb4053dcb299311daac5df20dcca3409d3298af7))
-   Fix webkit and CSP related issues. closes [#197](https://github.com/SteamClientHomebrew/Millennium/issues/197), [#196](https://github.com/SteamClientHomebrew/Millennium/issues/196), [#194](https://github.com/SteamClientHomebrew/Millennium/issues/194) ([e2cd49d](https://github.com/SteamClientHomebrew/Millennium/commit/e2cd49dd7b4911ededf5d16c5446f0221de35d4e))
-   Fix webkit issues, Close [#194](https://github.com/SteamClientHomebrew/Millennium/issues/194), [#196](https://github.com/SteamClientHomebrew/Millennium/issues/196) ([2c91a95](https://github.com/SteamClientHomebrew/Millennium/commit/2c91a9517bbe662e5227304c63dafdbfabee7ac9))
-   Fix webkit patcher edge cases on redirects ([2573215](https://github.com/SteamClientHomebrew/Millennium/commit/25732155fc5c4cb8a2d1b036b63a404b495eae94))
-   Fix webkit patcher skipping non-secure requests. ([b9a6d0d](https://github.com/SteamClientHomebrew/Millennium/commit/b9a6d0d0fef4f66f5bf0bd027dd45e98f710ff21))

### Features

-   Add system accent color to webkit ([af602c3](https://github.com/SteamClientHomebrew/Millennium/commit/af602c30e140a1588d901417d9b6d83a590ed4f6))

## [2.16.2](https://github.com/SteamClientHomebrew/Millennium/compare/v2.16.1...v2.16.2) (2024-12-21)

### Bug Fixes

-   Fix installer crashes (again) ([bfafcb7](https://github.com/SteamClientHomebrew/Millennium/commit/bfafcb79253fb0fb3475b35e87229dfa11c2471a))

## [2.16.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.16.0...v2.16.1) (2024-12-20)

### Bug Fixes

-   Catch installer socket being used instead of crashing. ([8817735](https://github.com/SteamClientHomebrew/Millennium/commit/88177355d74b53ad7671e35831f6c050f842172c))
-   Fix crashing on new installs ([9b7e1e5](https://github.com/SteamClientHomebrew/Millennium/commit/9b7e1e52b21556c6935112b92233ea75b52b69ba))
-   Fix unix pathing ([07dc66c](https://github.com/SteamClientHomebrew/Millennium/commit/07dc66cc0d707153e976d52b3fe981694c1fa5b3))
-   Properly handle theme config with invalid props. ([d25461d](https://github.com/SteamClientHomebrew/Millennium/commit/d25461d34f6e9790d18cc667395268a32508fb2a))

# [2.16.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.15.0...v2.16.0) (2024-12-19)

### Bug Fixes

-   **CI:** Fix CI ([b897b49](https://github.com/SteamClientHomebrew/Millennium/commit/b897b4901fa53ba8a76860c368a30b240ff129e6))
-   **CI:** Fix CI ([914df34](https://github.com/SteamClientHomebrew/Millennium/commit/914df34aef0f8b531f01e9c7dde8be5dd6543a3d))
-   Close installer after successful install ([cfd961c](https://github.com/SteamClientHomebrew/Millennium/commit/cfd961c54b59808b625a9dfbe077ae29940998b5))
-   Fix plugin JS being removed from webkit when a new theme is selected. ([a29c7df](https://github.com/SteamClientHomebrew/Millennium/commit/a29c7df0aeb1114bfb0c1c515231ce5fa7faf5fb))
-   Fix settings icons not being centered and plugin settings button not having propper styling ([#184](https://github.com/SteamClientHomebrew/Millennium/issues/184)) ([5fddc2d](https://github.com/SteamClientHomebrew/Millennium/commit/5fddc2db498d84a1da321c1301fafa1baac106fc))
-   Fix system accent color not working on some startups ([2eb7a94](https://github.com/SteamClientHomebrew/Millennium/commit/2eb7a943a951fe965d5e749c6b04b0573918d1d8))
-   Fix the artifact CI ([3faf711](https://github.com/SteamClientHomebrew/Millennium/commit/3faf7111cbecab18d6351abc9a8d55746c88085e))
-   Fix typo in install.sh ([#178](https://github.com/SteamClientHomebrew/Millennium/issues/178)) ([76349b3](https://github.com/SteamClientHomebrew/Millennium/commit/76349b3aa7374a67b408fad9583b0073164abb8d)), closes [#4](https://github.com/SteamClientHomebrew/Millennium/issues/4)
-   Fix typo on themes page [#168](https://github.com/SteamClientHomebrew/Millennium/issues/168) ([e05ec19](https://github.com/SteamClientHomebrew/Millennium/commit/e05ec1962999e57a4662b8391a0b379e3a2c82ee))
-   Prevent debug info from growing insanely large [#176](https://github.com/SteamClientHomebrew/Millennium/issues/176) ([d23bec9](https://github.com/SteamClientHomebrew/Millennium/commit/d23bec9832d8dbe9888a95d765f36d0cf9e6a5b4))
-   **Unix:** Fix LD_PRELOAD variable interfering with Steam games. ([cbfd653](https://github.com/SteamClientHomebrew/Millennium/commit/cbfd653b3980d42dd529fc4c84028271e0c6d4e2))
-   Use correct classes for Field ([#189](https://github.com/SteamClientHomebrew/Millennium/issues/189)) ([4ce6b5d](https://github.com/SteamClientHomebrew/Millennium/commit/4ce6b5d084eb5dfce022e5a4bcc7e68833f3a902))

### Features

-   Add better webkit support for plugins ([33b6cde](https://github.com/SteamClientHomebrew/Millennium/commit/33b6cde0091dab72761ebb4e0b051471d20b94ca))
-   Add Swedish localization. ([#180](https://github.com/SteamClientHomebrew/Millennium/issues/180)) ([0d9e8b4](https://github.com/SteamClientHomebrew/Millennium/commit/0d9e8b49cbfac3950e6a0bb280ca3cc6d22739c4))
-   Added CPS bypass & Added Millennium API to webkit modules ([eda0f54](https://github.com/SteamClientHomebrew/Millennium/commit/eda0f5460061075e0e389c9cacbd270a97c18739))
-   Conditional webkit patching based on URL with regex [#127](https://github.com/SteamClientHomebrew/Millennium/issues/127) ([bf36bd5](https://github.com/SteamClientHomebrew/Millennium/commit/bf36bd537c19ae5c5a10fdc6b3e86db3947dd862))
-   **Security:** Blacklist certain pages, like the checkout, from being injected into by plugins. ([54edc4c](https://github.com/SteamClientHomebrew/Millennium/commit/54edc4c6f82f6f6b41fed29ce7f0e7b01ba200c9))
-   Slightly Better Russian Translation ([#187](https://github.com/SteamClientHomebrew/Millennium/issues/187)) ([639390d](https://github.com/SteamClientHomebrew/Millennium/commit/639390dab1c9367cc72a3bff98dc454fa55ccbb0))
-   Softer and better crash detection. ([fc5e756](https://github.com/SteamClientHomebrew/Millennium/commit/fc5e7568757f72e020cfa3def59cb9c6026284d2))
-   Updated plugin support for better webkit modding. ([1a8daf0](https://github.com/SteamClientHomebrew/Millennium/commit/1a8daf048515c8c01b8ce703838c7da6efb40771))

# [2.15.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.14.2...v2.15.0) (2024-11-12)

### Features

-   Binary stripping on release modules to drastically reduce binary size ([45734f2](https://github.com/SteamClientHomebrew/Millennium/commit/45734f2be936a2ed58072f96d52c5d68945d6e71))

## [2.14.2](https://github.com/SteamClientHomebrew/Millennium/compare/v2.14.1...v2.14.2) (2024-11-12)

### Bug Fixes

-   Fix the CI ([7c29d23](https://github.com/SteamClientHomebrew/Millennium/commit/7c29d23fecaf2f3f6b760bf95f5d368db87e2a3f))
-   Fix theme installer not working ([559ae66](https://github.com/SteamClientHomebrew/Millennium/commit/559ae6617d79f2772bace63d3df1b4f049b764c2))
-   Hopefully help prevent false positives ([d448ab1](https://github.com/SteamClientHomebrew/Millennium/commit/d448ab12ed0b8bda10a17ced92123b91a2ef06ad))

## [2.14.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.14.0...v2.14.1) (2024-11-09)

### Bug Fixes

-   Fix theme editor. ([6446ebe](https://github.com/SteamClientHomebrew/Millennium/commit/6446ebe8b7d60dce828ce318a83009f9d1634a0b))

# [2.14.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.13.1...v2.14.0) (2024-11-09)

### Bug Fixes

-   **Linux:** Fix hang on shutdown [#142](https://github.com/SteamClientHomebrew/Millennium/issues/142) ([e8e9790](https://github.com/SteamClientHomebrew/Millennium/commit/e8e9790099c50ef804301995d56a21ade8b7295d))

### Features

-   Better error logging for plugin backends ([45433c0](https://github.com/SteamClientHomebrew/Millennium/commit/45433c03842227c80c9482d649b9aff2641c55d0))
-   **Unix:** Add theme auto installer & update manager ([2a8a880](https://github.com/SteamClientHomebrew/Millennium/commit/2a8a8803a160f5abfd503c2a84be8371c7f13e81))

## [2.13.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.13.0...v2.13.1) (2024-11-03)

### Bug Fixes

-   Fix race condition on startup ([b4131ef](https://github.com/SteamClientHomebrew/Millennium/commit/b4131efa0650e480ee064782e9f5b27ec4875eb2))
-   Fix startup crashes ([b00dd37](https://github.com/SteamClientHomebrew/Millennium/commit/b00dd378e63daa976ae5e1fa0770a1133b742ee3))
-   Fix startup crashes [#153](https://github.com/SteamClientHomebrew/Millennium/issues/153) ([256bc77](https://github.com/SteamClientHomebrew/Millennium/commit/256bc778d47e2b2428c5366310ddd725334f4bb1))

# [2.13.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.12.4...v2.13.0) (2024-11-02)

### Bug Fixes

-   Add file description and details to help prevent false positives. ([0fd35ad](https://github.com/SteamClientHomebrew/Millennium/commit/0fd35ad6e91f84b2e0119cad9e478de79eb050f1))
-   Create debugger flag from installer instead of Millennium ([652945d](https://github.com/SteamClientHomebrew/Millennium/commit/652945d0bd377e34cfef4ee7be127c74db515f5f))
-   Fix all issues with steam re-opening unskinned, and the UI freezing ([6f5cd67](https://github.com/SteamClientHomebrew/Millennium/commit/6f5cd6715b6c7201c9b246ec8d887a893917d753))
-   Fix std::future_error by mutex ([75dd852](https://github.com/SteamClientHomebrew/Millennium/commit/75dd852d1991e17c0aa17c34a80ad41d9036ac1a))
-   Fix uninstaller bugs and improve cleanup ([a923e2a](https://github.com/SteamClientHomebrew/Millennium/commit/a923e2aca843c44ff8063db5169f33be8bce8ef7))
-   Fully fix plugin hot reloadability. Plugins can now be loaded/unloaded at any time, in any order ([af651b5](https://github.com/SteamClientHomebrew/Millennium/commit/af651b5482044be0128b302131a2a6f31c5638ac))
-   Temporarily disable CLI support for Millennium on windows. ([02d9a76](https://github.com/SteamClientHomebrew/Millennium/commit/02d9a76e92498b52a59c1212a04d7d42a5232ebc))

### Features

-   Ability to override system accent color ([a850936](https://github.com/SteamClientHomebrew/Millennium/commit/a850936e40688345a90646d92600cd6e506ea623))
-   Add regex support for webkit patching ([#147](https://github.com/SteamClientHomebrew/Millennium/issues/147)) ([0c87da1](https://github.com/SteamClientHomebrew/Millennium/commit/0c87da152c1e8a5a00bc787978214ba4839efe70)), closes [#127](https://github.com/SteamClientHomebrew/Millennium/issues/127) [#140](https://github.com/SteamClientHomebrew/Millennium/issues/140)

## [2.12.4](https://github.com/SteamClientHomebrew/Millennium/compare/v2.12.3...v2.12.4) (2024-10-11)

### Bug Fixes

-   Fix issues with the plugin example crashing. ([8624fab](https://github.com/SteamClientHomebrew/Millennium/commit/8624fab5942c684291edc1c0b8a090731dcd91c0))

## [2.12.3](https://github.com/SteamClientHomebrew/Millennium/compare/v2.12.2...v2.12.3) (2024-10-07)

### Bug Fixes

-   Actually fix the CI. ([6051ee2](https://github.com/SteamClientHomebrew/Millennium/commit/6051ee2fa4e307633cd143fced91c2507a39bf24))

## [2.12.2](https://github.com/SteamClientHomebrew/Millennium/compare/v2.12.1...v2.12.2) (2024-10-07)

### Bug Fixes

-   Fix CI ([966fc22](https://github.com/SteamClientHomebrew/Millennium/commit/966fc22422e1b38c6f09c81984f57b53c8445ba7))
-   Fix CI output paths ([9bf0b09](https://github.com/SteamClientHomebrew/Millennium/commit/9bf0b09e3ed3c8b8c160e5f30198f86b66b9e967))
-   Platform bug fixes ([2b63f68](https://github.com/SteamClientHomebrew/Millennium/commit/2b63f682c9e5b5d969251a2ed0b39c2d7a1f098c))
-   Update installed themes in the dropdown without having to close and open settings ([e7303c1](https://github.com/SteamClientHomebrew/Millennium/commit/e7303c174eb6fb2f0974a6fe3a014ab60c839b08))

## [2.12.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.12.0...v2.12.1) (2024-10-06)

### Bug Fixes

-   Fix updater bug. ([acb0437](https://github.com/SteamClientHomebrew/Millennium/commit/acb0437367736cecbd5d65123e08620ed043f24b))

# [2.12.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.11.1...v2.12.0) (2024-10-06)

### Bug Fixes

-   Check if jq is installed ([#109](https://github.com/SteamClientHomebrew/Millennium/issues/109)) ([319c814](https://github.com/SteamClientHomebrew/Millennium/commit/319c81453331370ca63bc3ed8cf8227fef4712d7))
-   Fix issues where target port is "taken" when it's actually open and usable. [#122](https://github.com/SteamClientHomebrew/Millennium/issues/122) ([ffce333](https://github.com/SteamClientHomebrew/Millennium/commit/ffce333834b8e255c815def3b2d68d5bf4045310))
-   Fix updater not restarting steam properly ([2ece336](https://github.com/SteamClientHomebrew/Millennium/commit/2ece33607904656847ac1594f6e3b8a7094e5a2f))
-   Prevent logs files from getting too large ([e2aa7fd](https://github.com/SteamClientHomebrew/Millennium/commit/e2aa7fd1927e1caf78628e97b25e8b1aa05ff8fc))
-   Update theme dialog dropdown content on the fly. ([1944410](https://github.com/SteamClientHomebrew/Millennium/commit/194441091a7dfa13fd0bd2d6eadbb85a98a55dc6))

### Features

-   Add "webkitCSS" && "webkitJS" options ([019565e](https://github.com/SteamClientHomebrew/Millennium/commit/019565e60f68d51a45a20acf8a67255cd50f8ad2))
-   Add auto theme installer ([b732bc9](https://github.com/SteamClientHomebrew/Millennium/commit/b732bc93684753b1164154a1f4bc2ee605d4357e))
-   Add webkit JS option in skin.json ([3d360a4](https://github.com/SteamClientHomebrew/Millennium/commit/3d360a4d4a98bc366b807fcd46248980a092f21a))

## [2.11.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.11.0...v2.11.1) (2024-09-01)

### Bug Fixes

-   Fix skin not applying after BPM exit [#96](https://github.com/SteamClientHomebrew/Millennium/issues/96) ([ba9e001](https://github.com/SteamClientHomebrew/Millennium/commit/ba9e001c92f24e0d5420e41ae696789601b0285f))

# [2.11.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.10.1...v2.11.0) (2024-08-31)

### Features

-   Theme option tabs ([#94](https://github.com/SteamClientHomebrew/Millennium/issues/94)) ([cc6e339](https://github.com/SteamClientHomebrew/Millennium/commit/cc6e339ef454478c9945a8512851ff79a3a12c1b))

## [2.10.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.10.0...v2.10.1) (2024-08-28)

### Bug Fixes

-   Fix race condition causing boot loop ([f3c9e88](https://github.com/SteamClientHomebrew/Millennium/commit/f3c9e881eca3642885eb953801dc6dcc4bcd0058))
-   Fix Unix start script paths ([f4f2bb7](https://github.com/SteamClientHomebrew/Millennium/commit/f4f2bb7675e5e3a0ead907f69385683624624d63))

# [2.10.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.9.4...v2.10.0) (2024-08-28)

### Bug Fixes

-   Check if a queried plugin is already loaded before starting it ([5fa6d99](https://github.com/SteamClientHomebrew/Millennium/commit/5fa6d998b5938c410689dbeb9bb6461425813c87))
-   Decrease release binary size on linux ([dd0600a](https://github.com/SteamClientHomebrew/Millennium/commit/dd0600ac8906d81ffc281566ea4ec839f54a2a64))
-   Fix CI ([c952fbf](https://github.com/SteamClientHomebrew/Millennium/commit/c952fbf10f0af532e86430bbc8b37c99fff44aa8))
-   Fix CLI paths to use updated refs ([59b91dd](https://github.com/SteamClientHomebrew/Millennium/commit/59b91ddd70e8593f55e3731850ce16d0eb392a48))
-   Fix crashes on Steam close ([4d09aa6](https://github.com/SteamClientHomebrew/Millennium/commit/4d09aa688dd31758a222f5a9d44761fcb4086e14))
-   Fix edge case SEGV ([b17146d](https://github.com/SteamClientHomebrew/Millennium/commit/b17146d3febe448c577bf19ac9107f931e93144b))
-   Fix linux startup issues [#75](https://github.com/SteamClientHomebrew/Millennium/issues/75) ([dad87ba](https://github.com/SteamClientHomebrew/Millennium/commit/dad87ba8ba76f4df4ff033f14f68d2c53651a85f))
-   Fix Mac OS support. ([6b9997b](https://github.com/SteamClientHomebrew/Millennium/commit/6b9997be621223c0fb1ce64c4c09aa8fc7d68f93))
-   Fix race condition causing Millennium to get stuck on "Notifying frontend of backend load..." ([63973b2](https://github.com/SteamClientHomebrew/Millennium/commit/63973b293cfb22f6f1803cc3e46eee8353f4b5cb))
-   Fix startup bugs on Windows [#76](https://github.com/SteamClientHomebrew/Millennium/issues/76) ([b86c537](https://github.com/SteamClientHomebrew/Millennium/commit/b86c537b42ae5e11bf9793b2d7ab696e9fedcd96))
-   Fix startup issues on Linux ([9fcf293](https://github.com/SteamClientHomebrew/Millennium/commit/9fcf29307737bee8b1ca9473548b3958756f474d))
-   Fix startup issues on windows [#76](https://github.com/SteamClientHomebrew/Millennium/issues/76) ([aa2ade2](https://github.com/SteamClientHomebrew/Millennium/commit/aa2ade25f58da642c68b8305778d8b2619253369))
-   Fix threaded race condition ([08ab88d](https://github.com/SteamClientHomebrew/Millennium/commit/08ab88dc37a614c965b1b6f4d83d7953a7c688a6))
-   Issues where Steam would show prematurely ([486e892](https://github.com/SteamClientHomebrew/Millennium/commit/486e89232140ebe0512ce921f3a32b324d8f00ea))
-   Unix build bug fixes ([0745446](https://github.com/SteamClientHomebrew/Millennium/commit/0745446a6596b0a2435ad76d0e248686eb5dcfd7))

### Features

-   Better, easier to view installer for linux ([fd27c80](https://github.com/SteamClientHomebrew/Millennium/commit/fd27c802b49c150cd8ef6f701297041a810faeea))
-   Hot reload for plugins ([cdacaba](https://github.com/SteamClientHomebrew/Millennium/commit/cdacaba73197fd8a985ff96aaa19a8b122f5c652))
-   Show theme version in "About Theme" [#87](https://github.com/SteamClientHomebrew/Millennium/issues/87) ([f99046e](https://github.com/SteamClientHomebrew/Millennium/commit/f99046e053e6a4503564b74b2e71e93c9185bd0f))
-   Stage fully hot reloadable plugins ([79d4a27](https://github.com/SteamClientHomebrew/Millennium/commit/79d4a2744fb89a2b5836f013223fc2c439f82453))

### Performance Improvements

-   Improve shutdown speed on Linux ([b0a026f](https://github.com/SteamClientHomebrew/Millennium/commit/b0a026fd388cb8a706a8971312583e80c50ec072))
-   Startup performance improvements ([6a138d3](https://github.com/SteamClientHomebrew/Millennium/commit/6a138d39b44e37e16a81c8b8a0be89591885e8aa))

## [2.9.5](https://github.com/SteamClientHomebrew/Millennium/compare/v2.9.4...v2.9.5) (2024-08-09)

### Bug Fixes

-   Fix linux startup issues [#75](https://github.com/SteamClientHomebrew/Millennium/issues/75) ([dad87ba](https://github.com/SteamClientHomebrew/Millennium/commit/dad87ba8ba76f4df4ff033f14f68d2c53651a85f))
-   Fix startup bugs on Windows [#76](https://github.com/SteamClientHomebrew/Millennium/issues/76) ([b86c537](https://github.com/SteamClientHomebrew/Millennium/commit/b86c537b42ae5e11bf9793b2d7ab696e9fedcd96))

## [2.9.5](https://github.com/SteamClientHomebrew/Millennium/compare/v2.9.4...v2.9.5) (2024-08-09)

### Bug Fixes

-   Fix linux startup issues [#75](https://github.com/SteamClientHomebrew/Millennium/issues/75) ([dad87ba](https://github.com/SteamClientHomebrew/Millennium/commit/dad87ba8ba76f4df4ff033f14f68d2c53651a85f))

## [2.9.4](https://github.com/SteamClientHomebrew/Millennium/compare/v2.9.3...v2.9.4) (2024-08-08)

### Bug Fixes

-   (Linux) Permission & bug fixes ([56af75f](https://github.com/SteamClientHomebrew/Millennium/commit/56af75f8cee7bfd33d78badadfb3aa63cc5605ea))

## [2.9.3](https://github.com/SteamClientHomebrew/Millennium/compare/v2.9.2...v2.9.3) (2024-08-08)

### Bug Fixes

-   Fix config paths on linux ([07576b9](https://github.com/SteamClientHomebrew/Millennium/commit/07576b9ea51af006eecb050039a16ccedbf6240b))

## [2.9.2](https://github.com/SteamClientHomebrew/Millennium/compare/v2.9.1...v2.9.2) (2024-08-08)

### Bug Fixes

-   (Linux) Fix python binary paths ([76b40ff](https://github.com/SteamClientHomebrew/Millennium/commit/76b40ffaaec77eccf99ce85a2e30cf9fe05d85b6))

## [2.9.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.9.0...v2.9.1) (2024-08-08)

### Bug Fixes

-   Properly ship python libraries ([92ec03c](https://github.com/SteamClientHomebrew/Millennium/commit/92ec03c5843fb65222cf952142fe2890f9ccaa93))

## [2.9.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.9.0...v2.9.1) (2024-08-08)

### Bug Fixes

-   Properly ship python libraries ([92ec03c](https://github.com/SteamClientHomebrew/Millennium/commit/92ec03c5843fb65222cf952142fe2890f9ccaa93))

# [2.9.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.8.0...v2.9.0) (2024-08-08)

### Bug Fixes

-   Disable theme updater for compatibility until further notice ([6861a45](https://github.com/SteamClientHomebrew/Millennium/commit/6861a456bf868113af201f817646b075ac1c083b))
-   Fix watchdog threading errors ([cd0531b](https://github.com/SteamClientHomebrew/Millennium/commit/cd0531b44826ccb781f9286d4cb6734a5cba7844))
-   Properly segment install path and Steam path ([41f8ca8](https://github.com/SteamClientHomebrew/Millennium/commit/41f8ca8e4b96a06a1c7bf0286bd677f492b8d766))
-   Remove boxer on unix to prevent unneeded deps ([6b9953a](https://github.com/SteamClientHomebrew/Millennium/commit/6b9953a81e5eac96fb7d0a1cc26c17a2f0b7d488))
-   Simpler less verbose logs ([0c3e90a](https://github.com/SteamClientHomebrew/Millennium/commit/0c3e90aeea94061f443cd37be69ff2fd43981900))

### Features

-   Fix platform arch for 32 bit LD_PRELOAD-able binary ([515cb9e](https://github.com/SteamClientHomebrew/Millennium/commit/515cb9eb966c9d2adf9e5b3b2f51614b43bacabb))

# [2.8.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.7.2...v2.8.0) (2024-08-04)

### Bug Fixes

-   **CI:** Fix dependency issue on linux ([7e91f54](https://github.com/SteamClientHomebrew/Millennium/commit/7e91f54d19c4b4735e5dd15fdf43ee13013865a5))

### Features

-   Add install script for linux ([950ffa8](https://github.com/SteamClientHomebrew/Millennium/commit/950ffa8eccd131d35e101f4e195a1594ecb68d3a))

## [2.7.2](https://github.com/SteamClientHomebrew/Millennium/compare/v2.7.1...v2.7.2) (2024-08-03)

### Bug Fixes

-   **CI:** Fix asset processor ([bdedd20](https://github.com/SteamClientHomebrew/Millennium/commit/bdedd20abea101f09afc512c7196466b71974356))
-   Fix installer extracting ghost files ([96e238e](https://github.com/SteamClientHomebrew/Millennium/commit/96e238e86d2bc4ba35d550f40a54c8d3322f3c41))
-   Properly whitelist the default skin in the CLI ([1d8faef](https://github.com/SteamClientHomebrew/Millennium/commit/1d8faef57bde9ca8b08578e08be0f3685f719c3c))

## [2.7.2](https://github.com/SteamClientHomebrew/Millennium/compare/v2.7.1...v2.7.2) (2024-08-03)

### Bug Fixes

-   Fix installer extracting ghost files ([96e238e](https://github.com/SteamClientHomebrew/Millennium/commit/96e238e86d2bc4ba35d550f40a54c8d3322f3c41))
-   Properly whitelist the default skin in the CLI ([1d8faef](https://github.com/SteamClientHomebrew/Millennium/commit/1d8faef57bde9ca8b08578e08be0f3685f719c3c))

## [2.7.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.7.0...v2.7.1) (2024-08-03)

### Bug Fixes

-   Fix uninstaller core ([cd5c5e3](https://github.com/SteamClientHomebrew/Millennium/commit/cd5c5e3aff4efc95516442b609d3fc4cc99fbf22))
-   Only add CLI to PATH if its not already there ([9d794ce](https://github.com/SteamClientHomebrew/Millennium/commit/9d794ce1e0838cbfb67f705b9ae6f302e64bd426))

## [2.7.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.7.0...v2.7.1) (2024-08-03)

### Bug Fixes

-   Fix uninstaller core ([cd5c5e3](https://github.com/SteamClientHomebrew/Millennium/commit/cd5c5e3aff4efc95516442b609d3fc4cc99fbf22))
-   Only add CLI to PATH if its not already there ([9d794ce](https://github.com/SteamClientHomebrew/Millennium/commit/9d794ce1e0838cbfb67f705b9ae6f302e64bd426))

## [2.7.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.7.0...v2.7.1) (2024-08-03)

### Bug Fixes

-   Fix uninstaller core ([cd5c5e3](https://github.com/SteamClientHomebrew/Millennium/commit/cd5c5e3aff4efc95516442b609d3fc4cc99fbf22))
-   Only add CLI to PATH if its not already there ([9d794ce](https://github.com/SteamClientHomebrew/Millennium/commit/9d794ce1e0838cbfb67f705b9ae6f302e64bd426))

## [2.7.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.7.0...v2.7.1) (2024-08-03)

### Bug Fixes

-   Fix uninstaller core ([cd5c5e3](https://github.com/SteamClientHomebrew/Millennium/commit/cd5c5e3aff4efc95516442b609d3fc4cc99fbf22))
-   Only add CLI to PATH if its not already there ([9d794ce](https://github.com/SteamClientHomebrew/Millennium/commit/9d794ce1e0838cbfb67f705b9ae6f302e64bd426))

# [2.7.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.6.1...v2.7.0) (2024-08-02)

### Features

-   Add Millennium CLI to PATH ([05c5fa5](https://github.com/SteamClientHomebrew/Millennium/commit/05c5fa5e9746ade1b8cce9e6cbd15dbbffaceb60))

## [2.6.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.6.0...v2.6.1) (2024-08-02)

### Bug Fixes

-   Fix CI asset packer ([47cf6c6](https://github.com/SteamClientHomebrew/Millennium/commit/47cf6c66409ae94b4c00f1a29f4889c564378c71))

# [2.6.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.5.1...v2.6.0) (2024-08-02)

### Features

-   Remove LibGit2 and rely on CI assets ([5db0ebd](https://github.com/SteamClientHomebrew/Millennium/commit/5db0ebd6f571007b0fa3ea66c958a67dd93e64dd))

## [2.5.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.5.0...v2.5.1) (2024-08-02)

### Bug Fixes

-   Fix Semantic Release docs ([1f1a36c](https://github.com/SteamClientHomebrew/Millennium/commit/1f1a36ce0ab10d967269055108bcded0f0a9bb7f))
-   Install @semantic-release/changelog ([61d6356](https://github.com/SteamClientHomebrew/Millennium/commit/61d6356c29ea9fd279c069b5da86072eb4df1ec1))
-   Install @semantic-release/git ([9e483e8](https://github.com/SteamClientHomebrew/Millennium/commit/9e483e8adb4193b6db34cd9b859f46c0bc4b86d4))

# [2.5.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.4.0...v2.5.0) (2024-08-02)

### Bug Fixes

-   Add time to logger module ([80da7fb](https://github.com/SteamClientHomebrew/Millennium/commit/80da7fba4cf03b44bef70994ded5141fce659d9c))
-   Fix "object not found" error from package manager. ([bb01e9c](https://github.com/SteamClientHomebrew/Millennium/commit/bb01e9cc201e5af74170033ac935586d0054d9ec))
-   Fix plugin shutdowns to an extent ([738919c](https://github.com/SteamClientHomebrew/Millennium/commit/738919c789dab9b99df186febb910311fc264e68))
-   Fix SharedJSContext being missed on certain edge cases ([364e1c0](https://github.com/SteamClientHomebrew/Millennium/commit/364e1c087f3e1f17e842c283f1ea2bda349ec6b6))
-   Fix SharedJSContext not connecting when debugging Steam. ([1095977](https://github.com/SteamClientHomebrew/Millennium/commit/10959772484d8f255a12337c65fd54ccf75f5123))
-   Fix Steam freezing after PC sleep ([8c3dcbd](https://github.com/SteamClientHomebrew/Millennium/commit/8c3dcbd6c7d474a59fc299a975eefccd9f32f53b))
-   Revert shallow clone opts until further notice ([63da377](https://github.com/SteamClientHomebrew/Millennium/commit/63da3777ded625f110e3da8e8755c2c37f5eea2f))
-   Staging plugin hot reload ([7d1972a](https://github.com/SteamClientHomebrew/Millennium/commit/7d1972ab2ccdce3f348360b64c2af8bfb7b56032))
-   Suppress connection errors when steam isn't loaded (Linux) ([34b5e91](https://github.com/SteamClientHomebrew/Millennium/commit/34b5e91d2ffcdeec9d6762759e56602f645e8a7c))
-   Use Ninja on unix for faster build ([70d4a5d](https://github.com/SteamClientHomebrew/Millennium/commit/70d4a5df2d787ad1e0e5473781d576e3536d382c))

### Features

-   Add "useBackend" capability for plugin ([86c1943](https://github.com/SteamClientHomebrew/Millennium/commit/86c1943a9ba34e306dc6dfac3176a9ea22588690))
-   Staging CLI support ([f5cda3d](https://github.com/SteamClientHomebrew/Millennium/commit/f5cda3dde657fb8cc1ebe535ff83d27589cc5b80))
-   switch socket pipes to 1 wire ([53e6978](https://github.com/SteamClientHomebrew/Millennium/commit/53e6978abf6789bb4eb5c8a93f353710e5ca4e60))

# [2.4.0](https://github.com/SteamClientHomebrew/Millennium/compare/v2.3.1...v2.4.0) (2024-07-21)

### Bug Fixes

-   Fix libcurl & confusing logs ([c997a8c](https://github.com/SteamClientHomebrew/Millennium/commit/c997a8c549ab3f7c8cf9097e5137ee00eb8d664e))
-   Linux compatibility fixes. ([dd4c227](https://github.com/SteamClientHomebrew/Millennium/commit/dd4c227cdeee58af7b415307743fffada37511d0))
-   Properly log terminal colors in the installer ([892a7c8](https://github.com/SteamClientHomebrew/Millennium/commit/892a7c81c82df827c139352938c3a17f5750ec4e))
-   Remove confusing log ([cf19708](https://github.com/SteamClientHomebrew/Millennium/commit/cf197085e648b4244997ab60824c662d71ad9487))
-   Remove unused code ([0606641](https://github.com/SteamClientHomebrew/Millennium/commit/0606641248428d6a85dcb20838cf497eff7b9755))

### Features

-   Improved Installer ([134cce5](https://github.com/SteamClientHomebrew/Millennium/commit/134cce5fc01cfb86250e8ee5bc22342443dbe6b8))

## [2.3.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.3.0...v2.3.1) (2024-07-18)

### Features

-   Update to libgit2@1.8.0 for git_clone_options #64 ([6feced6](https://github.com/SteamClientHomebrew/Millennium/commit/6feced638ce16a4ceccf9cc5ac478355b54ee480))
-   Drastically reduce cloned repo size by @AHOHNMYC in https://github.com/SteamClientHomebrew/Millennium/pull/64

### Bug Fixes

-   de-increment version ([de72207](https://github.com/SteamClientHomebrew/Millennium/commit/de72207047dd3a02cbdb14ca4a4262aaf2ebe682))
-   Revert [#66](https://github.com/SteamClientHomebrew/Millennium/issues/66) ([07bb1d6](https://github.com/SteamClientHomebrew/Millennium/commit/07bb1d6318589aa3882ead1456dccaa0b3c9ca26))
-   Fix version number ([0581521](https://github.com/SteamClientHomebrew/Millennium/commit/05815210ffbf5d9f60c9d6108113ecbef3ca715c))
-   **installer:** More verbose prompts ([4e9af5b](https://github.com/SteamClientHomebrew/Millennium/commit/4e9af5b5653559404b1726b20fed75bb3bfcac0e))
-   revert vcpkg baseline ([a8fe40d](https://github.com/SteamClientHomebrew/Millennium/commit/a8fe40dea4e89c9dbe39a54d6162d18538cc5063))
-   **scripts:** Bug fixes for Installers ([51bc183](https://github.com/SteamClientHomebrew/Millennium/commit/51bc183b05b3622750978eb17bd7498f6ad3e553))
-   **uninstaller:** Check for corrupt installation ([f65d5eb](https://github.com/SteamClientHomebrew/Millennium/commit/f65d5eb51dfefb7e933f4e9f4c94a62f7c5a029d))

### Reverts

-   Revert "Merge pull request [#66](https://github.com/SteamClientHomebrew/Millennium/issues/66) from AHOHNMYC/update_libgit2" ([f4fa174](https://github.com/SteamClientHomebrew/Millennium/commit/f4fa17441c54ad23f7d0c61c112bd401178d3605))

## [2.2.2](https://github.com/SteamClientHomebrew/Millennium/compare/v2.2.1...v2.2.2) (2024-07-16)

### Bug Fixes

-   Optimize semantic release ([685cce3](https://github.com/SteamClientHomebrew/Millennium/commit/685cce311de6437e2e9db715172a6a1b892a054a))

## [2.2.1](https://github.com/SteamClientHomebrew/Millennium/compare/v2.2.0...v2.2.1) (2024-07-16)

### Bug Fixes

-   Fix semantic release version stubs ([7b436d7](https://github.com/SteamClientHomebrew/Millennium/commit/7b436d783c35c6637bfd045f5989822497867f96))
-   use powershell syntax 🤦 ([eb1b75b](https://github.com/SteamClientHomebrew/Millennium/commit/eb1b75b9ac5f9d0009625898ba8b8c6a930ad5c9))
