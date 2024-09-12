# Changelog

## [1.5.0](https://github.com/AkazaRenn/ublue-update/compare/v1.4.0...v1.5.0) (2024-09-12)


### Features

* Add --config argument for specifying a configuration file ([6e69105](https://github.com/AkazaRenn/ublue-update/commit/6e69105faa296b566d8a83b08bbda978bf06220f))
* Add a new 'network_is_metered' check ([06faa9b](https://github.com/AkazaRenn/ublue-update/commit/06faa9b775000b64203d9db45e61b87c31fb5216))
* add filelocking to make updates not run at the same time for same user ([28a6e9a](https://github.com/AkazaRenn/ublue-update/commit/28a6e9a9e1339967e0d785436a7002d2d8d58b9d))
* add log for when update is complete ([f3992f3](https://github.com/AkazaRenn/ublue-update/commit/f3992f39c5fae0db82e43e4192af67c7e9a7efce))
* Add module that waits for transaction completion before updating ([0abd5dc](https://github.com/AkazaRenn/ublue-update/commit/0abd5dccf0a805daed435ad791bfc94afd10a91c))
* Add module that waits for transaction completion before updating ([#55](https://github.com/AkazaRenn/ublue-update/issues/55)) ([d8d038b](https://github.com/AkazaRenn/ublue-update/commit/d8d038bb945a34b8c4fd562ba14c696355ea4ff4))
* add pidlock, only run updates for active sessions ([5b9702a](https://github.com/AkazaRenn/ublue-update/commit/5b9702a5966322715fe2eb4c6197e16884f16e0d))
* add proof-of-concept containerfile for this project ([aeeb3c0](https://github.com/AkazaRenn/ublue-update/commit/aeeb3c08e459488b7dbd4a9737a3fa25f7f3a92a))
* add RPM build and restructure to make it work ([9642188](https://github.com/AkazaRenn/ublue-update/commit/9642188e94a1d0c147b9b78efa37fba324eb23a3))
* Add script-based custom checks in addition to the predefined checks ([2079eb5](https://github.com/AkazaRenn/ublue-update/commit/2079eb51afdd10ef5e60c6f464b6d2368faff43c))
* Add support for updating with Fleek ([bcc731c](https://github.com/AkazaRenn/ublue-update/commit/bcc731cf609372ec54e5b5a0f692d8f895b01f0a))
* Add support for updating with Fleek ([#53](https://github.com/AkazaRenn/ublue-update/issues/53)) ([6bd7568](https://github.com/AkazaRenn/ublue-update/commit/6bd75682077d45f2cbf1b8c6a61c95a77cab5c43))
* Add the option to specify external script files in addition to inline scripts ([91e481d](https://github.com/AkazaRenn/ublue-update/commit/91e481d489d341ea01bdb8a30f31d276886373ec))
* Add topgrade support ([8a926c5](https://github.com/AkazaRenn/ublue-update/commit/8a926c5755d10aefc23480bc506b3936c2a7c58a))
* Add topgrade support ([#102](https://github.com/AkazaRenn/ublue-update/issues/102)) ([61dd86c](https://github.com/AkazaRenn/ublue-update/commit/61dd86c698e30c852c2cbd401bf407f9449553d8))
* Add unit tests ([6aa9307](https://github.com/AkazaRenn/ublue-update/commit/6aa93071b05c1127fd929a85d9f0099901e72d3c))
* Add updater for brew ([#76](https://github.com/AkazaRenn/ublue-update/issues/76)) ([63d40a1](https://github.com/AkazaRenn/ublue-update/commit/63d40a1688b52d4dcbcf37797ff14a355025c7fc))
* added --check option to run through update checks and exit ([ac0523b](https://github.com/AkazaRenn/ublue-update/commit/ac0523bea189c3216bdb45962d847a41169cdca1))
* added --user and --system flags ([697a986](https://github.com/AkazaRenn/ublue-update/commit/697a986001796c23ae573824e51ad6d7ea4f6b0e))
* added custom notification_manager to replace notify2 ([4b25c7c](https://github.com/AkazaRenn/ublue-update/commit/4b25c7c97a5f1f44a5d32e6df3a000e44cb02cfd))
* added NotificationObject, holds all notification data and makes it easier to deal with actions ([f67e3c9](https://github.com/AkazaRenn/ublue-update/commit/f67e3c905ae1ff19b988787cba6023cf410946ac))
* auto sign images ([#73](https://github.com/AkazaRenn/ublue-update/issues/73)) ([6acce45](https://github.com/AkazaRenn/ublue-update/commit/6acce45767dfd05e82c722c771b65400ce97cc82))
* **ci:** Split build for Fedora 38 and 39 ([#67](https://github.com/AkazaRenn/ublue-update/issues/67)) ([bd27a84](https://github.com/AkazaRenn/ublue-update/commit/bd27a84414aa917dbf4940defa062d9886164972))
* Implement system update check module and notification ([39f998b](https://github.com/AkazaRenn/ublue-update/commit/39f998bc38ebfabe83d71427d47d62cefc0fe77a))
* initial work for running system updates as root, and updates for each user ([8d683ad](https://github.com/AkazaRenn/ublue-update/commit/8d683add501d59bb63751ad201d7656fcfb609aa))
* made config loading more robust ([722c956](https://github.com/AkazaRenn/ublue-update/commit/722c956392235d268eacee803d1ccd00f930ab85))
* made updater service restart on failure ([5817e31](https://github.com/AkazaRenn/ublue-update/commit/5817e31d7355303f4c271d548e17bfd5640ada3e))
* move system update script to python ([#81](https://github.com/AkazaRenn/ublue-update/issues/81)) ([be229d1](https://github.com/AkazaRenn/ublue-update/commit/be229d1ee60dd7a5f7f5d0f118634bfa31918a88))
* moved all dbus and glib logic into notification_manager ([d69ac11](https://github.com/AkazaRenn/ublue-update/commit/d69ac116351ce09a3839ea245f95998a3faa1e89))
* moved config format to toml, cleaned up config logic to default to /usr/etc ([2c47f12](https://github.com/AkazaRenn/ublue-update/commit/2c47f12d942b9b2c79c277369c9f015af67fd15d))
* reformat ([6d605f2](https://github.com/AkazaRenn/ublue-update/commit/6d605f21e2a5b92fbb0a2037c5b2f94be54cf98c))
* remove notification manager, add notification icon ([72e1dec](https://github.com/AkazaRenn/ublue-update/commit/72e1decd9bd4916fa0a9d7c4dc46272af7cb27f8))
* Remove rebase step now that ISOs are nearly ready ([#105](https://github.com/AkazaRenn/ublue-update/issues/105)) ([1e670f0](https://github.com/AkazaRenn/ublue-update/commit/1e670f0044026b434da746bb28fa05a21fade00e))
* Remove rebase step now that ISOs are nearly ready, move topgrade configs to /usr/share, cleanup. ([8307b17](https://github.com/AkazaRenn/ublue-update/commit/8307b17a3c280431ffce863b7b98e74d31766cdb))
* removed dependency on notify2 ([dc3325e](https://github.com/AkazaRenn/ublue-update/commit/dc3325e45aaafad6c9afe174b16971d66aef347a))
* run system updates as root, run user updates for each user ([#62](https://github.com/AkazaRenn/ublue-update/issues/62)) ([f67b894](https://github.com/AkazaRenn/ublue-update/commit/f67b89414a613e2517efe8e4a99518af029cf086))
* **system-update:** Allow switching between branches via rebase ([e14f166](https://github.com/AkazaRenn/ublue-update/commit/e14f1665402a4e01a1778833c27568a07d48acfb))
* **system-update:** Allow switching between branches via rebase ([#91](https://github.com/AkazaRenn/ublue-update/issues/91)) ([e013061](https://github.com/AkazaRenn/ublue-update/commit/e013061013c97d5cf49d14237fdfe6b12ace8afe))
* systemd timing/service tweaks ([e1dd217](https://github.com/AkazaRenn/ublue-update/commit/e1dd2172d438f728ef0ef03f3b1110902ac203f2))
* **systemd:** timing changes ([652a29c](https://github.com/AkazaRenn/ublue-update/commit/652a29c0f893243051d61057d7b4ecac092f2252))
* use systemd-run, fix topgrade ([#130](https://github.com/AkazaRenn/ublue-update/issues/130)) ([e13e6ce](https://github.com/AkazaRenn/ublue-update/commit/e13e6ce36601f79bcad3ab3259b549197f5ef97a))


### Bug Fixes

* account for ostree-unverified-registry shorthand ([8271032](https://github.com/AkazaRenn/ublue-update/commit/8271032feed7b907d50520dfbc45afbc47d1cd6a))
* add brew to user and distrobox to system ([2e0e582](https://github.com/AkazaRenn/ublue-update/commit/2e0e582e125359108a910b5225f4daeb2e64a9bc))
* add brew to user and distrobox to system ([#107](https://github.com/AkazaRenn/ublue-update/issues/107)) ([d8fb315](https://github.com/AkazaRenn/ublue-update/commit/d8fb3157fac1f8c5836beae8ea97097c50403051))
* add documentation to clean target ([308c17c](https://github.com/AkazaRenn/ublue-update/commit/308c17cd537d02796c01b0721bb2bd2af36c5414))
* add documentation to clean target ([#34](https://github.com/AkazaRenn/ublue-update/issues/34)) ([14ad321](https://github.com/AkazaRenn/ublue-update/commit/14ad321cdaf35dcb5609b9199110aa7fd6b52beb))
* add extra spacing to please code formatter ([99fa0a3](https://github.com/AkazaRenn/ublue-update/commit/99fa0a370894001860b9333d1390985f93523fee))
* add proper error handling ([6c167d0](https://github.com/AkazaRenn/ublue-update/commit/6c167d0a787c8abf581dead09bae04123280c318))
* add root requirement for running updates ([0b54496](https://github.com/AkazaRenn/ublue-update/commit/0b544961438c4db3acbbe1ac2bb6cf7402024be7))
* Add try except to log error for clearer reason for failure ([#118](https://github.com/AkazaRenn/ublue-update/issues/118)) ([49a9f74](https://github.com/AkazaRenn/ublue-update/commit/49a9f7454d765437cdb9a8289ecd04ee074aba36))
* added { to please formatter ([7fae539](https://github.com/AkazaRenn/ublue-update/commit/7fae539ae8e880651417f816bb664ef7d8424662))
* added back Containerfile.builder to fix build action ([abf152e](https://github.com/AkazaRenn/ublue-update/commit/abf152ee44a36dbd5bbdb233fbd01c271c1abb3c))
* added import for DBusGMainLoop ([476c872](https://github.com/AkazaRenn/ublue-update/commit/476c872c58783487b9a045f1d2718590e7660543))
* added sudo as a dependency ([ac6cf00](https://github.com/AkazaRenn/ublue-update/commit/ac6cf0027fee90688d50dc67bd1dfda13216e6b3))
* Adjust update service and timer ([2dc0ccc](https://github.com/AkazaRenn/ublue-update/commit/2dc0ccc80cdaa850c7acd2729e883118e2212ad5))
* Also accept lowercase log levels for UBLUE_LOG ([c4db9bc](https://github.com/AkazaRenn/ublue-update/commit/c4db9bcb4f503fd11d3c66e20317b3cdf34d972c))
* apply some small python cleanups ([69e42d0](https://github.com/AkazaRenn/ublue-update/commit/69e42d0c74a2d5f0a78881ca1fd9494bad39c919))
* Avoid crashing on incomplete fallback config ([ba2c04d](https://github.com/AkazaRenn/ublue-update/commit/ba2c04d0bd7a3c2ea844922317c5b423989b9894))
* be more carefull when to rebase ([2ba442f](https://github.com/AkazaRenn/ublue-update/commit/2ba442f4be39dccf663dc1ae0c6696d6e738ca78))
* be more carefull when to rebase ([#88](https://github.com/AkazaRenn/ublue-update/issues/88)) ([427912c](https://github.com/AkazaRenn/ublue-update/commit/427912c53db77dab15f6e80c85f5d7a6118925b2))
* build rpm in release workflow ([#38](https://github.com/AkazaRenn/ublue-update/issues/38)) ([c1517cc](https://github.com/AkazaRenn/ublue-update/commit/c1517ccd183fb0f67380ba4d8af68f1b358240ac))
* bump version ([32ccf70](https://github.com/AkazaRenn/ublue-update/commit/32ccf7082ed5228d2f55968eadf2469e4e1ef7f7))
* bypass distrobox upgrade sudo checks ([#69](https://github.com/AkazaRenn/ublue-update/issues/69)) ([127ed90](https://github.com/AkazaRenn/ublue-update/commit/127ed90804f2b56ba0191a7255edc9ff02a0754e))
* change default max_mem_percent to 90.0 ([35a1c4f](https://github.com/AkazaRenn/ublue-update/commit/35a1c4f8a37c3661e2df268370ed51802fd4370c))
* change default max_mem_percent to 90.0 ([6119d3b](https://github.com/AkazaRenn/ublue-update/commit/6119d3b162ee72a28698ff501f7c7b6ead9c3594))
* change environment variables when running ublue-update as user ([5d77d74](https://github.com/AkazaRenn/ublue-update/commit/5d77d74ea05cc79e01452bc4d8dd514cd5e24198))
* change runner to 24.04 ([1635cca](https://github.com/AkazaRenn/ublue-update/commit/1635cca16b5e7a6e0b6b89beebe373ffeb1baaff))
* Check if the url already contains the protocol during update checks ([829af56](https://github.com/AkazaRenn/ublue-update/commit/829af5643a599789be1b86e3ec45cbb00b8aa3f0))
* Check if the url already contains the protocol during update checks ([#44](https://github.com/AkazaRenn/ublue-update/issues/44)) ([66ac29c](https://github.com/AkazaRenn/ublue-update/commit/66ac29c2c455b47ba3ee110c3716cad635d02e97))
* **ci:** intall topgrade before building ([f4acbf1](https://github.com/AkazaRenn/ublue-update/commit/f4acbf109e74d2fbba7cc13b7c446b061fb895bd))
* **ci:** update README deps and build.yml ([bdc968d](https://github.com/AkazaRenn/ublue-update/commit/bdc968d8bbabb66e498c3403d05a591c952fe071))
* **ci:** update README deps and build.yml ([#117](https://github.com/AkazaRenn/ublue-update/issues/117)) ([42676dc](https://github.com/AkazaRenn/ublue-update/commit/42676dc8f0f9c4b3040b05a9356c9f27cf014329))
* Clarify Comment for pending Deployment ([057ecbb](https://github.com/AkazaRenn/ublue-update/commit/057ecbb9e076a9b32b3e88ee9c066c9586c4f43f))
* **cli:** Remove residual semicolon from testing ([83b39d7](https://github.com/AkazaRenn/ublue-update/commit/83b39d707ce6c382883cc835fe11a692fe9c1e44))
* **config:** fix breakage when using fallback config, improved config logic to be more flexible ([f167dc9](https://github.com/AkazaRenn/ublue-update/commit/f167dc970d7b38e4ecf6d85895e800ce16760063))
* don't run sudo for each script, fixed string formatting ([5a28f1f](https://github.com/AkazaRenn/ublue-update/commit/5a28f1fbd26faa352979d7a74cd322c1894ef596))
* fedora version 40, remove rpm file extractor ([e328071](https://github.com/AkazaRenn/ublue-update/commit/e328071e117ad73dc3874ee1b689ecfea294611a))
* Fix Builder Containerfile ([d13b40a](https://github.com/AkazaRenn/ublue-update/commit/d13b40ad88d504dbb9d03ee4ee26cfddd0b0912e))
* fix program exiting telling user checks have failed when running from notification ([7b24b8c](https://github.com/AkazaRenn/ublue-update/commit/7b24b8cb4b31a2406c55cc88e60a9a90bda1b173))
* fix program exiting telling user checks have failed when running from notification ([#43](https://github.com/AkazaRenn/ublue-update/issues/43)) ([2b42c62](https://github.com/AkazaRenn/ublue-update/commit/2b42c628660f3fa5999d8eb1542c919b9c44a087))
* fix python errors ([451e33c](https://github.com/AkazaRenn/ublue-update/commit/451e33c9d9b5df9c1043d6239a7fc637a2e6d278))
* fix updater throwing exception when dbus is inactive ([ee226b7](https://github.com/AkazaRenn/ublue-update/commit/ee226b7cfd164ec71487ea73b476eb8213775fb4))
* fixed and simplified argument behavior, use better naming ([3068671](https://github.com/AkazaRenn/ublue-update/commit/30686717c4e8ad5c4b369694d8f147718efa6656))
* fixed issues that prevented script from running, removed commented out code ([22b83c8](https://github.com/AkazaRenn/ublue-update/commit/22b83c850bf8dcb5dbba008f209a3f7705dc7579))
* fixed line length and corrected variable reference ([864e2ea](https://github.com/AkazaRenn/ublue-update/commit/864e2ea14872ca7c3d5b2f7b4d5848553425547f))
* fixed user prompts when running as root ([b40ed7a](https://github.com/AkazaRenn/ublue-update/commit/b40ed7a5101576d180f9e88334f23ead0e9222e2))
* **flake8:** Ignore W503 and W504 ([5111b06](https://github.com/AkazaRenn/ublue-update/commit/5111b0643b146712117de9cae015f79296ee1646))
* format to please flake8 ([3287b64](https://github.com/AkazaRenn/ublue-update/commit/3287b6441d6a388151bbf8113149f92aa8c9747c))
* formatted code, used f-strings for cmd args ([a5ce221](https://github.com/AkazaRenn/ublue-update/commit/a5ce2217122e607c2df3aa55c332c11c650f8b0d))
* formatting ([2a25ca0](https://github.com/AkazaRenn/ublue-update/commit/2a25ca02bbf18d1b8911107f04bb0f753783f115))
* formatting and errors ([3248580](https://github.com/AkazaRenn/ublue-update/commit/32485806b6182d7ad104bfe0eeb559288167a572))
* formatting and errors ([53da743](https://github.com/AkazaRenn/ublue-update/commit/53da7431e5c4268519809c0d69bd4f1dd30a7aca))
* formatting errors after merge ([d3f011a](https://github.com/AkazaRenn/ublue-update/commit/d3f011ae4f46dce352ed46e61d20029845bd1fde))
* get active sessions with logind, use capture_output=True for subprocess.run() ([2907793](https://github.com/AkazaRenn/ublue-update/commit/2907793477832eda0bd21d80aad8dc151280546d))
* get xdg_runtime_dir through loginctl ([96586ee](https://github.com/AkazaRenn/ublue-update/commit/96586ee0e9e457a33484e0c817795f4babae62a2))
* **hardware.py:** fixed memory check ([85de3b3](https://github.com/AkazaRenn/ublue-update/commit/85de3b3e3d2c31889bc70695446f58e217ef8bda))
* **hardware.py:** fixed memory check ([3f9aaec](https://github.com/AkazaRenn/ublue-update/commit/3f9aaec05fd04183f3eacdf1fef1b3260522c055))
* import notification_manager module properly ([ebc387f](https://github.com/AkazaRenn/ublue-update/commit/ebc387fadfafefdc024b071fac54d8269a648902))
* Improve brew updater to work even if bash_profile change is missing ([#82](https://github.com/AkazaRenn/ublue-update/issues/82)) ([9993055](https://github.com/AkazaRenn/ublue-update/commit/99930556ea977fdf8234d84f45e402bdc162bbfa))
* Just drop the registry reference in URL for latest image ([d6b9e37](https://github.com/AkazaRenn/ublue-update/commit/d6b9e3750a46e9b102590f8f48eb6d13b575aff5))
* Just drop the registry reference in URL for latest image ([#47](https://github.com/AkazaRenn/ublue-update/issues/47)) ([00e8724](https://github.com/AkazaRenn/ublue-update/commit/00e87240721f93f91f50b4d612f9c855b08c22a1))
* lessen preset priority ([#121](https://github.com/AkazaRenn/ublue-update/issues/121)) ([2e8c9d2](https://github.com/AkazaRenn/ublue-update/commit/2e8c9d2d2246d1c25bb3289423eb8e2546b387ad))
* make -c option work as intended ([c743b98](https://github.com/AkazaRenn/ublue-update/commit/c743b9844e1455ba07e33b159afee6c8a931f9df))
* make subprocess.run() statements not rely on $PATH ([9592dec](https://github.com/AkazaRenn/ublue-update/commit/9592dec3f5e40915ec56560baa18b1c30ed837b2))
* make systemd service more robust ([ff74a78](https://github.com/AkazaRenn/ublue-update/commit/ff74a784f8b991f9e0d1af7f3c0574c37a48fe2a))
* Make update scripts executable in spec file ([d57ea4e](https://github.com/AkazaRenn/ublue-update/commit/d57ea4ebbf080173d3cb9a56dbf89cd6bb1e11f5))
* min_battery_percent = 0 now works to "skip" ([5ad9228](https://github.com/AkazaRenn/ublue-update/commit/5ad9228568be47cd374e627a84008e609104d31d))
* min_battery_percent = 0 now works to "skip" battery check ([#89](https://github.com/AkazaRenn/ublue-update/issues/89)) ([c1f7355](https://github.com/AkazaRenn/ublue-update/commit/c1f735557c98f3483a96b81693571713a9f77305))
* missing build requires python-pip ([13086de](https://github.com/AkazaRenn/ublue-update/commit/13086dec15e3d753d448cbcd9c7bd236c0b0c3df))
* missing build requires python-pip ([#56](https://github.com/AkazaRenn/ublue-update/issues/56)) ([c583cae](https://github.com/AkazaRenn/ublue-update/commit/c583cae21c10eca1b7bf146f2ee066d65dc8af2a))
* move update logging into run_updates() function ([cb309ac](https://github.com/AkazaRenn/ublue-update/commit/cb309ac12863ac72fbbbe95372bbed542c16ecdf))
* moved log.info outside of if check ([ed25b1c](https://github.com/AkazaRenn/ublue-update/commit/ed25b1c3e17bcd8a64b2b60f26c73ba8a20bb404))
* **notifications:** Handle actions properly ([763256a](https://github.com/AkazaRenn/ublue-update/commit/763256afa27f0edbed2e7bea96ccb4650e59b288))
* notify outside of for loop ([e799b0a](https://github.com/AkazaRenn/ublue-update/commit/e799b0afabd5eeab4daae4d30edc0f9ec964907a))
* offline iso update ([ea267e0](https://github.com/AkazaRenn/ublue-update/commit/ea267e044b47ee206620e59112bc5b0f2b8b623f))
* offline iso update ([#87](https://github.com/AkazaRenn/ublue-update/issues/87)) ([986ed9a](https://github.com/AkazaRenn/ublue-update/commit/986ed9a89bac290db79c393a2687794dce33827d))
* only show post update notification when there is a pending deployment ([#83](https://github.com/AkazaRenn/ublue-update/issues/83)) ([e117cc8](https://github.com/AkazaRenn/ublue-update/commit/e117cc89fd99b9438576cdd5e560afcef6c028d3))
* preserve unsigned image tag upon rebase ([0ff9fd5](https://github.com/AkazaRenn/ublue-update/commit/0ff9fd546607548e4aa15b82ca47bbe8c6ad14d4))
* preserve unsigned image tag upon rebase ([#75](https://github.com/AkazaRenn/ublue-update/issues/75)) ([75fd78b](https://github.com/AkazaRenn/ublue-update/commit/75fd78b0be2379185874074a4c0c5f2501ddd417))
* properly initialize env vars for notifications ([8d8ef28](https://github.com/AkazaRenn/ublue-update/commit/8d8ef28d8c522ed20586815960a9a500a53aba2e))
* Properly pull URL and tag from current image ([b0a35a2](https://github.com/AkazaRenn/ublue-update/commit/b0a35a2b1bc9d674cc651200afc0796bcdfc9150))
* Properly pull URL and tag from current image ([#46](https://github.com/AkazaRenn/ublue-update/issues/46)) ([aedb3cb](https://github.com/AkazaRenn/ublue-update/commit/aedb3cb8e55a8c64ce6580d9e8a3210500ca17ab))
* reformat ([083a87a](https://github.com/AkazaRenn/ublue-update/commit/083a87a867bad87afc421e102031aaeff1f63b42))
* reformat to please flake8 ([0e22e49](https://github.com/AkazaRenn/ublue-update/commit/0e22e49a2e394f5708cc131d84494a55be65a866))
* reformat to please the formatting gods ([7856d98](https://github.com/AkazaRenn/ublue-update/commit/7856d988cc0b219acf368fc6bdf5650cb4889058))
* reformat to please the formatting gods ([38a18ec](https://github.com/AkazaRenn/ublue-update/commit/38a18ecbbf5a6c3bffeafc4d5e1668b4271d8d39))
* remove 'sudo' from 'sudo install' in rpm spec ([8d80161](https://github.com/AkazaRenn/ublue-update/commit/8d801611a863338552a10047aa64cfb86be35b5f))
* remove build remnent from git ([0e2fe81](https://github.com/AkazaRenn/ublue-update/commit/0e2fe8197cdc5b9a0debc61f07c5d209c7c8bf6e))
* Remove confusing Notification regarding System updates ([d3123c0](https://github.com/AkazaRenn/ublue-update/commit/d3123c0d1bc2a2fa61094e1bfb685c9561ce7699))
* Remove confusing Notification regarding System updates ([#128](https://github.com/AkazaRenn/ublue-update/issues/128)) ([dce31e5](https://github.com/AkazaRenn/ublue-update/commit/dce31e5418e8aa45ef1b1941b4775865065146af))
* remove debug code, fixed crash because of keyerror with temporary sessions ([086e027](https://github.com/AkazaRenn/ublue-update/commit/086e0270706d841ab0601d6d0f3c5340d75cd5c4))
* remove debug python code and unneeded lines in systemd service ([2b89d8d](https://github.com/AkazaRenn/ublue-update/commit/2b89d8d2c7e3d0d405402fcecdd067fb8ad7eb1b))
* remove home directory configuration, ublue-update is now system-wide ([03a70eb](https://github.com/AkazaRenn/ublue-update/commit/03a70eb3234ddbbfbf576323dd8fd97d9a9bef0a))
* remove ignores for **.md and **.txt ([837f0d5](https://github.com/AkazaRenn/ublue-update/commit/837f0d55e8ba7e540621ac6d941beec1ea411526))
* remove notification when system passes checks when running with -c ([0e1fa6e](https://github.com/AkazaRenn/ublue-update/commit/0e1fa6eedd18a86cef6c98aa90685e06a77e42a8))
* Remove the broken fallback config logic ([cea7eb8](https://github.com/AkazaRenn/ublue-update/commit/cea7eb8610be6add67c1f8963b0fc048aa2d8840))
* remove typo in arguments for notify-send ([54d92a8](https://github.com/AkazaRenn/ublue-update/commit/54d92a8a06e847f287d4f6f099978ce06df38776))
* remove typo in arguments for notify-send ([41e3ed9](https://github.com/AkazaRenn/ublue-update/commit/41e3ed90b919891d98fd4a6b86a0bc3c04aa1831))
* remove typo in arguments for notify-send ([#61](https://github.com/AkazaRenn/ublue-update/issues/61)) ([0b0edf0](https://github.com/AkazaRenn/ublue-update/commit/0b0edf048a02a5a15ab9fb9c909383818dd2146e))
* remove unnecessary \ ([856dee2](https://github.com/AkazaRenn/ublue-update/commit/856dee270f75490a6be4620e4b99d5157894f6fa))
* remove unnecessary documentation ([f6aeb24](https://github.com/AkazaRenn/ublue-update/commit/f6aeb24041558649c45815ba0bde67171ebb576e))
* remove unnecessary documentation ([#36](https://github.com/AkazaRenn/ublue-update/issues/36)) ([96fc700](https://github.com/AkazaRenn/ublue-update/commit/96fc7008cdece6b728ed4734c9b49e633ca7ec61))
* remove unnecessary if statement ([704e80e](https://github.com/AkazaRenn/ublue-update/commit/704e80e12e1f33e618fca4b880d6efdbcb55c41f))
* remove unused makefile recipes ([93ea24a](https://github.com/AkazaRenn/ublue-update/commit/93ea24a290aaae4e66bec1397655c67ffcf4cf12))
* removed exit() and print() function used for debugging ([2eca189](https://github.com/AkazaRenn/ublue-update/commit/2eca1892a262ff7b1381dfcecb65d27fa5cd203e))
* rename config file value to be loaded ([f5f7673](https://github.com/AkazaRenn/ublue-update/commit/f5f76732c8f2d7e37ca90e744b88430417fd2397))
* revert ([da42c71](https://github.com/AkazaRenn/ublue-update/commit/da42c718c9fcc180c28c79f26b7c43f92003aa6d))
* revert systemd service changes ([c2f16ae](https://github.com/AkazaRenn/ublue-update/commit/c2f16ae3fd6a6569fcc5abac4f3721536e2c6bb9))
* **session:** Ensure session type exists before appending active session ([53d4b13](https://github.com/AkazaRenn/ublue-update/commit/53d4b139b20a0fc43122892d8d28536c8e13c410))
* single line that makes the app not executable ([08706a5](https://github.com/AkazaRenn/ublue-update/commit/08706a546b8199bcad6ee1a611185e1ed1a82729))
* skip copr-build on PRs ([7ef783c](https://github.com/AkazaRenn/ublue-update/commit/7ef783c27e1619434f2d81677f16bd15c4743ed9))
* skip copr-build on PRs ([9d1b30a](https://github.com/AkazaRenn/ublue-update/commit/9d1b30aecc9eb815eb34205f6a2128bd77f7ed37))
* **systemd timer:** fixed spelling of persistent ([0c74fa2](https://github.com/AkazaRenn/ublue-update/commit/0c74fa24f8e7eab557fa7030571b671bee964b62))
* try to build release rpm ([83dfafa](https://github.com/AkazaRenn/ublue-update/commit/83dfafab19b46364aab689a4dc6b68d06f22f541))
* try to build release rpm ([#39](https://github.com/AkazaRenn/ublue-update/issues/39)) ([12b2ac2](https://github.com/AkazaRenn/ublue-update/commit/12b2ac2da57bfe35b29f96bf655365643c7a34cc))
* try to use staging copr project ([#71](https://github.com/AkazaRenn/ublue-update/issues/71)) ([2686474](https://github.com/AkazaRenn/ublue-update/commit/26864748cc9deca97a8387f33b4b8b95989b0a79))
* typo ([6d1a817](https://github.com/AkazaRenn/ublue-update/commit/6d1a817a9ebbb2d14603c1d1b2e3348c02ee4464))
* uncomment regular rpm output ([f32798f](https://github.com/AkazaRenn/ublue-update/commit/f32798fba0ecf87996eba049b48cbadeff7d3746))
* update cli args for `sudo` to be in the correct order ([2f38bf8](https://github.com/AkazaRenn/ublue-update/commit/2f38bf815a05dbf653d89776eb5471279e61472d))
* update comment ([3a6aff7](https://github.com/AkazaRenn/ublue-update/commit/3a6aff771def651f25fcbec6ff5504ae49666669))
* update error message logging, log subprocess output ([#77](https://github.com/AkazaRenn/ublue-update/issues/77)) ([007e1e3](https://github.com/AkazaRenn/ublue-update/commit/007e1e3b263c542c0510cc8bbb11272127fc3b75))
* update install instructions to new image location ([eba75de](https://github.com/AkazaRenn/ublue-update/commit/eba75de2e56d96afd4b409427339206f242cb28e))
* update shellcheck path in RPM spec ([3fcefb1](https://github.com/AkazaRenn/ublue-update/commit/3fcefb137ab8a46e6f9fbc25274bdd1a0859abce))
* update tags ([d2cc2a6](https://github.com/AkazaRenn/ublue-update/commit/d2cc2a63b2c6cf972fb5239d0e8148dca6827a37))
* update ublue_update_version macro to match version with github tag ([60ad5fd](https://github.com/AkazaRenn/ublue-update/commit/60ad5fd263253d2759e8d359b6bae94f55fae7ae))
* update ublue_update_version macro to match version with github tag ([#49](https://github.com/AkazaRenn/ublue-update/issues/49)) ([f0bbc04](https://github.com/AkazaRenn/ublue-update/commit/f0bbc048556680f710fae4b3906f0244b9c043dc))
* use builder container file for release ([51b496a](https://github.com/AkazaRenn/ublue-update/commit/51b496a6a43ebfe3cb64ee5fbb2e308c79b9cb3c))
* use less sudo, clean up process ee ([bdc19c5](https://github.com/AkazaRenn/ublue-update/commit/bdc19c50c4adcab42bdd8e16d8bff4d74be81cb0))
* use os._exit() instead of sys.exit() to completely kill program ([abca773](https://github.com/AkazaRenn/ublue-update/commit/abca7739599b6bbb0cbef7b7312aed69c84e846f))
* use tabs not spaces ([7e33290](https://github.com/AkazaRenn/ublue-update/commit/7e332909d7a9443a0ba895515ac71b6fa7d3a56b))
* use the correct name ([2848f64](https://github.com/AkazaRenn/ublue-update/commit/2848f6434eaca1c71680e24250d03bf23a0c1504))
* use user_uid instead of process_uid, fixes user updates ([ef5d4e7](https://github.com/AkazaRenn/ublue-update/commit/ef5d4e73a95051ae2b059920d9a2352cebb3daac))
* use user['Name'] instead of user.pw_name ([b84e2e3](https://github.com/AkazaRenn/ublue-update/commit/b84e2e3de6829c6cd2f0d6dcadc93c896b492c07))

## [1.4.0](https://github.com/ublue-os/ublue-update/compare/v1.3.0...v1.4.0) (2024-05-02)


### Features

* Add topgrade support ([8a926c5](https://github.com/ublue-os/ublue-update/commit/8a926c5755d10aefc23480bc506b3936c2a7c58a))
* Add topgrade support ([#102](https://github.com/ublue-os/ublue-update/issues/102)) ([61dd86c](https://github.com/ublue-os/ublue-update/commit/61dd86c698e30c852c2cbd401bf407f9449553d8))
* Add updater for brew ([#76](https://github.com/ublue-os/ublue-update/issues/76)) ([63d40a1](https://github.com/ublue-os/ublue-update/commit/63d40a1688b52d4dcbcf37797ff14a355025c7fc))
* auto sign images ([#73](https://github.com/ublue-os/ublue-update/issues/73)) ([6acce45](https://github.com/ublue-os/ublue-update/commit/6acce45767dfd05e82c722c771b65400ce97cc82))
* move system update script to python ([#81](https://github.com/ublue-os/ublue-update/issues/81)) ([be229d1](https://github.com/ublue-os/ublue-update/commit/be229d1ee60dd7a5f7f5d0f118634bfa31918a88))
* Remove rebase step now that ISOs are nearly ready ([#105](https://github.com/ublue-os/ublue-update/issues/105)) ([1e670f0](https://github.com/ublue-os/ublue-update/commit/1e670f0044026b434da746bb28fa05a21fade00e))
* Remove rebase step now that ISOs are nearly ready, move topgrade configs to /usr/share, cleanup. ([8307b17](https://github.com/ublue-os/ublue-update/commit/8307b17a3c280431ffce863b7b98e74d31766cdb))
* **system-update:** Allow switching between branches via rebase ([e14f166](https://github.com/ublue-os/ublue-update/commit/e14f1665402a4e01a1778833c27568a07d48acfb))
* **system-update:** Allow switching between branches via rebase ([#91](https://github.com/ublue-os/ublue-update/issues/91)) ([e013061](https://github.com/ublue-os/ublue-update/commit/e013061013c97d5cf49d14237fdfe6b12ace8afe))


### Bug Fixes

* account for ostree-unverified-registry shorthand ([8271032](https://github.com/ublue-os/ublue-update/commit/8271032feed7b907d50520dfbc45afbc47d1cd6a))
* add brew to user and distrobox to system ([2e0e582](https://github.com/ublue-os/ublue-update/commit/2e0e582e125359108a910b5225f4daeb2e64a9bc))
* add brew to user and distrobox to system ([#107](https://github.com/ublue-os/ublue-update/issues/107)) ([d8fb315](https://github.com/ublue-os/ublue-update/commit/d8fb3157fac1f8c5836beae8ea97097c50403051))
* be more carefull when to rebase ([2ba442f](https://github.com/ublue-os/ublue-update/commit/2ba442f4be39dccf663dc1ae0c6696d6e738ca78))
* be more carefull when to rebase ([#88](https://github.com/ublue-os/ublue-update/issues/88)) ([427912c](https://github.com/ublue-os/ublue-update/commit/427912c53db77dab15f6e80c85f5d7a6118925b2))
* bump version ([32ccf70](https://github.com/ublue-os/ublue-update/commit/32ccf7082ed5228d2f55968eadf2469e4e1ef7f7))
* bypass distrobox upgrade sudo checks ([#69](https://github.com/ublue-os/ublue-update/issues/69)) ([127ed90](https://github.com/ublue-os/ublue-update/commit/127ed90804f2b56ba0191a7255edc9ff02a0754e))
* **flake8:** Ignore W503 and W504 ([5111b06](https://github.com/ublue-os/ublue-update/commit/5111b0643b146712117de9cae015f79296ee1646))
* Improve brew updater to work even if bash_profile change is missing ([#82](https://github.com/ublue-os/ublue-update/issues/82)) ([9993055](https://github.com/ublue-os/ublue-update/commit/99930556ea977fdf8234d84f45e402bdc162bbfa))
* min_battery_percent = 0 now works to "skip" ([5ad9228](https://github.com/ublue-os/ublue-update/commit/5ad9228568be47cd374e627a84008e609104d31d))
* min_battery_percent = 0 now works to "skip" battery check ([#89](https://github.com/ublue-os/ublue-update/issues/89)) ([c1f7355](https://github.com/ublue-os/ublue-update/commit/c1f735557c98f3483a96b81693571713a9f77305))
* offline iso update ([ea267e0](https://github.com/ublue-os/ublue-update/commit/ea267e044b47ee206620e59112bc5b0f2b8b623f))
* offline iso update ([#87](https://github.com/ublue-os/ublue-update/issues/87)) ([986ed9a](https://github.com/ublue-os/ublue-update/commit/986ed9a89bac290db79c393a2687794dce33827d))
* only show post update notification when there is a pending deployment ([#83](https://github.com/ublue-os/ublue-update/issues/83)) ([e117cc8](https://github.com/ublue-os/ublue-update/commit/e117cc89fd99b9438576cdd5e560afcef6c028d3))
* preserve unsigned image tag upon rebase ([0ff9fd5](https://github.com/ublue-os/ublue-update/commit/0ff9fd546607548e4aa15b82ca47bbe8c6ad14d4))
* preserve unsigned image tag upon rebase ([#75](https://github.com/ublue-os/ublue-update/issues/75)) ([75fd78b](https://github.com/ublue-os/ublue-update/commit/75fd78b0be2379185874074a4c0c5f2501ddd417))
* try to use staging copr project ([#71](https://github.com/ublue-os/ublue-update/issues/71)) ([2686474](https://github.com/ublue-os/ublue-update/commit/26864748cc9deca97a8387f33b4b8b95989b0a79))
* update error message logging, log subprocess output ([#77](https://github.com/ublue-os/ublue-update/issues/77)) ([007e1e3](https://github.com/ublue-os/ublue-update/commit/007e1e3b263c542c0510cc8bbb11272127fc3b75))

## [1.3.0](https://github.com/ublue-os/ublue-update/compare/v1.2.2...v1.3.0) (2023-09-20)


### Features

* **ci:** Split build for Fedora 38 and 39 ([#67](https://github.com/ublue-os/ublue-update/issues/67)) ([bd27a84](https://github.com/ublue-os/ublue-update/commit/bd27a84414aa917dbf4940defa062d9886164972))

## [1.2.2](https://github.com/ublue-os/ublue-update/compare/v1.2.1...v1.2.2) (2023-09-17)


### Bug Fixes

* change default max_mem_percent to 90.0 ([6119d3b](https://github.com/ublue-os/ublue-update/commit/6119d3b162ee72a28698ff501f7c7b6ead9c3594))
* formatting and errors ([53da743](https://github.com/ublue-os/ublue-update/commit/53da7431e5c4268519809c0d69bd4f1dd30a7aca))
* **hardware.py:** fixed memory check ([3f9aaec](https://github.com/ublue-os/ublue-update/commit/3f9aaec05fd04183f3eacdf1fef1b3260522c055))
* remove typo in arguments for notify-send ([41e3ed9](https://github.com/ublue-os/ublue-update/commit/41e3ed90b919891d98fd4a6b86a0bc3c04aa1831))
* remove typo in arguments for notify-send ([#61](https://github.com/ublue-os/ublue-update/issues/61)) ([0b0edf0](https://github.com/ublue-os/ublue-update/commit/0b0edf048a02a5a15ab9fb9c909383818dd2146e))
* skip copr-build on PRs ([9d1b30a](https://github.com/ublue-os/ublue-update/commit/9d1b30aecc9eb815eb34205f6a2128bd77f7ed37))

## [1.2.1](https://github.com/ublue-os/ublue-update/compare/v1.2.0...v1.2.1) (2023-09-04)


### Bug Fixes

* missing build requires python-pip ([#56](https://github.com/ublue-os/ublue-update/issues/56)) ([c583cae](https://github.com/ublue-os/ublue-update/commit/c583cae21c10eca1b7bf146f2ee066d65dc8af2a))

## [1.2.0](https://github.com/ublue-os/ublue-update/compare/v1.1.6...v1.2.0) (2023-09-02)


### Features

* Add module that waits for transaction completion before updating ([0abd5dc](https://github.com/ublue-os/ublue-update/commit/0abd5dccf0a805daed435ad791bfc94afd10a91c))
* Add module that waits for transaction completion before updating ([#55](https://github.com/ublue-os/ublue-update/issues/55)) ([d8d038b](https://github.com/ublue-os/ublue-update/commit/d8d038bb945a34b8c4fd562ba14c696355ea4ff4))
* Add support for updating with Fleek ([bcc731c](https://github.com/ublue-os/ublue-update/commit/bcc731cf609372ec54e5b5a0f692d8f895b01f0a))
* Add support for updating with Fleek ([#53](https://github.com/ublue-os/ublue-update/issues/53)) ([6bd7568](https://github.com/ublue-os/ublue-update/commit/6bd75682077d45f2cbf1b8c6a61c95a77cab5c43))


### Bug Fixes

* typo ([6d1a817](https://github.com/ublue-os/ublue-update/commit/6d1a817a9ebbb2d14603c1d1b2e3348c02ee4464))

## [1.1.6](https://github.com/ublue-os/ublue-update/compare/v1.1.5...v1.1.6) (2023-08-26)


### Bug Fixes

* update ublue_update_version macro to match version with github tag ([60ad5fd](https://github.com/ublue-os/ublue-update/commit/60ad5fd263253d2759e8d359b6bae94f55fae7ae))
* update ublue_update_version macro to match version with github tag ([#49](https://github.com/ublue-os/ublue-update/issues/49)) ([f0bbc04](https://github.com/ublue-os/ublue-update/commit/f0bbc048556680f710fae4b3906f0244b9c043dc))

## [1.1.5](https://github.com/ublue-os/ublue-update/compare/v1.1.4...v1.1.5) (2023-07-16)


### Bug Fixes

* Properly pull URL and tag from current image ([b0a35a2](https://github.com/ublue-os/ublue-update/commit/b0a35a2b1bc9d674cc651200afc0796bcdfc9150))
* Properly pull URL and tag from current image ([#46](https://github.com/ublue-os/ublue-update/issues/46)) ([aedb3cb](https://github.com/ublue-os/ublue-update/commit/aedb3cb8e55a8c64ce6580d9e8a3210500ca17ab))

## [1.1.4](https://github.com/ublue-os/ublue-update/compare/v1.1.3...v1.1.4) (2023-07-15)


### Bug Fixes

* added back Containerfile.builder to fix build action ([abf152e](https://github.com/ublue-os/ublue-update/commit/abf152ee44a36dbd5bbdb233fbd01c271c1abb3c))
* fix program exiting telling user checks have failed when running from notification ([7b24b8c](https://github.com/ublue-os/ublue-update/commit/7b24b8cb4b31a2406c55cc88e60a9a90bda1b173))
* fix program exiting telling user checks have failed when running from notification ([#43](https://github.com/ublue-os/ublue-update/issues/43)) ([2b42c62](https://github.com/ublue-os/ublue-update/commit/2b42c628660f3fa5999d8eb1542c919b9c44a087))
* fix updater throwing exception when dbus is inactive ([ee226b7](https://github.com/ublue-os/ublue-update/commit/ee226b7cfd164ec71487ea73b476eb8213775fb4))
* fixed and simplified argument behavior, use better naming ([3068671](https://github.com/ublue-os/ublue-update/commit/30686717c4e8ad5c4b369694d8f147718efa6656))
* formatting ([2a25ca0](https://github.com/ublue-os/ublue-update/commit/2a25ca02bbf18d1b8911107f04bb0f753783f115))
* make -c option work as intended ([c743b98](https://github.com/ublue-os/ublue-update/commit/c743b9844e1455ba07e33b159afee6c8a931f9df))
* move update logging into run_updates() function ([cb309ac](https://github.com/ublue-os/ublue-update/commit/cb309ac12863ac72fbbbe95372bbed542c16ecdf))
* reformat ([083a87a](https://github.com/ublue-os/ublue-update/commit/083a87a867bad87afc421e102031aaeff1f63b42))
* reformat to please the formatting gods ([38a18ec](https://github.com/ublue-os/ublue-update/commit/38a18ecbbf5a6c3bffeafc4d5e1668b4271d8d39))
* remove build remnent from git ([0e2fe81](https://github.com/ublue-os/ublue-update/commit/0e2fe8197cdc5b9a0debc61f07c5d209c7c8bf6e))
* remove ignores for **.md and **.txt ([837f0d5](https://github.com/ublue-os/ublue-update/commit/837f0d55e8ba7e540621ac6d941beec1ea411526))
* remove notification when system passes checks when running with -c ([0e1fa6e](https://github.com/ublue-os/ublue-update/commit/0e1fa6eedd18a86cef6c98aa90685e06a77e42a8))
* remove unnecessary if statement ([704e80e](https://github.com/ublue-os/ublue-update/commit/704e80e12e1f33e618fca4b880d6efdbcb55c41f))
* rename config file value to be loaded ([f5f7673](https://github.com/ublue-os/ublue-update/commit/f5f76732c8f2d7e37ca90e744b88430417fd2397))
* use os._exit() instead of sys.exit() to completely kill program ([abca773](https://github.com/ublue-os/ublue-update/commit/abca7739599b6bbb0cbef7b7312aed69c84e846f))

## [1.1.3](https://github.com/ublue-os/ublue-update/compare/v1.1.2...v1.1.3) (2023-07-15)


### Bug Fixes

* try to build release rpm ([83dfafa](https://github.com/ublue-os/ublue-update/commit/83dfafab19b46364aab689a4dc6b68d06f22f541))
* try to build release rpm ([#39](https://github.com/ublue-os/ublue-update/issues/39)) ([12b2ac2](https://github.com/ublue-os/ublue-update/commit/12b2ac2da57bfe35b29f96bf655365643c7a34cc))

## [1.1.2](https://github.com/ublue-os/ublue-update/compare/v1.1.1...v1.1.2) (2023-07-15)


### Bug Fixes

* build rpm in release workflow ([#38](https://github.com/ublue-os/ublue-update/issues/38)) ([c1517cc](https://github.com/ublue-os/ublue-update/commit/c1517ccd183fb0f67380ba4d8af68f1b358240ac))
* remove unnecessary documentation ([f6aeb24](https://github.com/ublue-os/ublue-update/commit/f6aeb24041558649c45815ba0bde67171ebb576e))
* remove unnecessary documentation ([#36](https://github.com/ublue-os/ublue-update/issues/36)) ([96fc700](https://github.com/ublue-os/ublue-update/commit/96fc7008cdece6b728ed4734c9b49e633ca7ec61))

## [1.1.1](https://github.com/ublue-os/ublue-update/compare/v1.1.0...v1.1.1) (2023-07-15)


### Bug Fixes

* use builder container file for release ([51b496a](https://github.com/ublue-os/ublue-update/commit/51b496a6a43ebfe3cb64ee5fbb2e308c79b9cb3c))

## [1.1.0](https://github.com/ublue-os/ublue-update/compare/v1.0.1...v1.1.0) (2023-07-09)


### Features

* added custom notification_manager to replace notify2 ([4b25c7c](https://github.com/ublue-os/ublue-update/commit/4b25c7c97a5f1f44a5d32e6df3a000e44cb02cfd))
* added NotificationObject, holds all notification data and makes it easier to deal with actions ([f67e3c9](https://github.com/ublue-os/ublue-update/commit/f67e3c905ae1ff19b988787cba6023cf410946ac))
* moved all dbus and glib logic into notification_manager ([d69ac11](https://github.com/ublue-os/ublue-update/commit/d69ac116351ce09a3839ea245f95998a3faa1e89))
* removed dependency on notify2 ([dc3325e](https://github.com/ublue-os/ublue-update/commit/dc3325e45aaafad6c9afe174b16971d66aef347a))


### Bug Fixes

* add extra spacing to please code formatter ([99fa0a3](https://github.com/ublue-os/ublue-update/commit/99fa0a370894001860b9333d1390985f93523fee))
* added import for DBusGMainLoop ([476c872](https://github.com/ublue-os/ublue-update/commit/476c872c58783487b9a045f1d2718590e7660543))
* fixed issues that prevented script from running, removed commented out code ([22b83c8](https://github.com/ublue-os/ublue-update/commit/22b83c850bf8dcb5dbba008f209a3f7705dc7579))
* fixed line length and corrected variable reference ([864e2ea](https://github.com/ublue-os/ublue-update/commit/864e2ea14872ca7c3d5b2f7b4d5848553425547f))
* import notification_manager module properly ([ebc387f](https://github.com/ublue-os/ublue-update/commit/ebc387fadfafefdc024b071fac54d8269a648902))

## [1.0.1](https://github.com/ublue-os/ublue-update/compare/v1.0.0...v1.0.1) (2023-07-06)


### Bug Fixes

* **config:** fix breakage when using fallback config, improved config logic to be more flexible ([f167dc9](https://github.com/ublue-os/ublue-update/commit/f167dc970d7b38e4ecf6d85895e800ce16760063))
* removed exit() and print() function used for debugging ([2eca189](https://github.com/ublue-os/ublue-update/commit/2eca1892a262ff7b1381dfcecb65d27fa5cd203e))

## 1.0.0 (2023-07-04)


### Features

* add log for when update is complete ([f3992f3](https://github.com/ublue-os/ublue-update/commit/f3992f39c5fae0db82e43e4192af67c7e9a7efce))
* add proof-of-concept containerfile for this project ([aeeb3c0](https://github.com/ublue-os/ublue-update/commit/aeeb3c08e459488b7dbd4a9737a3fa25f7f3a92a))
* add RPM build and restructure to make it work ([9642188](https://github.com/ublue-os/ublue-update/commit/9642188e94a1d0c147b9b78efa37fba324eb23a3))
* added --check option to run through update checks and exit ([ac0523b](https://github.com/ublue-os/ublue-update/commit/ac0523bea189c3216bdb45962d847a41169cdca1))
* made config loading more robust ([722c956](https://github.com/ublue-os/ublue-update/commit/722c956392235d268eacee803d1ccd00f930ab85))
* moved config format to toml, cleaned up config logic to default to /usr/etc ([2c47f12](https://github.com/ublue-os/ublue-update/commit/2c47f12d942b9b2c79c277369c9f015af67fd15d))


### Bug Fixes

* Adjust update service and timer ([2dc0ccc](https://github.com/ublue-os/ublue-update/commit/2dc0ccc80cdaa850c7acd2729e883118e2212ad5))
* apply some small python cleanups ([69e42d0](https://github.com/ublue-os/ublue-update/commit/69e42d0c74a2d5f0a78881ca1fd9494bad39c919))
* formatting errors after merge ([d3f011a](https://github.com/ublue-os/ublue-update/commit/d3f011ae4f46dce352ed46e61d20029845bd1fde))
* Make update scripts executable in spec file ([d57ea4e](https://github.com/ublue-os/ublue-update/commit/d57ea4ebbf080173d3cb9a56dbf89cd6bb1e11f5))
* moved log.info outside of if check ([ed25b1c](https://github.com/ublue-os/ublue-update/commit/ed25b1c3e17bcd8a64b2b60f26c73ba8a20bb404))
* remove 'sudo' from 'sudo install' in rpm spec ([8d80161](https://github.com/ublue-os/ublue-update/commit/8d801611a863338552a10047aa64cfb86be35b5f))
* remove unused makefile recipes ([93ea24a](https://github.com/ublue-os/ublue-update/commit/93ea24a290aaae4e66bec1397655c67ffcf4cf12))
* single line that makes the app not executable ([08706a5](https://github.com/ublue-os/ublue-update/commit/08706a546b8199bcad6ee1a611185e1ed1a82729))
* **systemd timer:** fixed spelling of persistent ([0c74fa2](https://github.com/ublue-os/ublue-update/commit/0c74fa24f8e7eab557fa7030571b671bee964b62))
* update comment ([3a6aff7](https://github.com/ublue-os/ublue-update/commit/3a6aff771def651f25fcbec6ff5504ae49666669))
* update install instructions to new image location ([eba75de](https://github.com/ublue-os/ublue-update/commit/eba75de2e56d96afd4b409427339206f242cb28e))
* use tabs not spaces ([7e33290](https://github.com/ublue-os/ublue-update/commit/7e332909d7a9443a0ba895515ac71b6fa7d3a56b))
* use the correct name ([2848f64](https://github.com/ublue-os/ublue-update/commit/2848f6434eaca1c71680e24250d03bf23a0c1504))

## 1.0.0 (2023-07-03)


### Features

* add log for when update is complete ([f3992f3](https://github.com/akdev1l/ublue-update/commit/f3992f39c5fae0db82e43e4192af67c7e9a7efce))
* add proof-of-concept containerfile for this project ([aeeb3c0](https://github.com/akdev1l/ublue-update/commit/aeeb3c08e459488b7dbd4a9737a3fa25f7f3a92a))
* add RPM build and restructure to make it work ([9642188](https://github.com/akdev1l/ublue-update/commit/9642188e94a1d0c147b9b78efa37fba324eb23a3))
* added --check option to run through update checks and exit ([ac0523b](https://github.com/akdev1l/ublue-update/commit/ac0523bea189c3216bdb45962d847a41169cdca1))
* made config loading more robust ([722c956](https://github.com/akdev1l/ublue-update/commit/722c956392235d268eacee803d1ccd00f930ab85))


### Bug Fixes

* apply some small python cleanups ([69e42d0](https://github.com/akdev1l/ublue-update/commit/69e42d0c74a2d5f0a78881ca1fd9494bad39c919))
* formatting errors after merge ([d3f011a](https://github.com/akdev1l/ublue-update/commit/d3f011ae4f46dce352ed46e61d20029845bd1fde))
* Make update scripts executable in spec file ([d57ea4e](https://github.com/akdev1l/ublue-update/commit/d57ea4ebbf080173d3cb9a56dbf89cd6bb1e11f5))
* moved log.info outside of if check ([ed25b1c](https://github.com/akdev1l/ublue-update/commit/ed25b1c3e17bcd8a64b2b60f26c73ba8a20bb404))
* remove 'sudo' from 'sudo install' in rpm spec ([8d80161](https://github.com/akdev1l/ublue-update/commit/8d801611a863338552a10047aa64cfb86be35b5f))
* remove unused makefile recipes ([93ea24a](https://github.com/akdev1l/ublue-update/commit/93ea24a290aaae4e66bec1397655c67ffcf4cf12))
* single line that makes the app not executable ([08706a5](https://github.com/akdev1l/ublue-update/commit/08706a546b8199bcad6ee1a611185e1ed1a82729))
* update comment ([3a6aff7](https://github.com/akdev1l/ublue-update/commit/3a6aff771def651f25fcbec6ff5504ae49666669))
* update install instructions to new image location ([eba75de](https://github.com/akdev1l/ublue-update/commit/eba75de2e56d96afd4b409427339206f242cb28e))
* use tabs not spaces ([7e33290](https://github.com/akdev1l/ublue-update/commit/7e332909d7a9443a0ba895515ac71b6fa7d3a56b))
* use the correct name ([2848f64](https://github.com/akdev1l/ublue-update/commit/2848f6434eaca1c71680e24250d03bf23a0c1504))
