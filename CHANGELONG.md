# Changelog

## [3.4.3](https://github.com/PiShock-Inc/MultiShockSrc/compare/v3.4.2...v3.4.3) (2024-09-08)


### Bug Fixes

* actually send end commands to serial ([ec45f20](https://github.com/PiShock-Inc/MultiShockSrc/commit/ec45f20f5461972d1d73ba6956983fe334e5822e))
* add max duration to liindys shocker ([ec45f20](https://github.com/PiShock-Inc/MultiShockSrc/commit/ec45f20f5461972d1d73ba6956983fe334e5822e))
* hype train not working ([fb058c3](https://github.com/PiShock-Inc/MultiShockSrc/commit/fb058c39d48114a4e0036b00d51f17580155ade4))
* liindys controller shocks acting weird ([4ee0ab9](https://github.com/PiShock-Inc/MultiShockSrc/commit/4ee0ab9ac0e07b952ac2bc086899178725fa1049))
* linux actually find browsers ([1ded8a7](https://github.com/PiShock-Inc/MultiShockSrc/commit/1ded8a7f6c3301902349dc84568aebf7b0e1034c))
* linux app data path ([95e1707](https://github.com/PiShock-Inc/MultiShockSrc/commit/95e1707c09d334b6245c77079c62a721a248dc50))
* linux support ([a4825e4](https://github.com/PiShock-Inc/MultiShockSrc/commit/a4825e4bed9ab8801c0376845d0ccf1ba8be73a3))
* properly switch back to redis on command fail ([47803a2](https://github.com/PiShock-Inc/MultiShockSrc/commit/47803a20c95eb2ebfce96bdba4765797c18b5020))

## [3.4.2](https://github.com/PiShock-Inc/MultiShockSrc/compare/v3.4.1...v3.4.2) (2024-09-01)


### Bug Fixes

* actually add toggle for turning off websocket ([32851f5](https://github.com/PiShock-Inc/MultiShockSrc/commit/32851f5725971ee490b1d75b32b87f4e5f2e7018))
* image detection not working ([5961021](https://github.com/PiShock-Inc/MultiShockSrc/commit/596102165dddbce882a12f7b47e3a2816a9b5fb5))
* styling on settings page ([4be16b8](https://github.com/PiShock-Inc/MultiShockSrc/commit/4be16b8b499b002e808c8096500427c52819f476))

## [3.4.1](https://github.com/PiShock-Inc/MultiShockSrc/compare/v3.4.0...v3.4.1) (2024-08-31)


### Bug Fixes

* fetching shared shocker no longer hangs process ([1d0ad26](https://github.com/PiShock-Inc/MultiShockSrc/commit/1d0ad26925f40890d1aa177ac9574f64c8509cbf))

## [3.4.0](https://github.com/PiShock-Inc/MultiShockSrc/compare/v3.3.1...v3.4.0) (2024-08-31)


### Features

* add the ability to click the logo to return to front page ([d729f17](https://github.com/PiShock-Inc/MultiShockSrc/commit/d729f179757026c960ca5eda59db81af7bcd7b62))
* auto save setting on exit of main settings page ([5c8ef96](https://github.com/PiShock-Inc/MultiShockSrc/commit/5c8ef96b8294273a58dedd5906426c67abdb9a6e))
* sharecodes support ([d729f17](https://github.com/PiShock-Inc/MultiShockSrc/commit/d729f179757026c960ca5eda59db81af7bcd7b62))
* shared shocker support (BETA) ([5c8ef96](https://github.com/PiShock-Inc/MultiShockSrc/commit/5c8ef96b8294273a58dedd5906426c67abdb9a6e))
* specific shockers for image detection ([5c8ef96](https://github.com/PiShock-Inc/MultiShockSrc/commit/5c8ef96b8294273a58dedd5906426c67abdb9a6e))
* style updates ([d729f17](https://github.com/PiShock-Inc/MultiShockSrc/commit/d729f179757026c960ca5eda59db81af7bcd7b62))


### Bug Fixes

* dont reload shockers when saving image detection settings ([5c8ef96](https://github.com/PiShock-Inc/MultiShockSrc/commit/5c8ef96b8294273a58dedd5906426c67abdb9a6e))
* osc addon not reciving messages from vrchat ([5c8ef96](https://github.com/PiShock-Inc/MultiShockSrc/commit/5c8ef96b8294273a58dedd5906426c67abdb9a6e))

## [3.3.1](https://github.com/PiShock-Inc/MultiShockSrc/compare/v3.3.0...v3.3.1) (2024-08-17)


### Bug Fixes

* twitch not working ([21f071b](https://github.com/PiShock-Inc/MultiShockSrc/commit/21f071b493478b896ed70acb2b4c4ffe8f2dce70))

## [3.3.0](https://github.com/PiShock-Inc/MultiShockSrc/compare/v3.2.0...v3.3.0) (2024-08-16)


### Features

* add external websocket control support ([01c1fe6](https://github.com/PiShock-Inc/MultiShockSrc/commit/01c1fe65cd16edbd8ee6c4d079fb1ab854b1c0d7))
* add options for warning and held to websocket operations ([d96aedb](https://github.com/PiShock-Inc/MultiShockSrc/commit/d96aedba60decdf0e5aee7baa721f429b4d40607))
* add OSC listener ([1ee7840](https://github.com/PiShock-Inc/MultiShockSrc/commit/1ee7840da7a37bf61bfda44108ad4427fc841a4e))
* add zeroconf server for websocket server port ([bf44409](https://github.com/PiShock-Inc/MultiShockSrc/commit/bf444095f884e91eff33c9c1a6eaf446d473b246))
* implement osc controls for liindys controller ([42b5fc8](https://github.com/PiShock-Inc/MultiShockSrc/commit/42b5fc8080dc8303e41866e5f4d39b92c657c539))
* implement serial connections ([01c1fe6](https://github.com/PiShock-Inc/MultiShockSrc/commit/01c1fe65cd16edbd8ee6c4d079fb1ab854b1c0d7))
* UI now shows whats being started during startup instead of just being unresponsive ([6975d22](https://github.com/PiShock-Inc/MultiShockSrc/commit/6975d22f094b5b272784a73eaf7f262755e54613))


### Bug Fixes

* add warning about twitch moderation ([b75a9c9](https://github.com/PiShock-Inc/MultiShockSrc/commit/b75a9c910950c2d20f288e70e76ba8af813f8061))
* auth key not saving ([7ceb41f](https://github.com/PiShock-Inc/MultiShockSrc/commit/7ceb41fc4fa03c041849371c78442e7cf6c9b269))
* bool values not always working ([403dffe](https://github.com/PiShock-Inc/MultiShockSrc/commit/403dffe996282055a6f1d004f7f51efd5f74b5e3))
* error for invalid image/key/value whatever ([ed94e7c](https://github.com/PiShock-Inc/MultiShockSrc/commit/ed94e7c1b802450d2754a5542e517722fc41a6ab))
* if follower listener is not used dont fetch followers on startup ([6975d22](https://github.com/PiShock-Inc/MultiShockSrc/commit/6975d22f094b5b272784a73eaf7f262755e54613))
* implement usage of new login page ([6975d22](https://github.com/PiShock-Inc/MultiShockSrc/commit/6975d22f094b5b272784a73eaf7f262755e54613))
* make internal addons more secure? ([0f53447](https://github.com/PiShock-Inc/MultiShockSrc/commit/0f534472384b67d814dae08d3c412a7c4f93ec9d))
* serial not being chosen when shockers are reloaded ([337292e](https://github.com/PiShock-Inc/MultiShockSrc/commit/337292ef47e94a4486f10d1b2e096d47f5a47d94))

## [3.2.0](https://github.com/PiShock-Inc/MultiShockSrc/compare/v3.1.0...v3.2.0) (2024-07-26)


### Features

* Implement logging to help find errors ([d35de2b](https://github.com/PiShock-Inc/MultiShockSrc/commit/d35de2bb633c37786624d1d43233041dbe089552))
* Properly kill old running processes on startup ([d35de2b](https://github.com/PiShock-Inc/MultiShockSrc/commit/d35de2bb633c37786624d1d43233041dbe089552))


### Bug Fixes

* actually set a minimum for intensity's and durations ([d7cb184](https://github.com/PiShock-Inc/MultiShockSrc/commit/d7cb184a456edd9b98b40c5e2907babc73363776))
* Add handling for resubs ([d35de2b](https://github.com/PiShock-Inc/MultiShockSrc/commit/d35de2bb633c37786624d1d43233041dbe089552))
* fix twitch addon ([376e4a0](https://github.com/PiShock-Inc/MultiShockSrc/commit/376e4a099da4af74a02860d5cbd63087740dc33b))
* If backend is killed, kill UI ([038715b](https://github.com/PiShock-Inc/MultiShockSrc/commit/038715bec4731236fabcade3838973bf2599eda5))
* Properly kill old processes on startup ([038715b](https://github.com/PiShock-Inc/MultiShockSrc/commit/038715bec4731236fabcade3838973bf2599eda5))
* properly kill twitch processes ([d7cb184](https://github.com/PiShock-Inc/MultiShockSrc/commit/d7cb184a456edd9b98b40c5e2907babc73363776))
* resubs no longer cause errors ([f496b71](https://github.com/PiShock-Inc/MultiShockSrc/commit/f496b716882c6abf29ea4bd42c233cdb1c2effa9))
* sending twitch messages no longer kills the process ([d7cb184](https://github.com/PiShock-Inc/MultiShockSrc/commit/d7cb184a456edd9b98b40c5e2907babc73363776))

## [3.1.0](https://github.com/PiShock-Inc/MultiShockSrc/compare/v3.1.0...v3.1.0) (2024-06-29)


### Features

* add ability to clear ququed shocker actions ([17685cf](https://github.com/PiShock-Inc/MultiShockSrc/commit/17685cf212b9e4381c90c065237185b2a80892a7))
* Add cheer and bits page ([a9fb725](https://github.com/PiShock-Inc/MultiShockSrc/commit/a9fb725cf36a6e6670a4e3052183ab5f590e54f2))
* Add debug option ([2291207](https://github.com/PiShock-Inc/MultiShockSrc/commit/2291207f5283dd863f6e857c2bbf13956e5d90cd))
* add follow messages ([17685cf](https://github.com/PiShock-Inc/MultiShockSrc/commit/17685cf212b9e4381c90c065237185b2a80892a7))
* Add number inputs for each slider ([80e80d8](https://github.com/PiShock-Inc/MultiShockSrc/commit/80e80d898d6faf0b21f02687399fcb6638075221))
* added queueing to actions ([d9df898](https://github.com/PiShock-Inc/MultiShockSrc/commit/d9df898377a7acaca25522c2bc97b2b2370db210))
* adds configurable messages for cheers, redeems, subs, gifted subs, and timed message ([d9df898](https://github.com/PiShock-Inc/MultiShockSrc/commit/d9df898377a7acaca25522c2bc97b2b2370db210))
* Adds frontend pages for new stream modules ([9dfe8ce](https://github.com/PiShock-Inc/MultiShockSrc/commit/9dfe8ce4beedeb75724a5f0cdbdca4a23e88b664))
* adds streamloots card listener ([d9df898](https://github.com/PiShock-Inc/MultiShockSrc/commit/d9df898377a7acaca25522c2bc97b2b2370db210))
* adds streamloots card listener ([22da68a](https://github.com/PiShock-Inc/MultiShockSrc/commit/22da68a6681ebae77102a26b862a27043f207f16))
* adds subscriptions and subscription gifts to twitch chandler ([20752e5](https://github.com/PiShock-Inc/MultiShockSrc/commit/20752e5fb2af3c43474a758a26a892ae29e7ee16))
* adds twitch cheer page ([258e1b0](https://github.com/PiShock-Inc/MultiShockSrc/commit/258e1b0dd7c7d4ef3b35a1737a22b7b7d7fae410))
* allow enabling and disable cheer sections ([f99d2e0](https://github.com/PiShock-Inc/MultiShockSrc/commit/f99d2e097e36c78e15e77e9e0c5c5a306750998c))
* update configs to be less dumb when saving and loading ([17685cf](https://github.com/PiShock-Inc/MultiShockSrc/commit/17685cf212b9e4381c90c065237185b2a80892a7))


### Bug Fixes

* Add missing devices to config when fetching from api ([338a8ff](https://github.com/PiShock-Inc/MultiShockSrc/commit/338a8fff4e7e4ae947c5ebf7de12fee5bc86ef4e))
* add more error handling for people with bad connection ([6918b70](https://github.com/PiShock-Inc/MultiShockSrc/commit/6918b705cf092a487c958058db449c23e8d39766))
* Brackets are now properly chosen ([80e80d8](https://github.com/PiShock-Inc/MultiShockSrc/commit/80e80d898d6faf0b21f02687399fcb6638075221))
* disabled shockers still being chosen for random and round-robin modes ([7b94370](https://github.com/PiShock-Inc/MultiShockSrc/commit/7b94370649db90543b95f39f28d6cd2164029124))
* fix can shock toggle to actually function ([063e9ce](https://github.com/PiShock-Inc/MultiShockSrc/commit/063e9ce9a686505676a1f1d413c0118b2ac33a73))
* fix cheers, follows, redeems, etc ([ef8af3b](https://github.com/PiShock-Inc/MultiShockSrc/commit/ef8af3b9f7dbe1ccea3f04a95c7b5e8b9ca2716e))
* fix streamloots module username ([7efcb75](https://github.com/PiShock-Inc/MultiShockSrc/commit/7efcb752672e011bcb6fb2999659c0a342915242))
* fixes error when first ever launch of app ([d57d6c7](https://github.com/PiShock-Inc/MultiShockSrc/commit/d57d6c7589b7e0398df8335e19fa6696e4a05978))
* Fixes follows not working ([2291207](https://github.com/PiShock-Inc/MultiShockSrc/commit/2291207f5283dd863f6e857c2bbf13956e5d90cd))
* Improve how multiple shockers show up in settings ([317b1a0](https://github.com/PiShock-Inc/MultiShockSrc/commit/317b1a0f727a62ffdacce9ba9e3bc601a0fa27c8))
* login() is no longer called when certain pages are opened ([17685cf](https://github.com/PiShock-Inc/MultiShockSrc/commit/17685cf212b9e4381c90c065237185b2a80892a7))
* make request timeout longer ([39d4e9f](https://github.com/PiShock-Inc/MultiShockSrc/commit/39d4e9f625972379a24e7094307ab85e45e1eb08))
* multiple shockers *should* now work ([2291207](https://github.com/PiShock-Inc/MultiShockSrc/commit/2291207f5283dd863f6e857c2bbf13956e5d90cd))
* new modules no longer fail to set creator name and description ([feb9331](https://github.com/PiShock-Inc/MultiShockSrc/commit/feb9331ff4ed554245e5773b2ad5d08939019ef6))
* no longer load disabled shockers ([063e9ce](https://github.com/PiShock-Inc/MultiShockSrc/commit/063e9ce9a686505676a1f1d413c0118b2ac33a73))
* No more error on startup when twitch token in empty ([7d4bef0](https://github.com/PiShock-Inc/MultiShockSrc/commit/7d4bef0c87447a1d45e76cc93c7c12b4a7e9665b))
* Optimized twitch process and removed need to input twitch username ([858d049](https://github.com/PiShock-Inc/MultiShockSrc/commit/858d0497d6f791f4465ef4d9ab19536574034c50))
* Saving config no longer sets use v3 to false ([7d4bef0](https://github.com/PiShock-Inc/MultiShockSrc/commit/7d4bef0c87447a1d45e76cc93c7c12b4a7e9665b))
* Saving no longer nukes loaded ([9dfe8ce](https://github.com/PiShock-Inc/MultiShockSrc/commit/9dfe8ce4beedeb75724a5f0cdbdca4a23e88b664))
* show try to kill old processes when starting a new one? ([2291207](https://github.com/PiShock-Inc/MultiShockSrc/commit/2291207f5283dd863f6e857c2bbf13956e5d90cd))
* update checker checks new repo ([f5bd1d9](https://github.com/PiShock-Inc/MultiShockSrc/commit/f5bd1d9a6fad75fe59046c4353bf0b3b8111b743))


### Miscellaneous Chores

* release 3.0.4 ([3ef5320](https://github.com/PiShock-Inc/MultiShockSrc/commit/3ef5320a63ec4f56952f91e8c4fd8099786e4a8d))
* release 3.1.0 ([d337de8](https://github.com/PiShock-Inc/MultiShockSrc/commit/d337de83741f317500c81990b2435a2ce0c2f081))

## [3.1.0](https://github.com/PiShock-Inc/MultiShockSrc/compare/v3.0.5...v3.1.0) (2024-06-29)


### Features

* add ability to clear ququed shocker actions ([17685cf](https://github.com/PiShock-Inc/MultiShockSrc/commit/17685cf212b9e4381c90c065237185b2a80892a7))
* Add debug option ([2291207](https://github.com/PiShock-Inc/MultiShockSrc/commit/2291207f5283dd863f6e857c2bbf13956e5d90cd))
* add follow messages ([17685cf](https://github.com/PiShock-Inc/MultiShockSrc/commit/17685cf212b9e4381c90c065237185b2a80892a7))
* Add number inputs for each slider ([80e80d8](https://github.com/PiShock-Inc/MultiShockSrc/commit/80e80d898d6faf0b21f02687399fcb6638075221))
* added queueing to actions ([d9df898](https://github.com/PiShock-Inc/MultiShockSrc/commit/d9df898377a7acaca25522c2bc97b2b2370db210))
* adds configurable messages for cheers, redeems, subs, gifted subs, and timed message ([d9df898](https://github.com/PiShock-Inc/MultiShockSrc/commit/d9df898377a7acaca25522c2bc97b2b2370db210))
* Adds frontend pages for new stream modules ([9dfe8ce](https://github.com/PiShock-Inc/MultiShockSrc/commit/9dfe8ce4beedeb75724a5f0cdbdca4a23e88b664))
* adds streamloots card listener ([d9df898](https://github.com/PiShock-Inc/MultiShockSrc/commit/d9df898377a7acaca25522c2bc97b2b2370db210))
* adds streamloots card listener ([22da68a](https://github.com/PiShock-Inc/MultiShockSrc/commit/22da68a6681ebae77102a26b862a27043f207f16))
* adds subscriptions and subscription gifts to twitch chandler ([20752e5](https://github.com/PiShock-Inc/MultiShockSrc/commit/20752e5fb2af3c43474a758a26a892ae29e7ee16))
* adds twitch cheer page ([258e1b0](https://github.com/PiShock-Inc/MultiShockSrc/commit/258e1b0dd7c7d4ef3b35a1737a22b7b7d7fae410))
* allow enabling and disable cheer sections ([f99d2e0](https://github.com/PiShock-Inc/MultiShockSrc/commit/f99d2e097e36c78e15e77e9e0c5c5a306750998c))
* update configs to be less dumb when saving and loading ([17685cf](https://github.com/PiShock-Inc/MultiShockSrc/commit/17685cf212b9e4381c90c065237185b2a80892a7))


### Bug Fixes

* add more error handling for people with bad connection ([6918b70](https://github.com/PiShock-Inc/MultiShockSrc/commit/6918b705cf092a487c958058db449c23e8d39766))
* Brackets are now properly chosen ([80e80d8](https://github.com/PiShock-Inc/MultiShockSrc/commit/80e80d898d6faf0b21f02687399fcb6638075221))
* disabled shockers still being chosen for random and round-robin modes ([7b94370](https://github.com/PiShock-Inc/MultiShockSrc/commit/7b94370649db90543b95f39f28d6cd2164029124))
* fix can shock toggle to actually function ([063e9ce](https://github.com/PiShock-Inc/MultiShockSrc/commit/063e9ce9a686505676a1f1d413c0118b2ac33a73))
* fix cheers, follows, redeems, etc ([ef8af3b](https://github.com/PiShock-Inc/MultiShockSrc/commit/ef8af3b9f7dbe1ccea3f04a95c7b5e8b9ca2716e))
* fix streamloots module username ([7efcb75](https://github.com/PiShock-Inc/MultiShockSrc/commit/7efcb752672e011bcb6fb2999659c0a342915242))
* fixes error when first ever launch of app ([d57d6c7](https://github.com/PiShock-Inc/MultiShockSrc/commit/d57d6c7589b7e0398df8335e19fa6696e4a05978))
* Fixes follows not working ([2291207](https://github.com/PiShock-Inc/MultiShockSrc/commit/2291207f5283dd863f6e857c2bbf13956e5d90cd))
* Improve how multiple shockers show up in settings ([317b1a0](https://github.com/PiShock-Inc/MultiShockSrc/commit/317b1a0f727a62ffdacce9ba9e3bc601a0fa27c8))
* login() is no longer called when certain pages are opened ([17685cf](https://github.com/PiShock-Inc/MultiShockSrc/commit/17685cf212b9e4381c90c065237185b2a80892a7))
* multiple shockers *should* now work ([2291207](https://github.com/PiShock-Inc/MultiShockSrc/commit/2291207f5283dd863f6e857c2bbf13956e5d90cd))
* new modules no longer fail to set creator name and description ([feb9331](https://github.com/PiShock-Inc/MultiShockSrc/commit/feb9331ff4ed554245e5773b2ad5d08939019ef6))
* no longer load disabled shockers ([063e9ce](https://github.com/PiShock-Inc/MultiShockSrc/commit/063e9ce9a686505676a1f1d413c0118b2ac33a73))
* No more error on startup when twitch token in empty ([7d4bef0](https://github.com/PiShock-Inc/MultiShockSrc/commit/7d4bef0c87447a1d45e76cc93c7c12b4a7e9665b))
* Optimized twitch process and removed need to input twitch username ([858d049](https://github.com/PiShock-Inc/MultiShockSrc/commit/858d0497d6f791f4465ef4d9ab19536574034c50))
* Saving config no longer sets use v3 to false ([7d4bef0](https://github.com/PiShock-Inc/MultiShockSrc/commit/7d4bef0c87447a1d45e76cc93c7c12b4a7e9665b))
* Saving no longer nukes loaded ([9dfe8ce](https://github.com/PiShock-Inc/MultiShockSrc/commit/9dfe8ce4beedeb75724a5f0cdbdca4a23e88b664))
* show try to kill old processes when starting a new one? ([2291207](https://github.com/PiShock-Inc/MultiShockSrc/commit/2291207f5283dd863f6e857c2bbf13956e5d90cd))

## [3.0.5](https://github.com/PiShock-Inc/MultiShockSrc/compare/v3.0.4...v3.0.5) (2024-05-19)


### Bug Fixes

* Add missing devices to config when fetching from api ([338a8ff](https://github.com/PiShock-Inc/MultiShockSrc/commit/338a8fff4e7e4ae947c5ebf7de12fee5bc86ef4e))

## [3.0.4](https://github.com/PiShock-Inc/MultiShockSrc/compare/v3.0.3...v3.0.4) (2024-05-16)


### Bug Fixes

* make request timeout longer ([39d4e9f](https://github.com/PiShock-Inc/MultiShockSrc/commit/39d4e9f625972379a24e7094307ab85e45e1eb08))
* update checker checks new repo ([f5bd1d9](https://github.com/PiShock-Inc/MultiShockSrc/commit/f5bd1d9a6fad75fe59046c4353bf0b3b8111b743))


### Miscellaneous Chores

* release 3.0.4 ([3ef5320](https://github.com/PiShock-Inc/MultiShockSrc/commit/3ef5320a63ec4f56952f91e8c4fd8099786e4a8d))
