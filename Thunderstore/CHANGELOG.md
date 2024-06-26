# Changelog

All notable changes to this project will be documented in this file. See [conventional commits](https://www.conventionalcommits.org/) for commit guidelines.

---
## [0.0.6](https://github.com/bananasov/LethalVibrations/compare/v0.0.5..0.0.6) - 2024-03-31

### Bug Fixes

- Remove the stupid BepInEx stuff i did - ([f7213c0](https://github.com/bananasov/LethalVibrations/commit/f7213c01bbaa4f357786d54f56822b8c636c0c5f)) - sovnya
- Disable airhorn vibrations by default - ([b24efcf](https://github.com/bananasov/LethalVibrations/commit/b24efcf0a55e5ba1a7d54c3f1b8804ebec7a77ab)) - sovnya
- Let other clients be able to vibrate your plug when the ship horn is pulled - ([5967d29](https://github.com/bananasov/LethalVibrations/commit/5967d2939c7022d2c68ab19dd13f385baccf4d01)) - sovnya

### Features

- Vibrate on airhorn - ([79e25d1](https://github.com/bananasov/LethalVibrations/commit/79e25d10ce062e53e18378549765b999d590d13c)) - sovnya
- Vibration upon ship horn pulled - ([cf174f7](https://github.com/bananasov/LethalVibrations/commit/cf174f7694999bb0ca31e68fbb43da0ae47360be)) - sovnya
- Separate timed vibration functions - ([1251987](https://github.com/bananasov/LethalVibrations/commit/1251987193cebf61644e37072bd335fbf4886048)) - sovnya
- Add stun grenade explosion vibration - ([32f7595](https://github.com/bananasov/LethalVibrations/commit/32f7595623fdafdd3f56f306fe0b235b45d4dc07)) - sovnya

---
## [0.0.5](https://github.com/bananasov/LethalVibrations/compare/v0.0.4..v0.0.5) - 2024-01-10

### Bug Fixes

- Fix incorrect variable placement in Justfile - ([00a8251](https://github.com/bananasov/LethalVibrations/commit/00a825123d07c76ea9e5e65c4a09103f0d908f4b)) - sovnya
- Rename screen vibration variables - ([7e34385](https://github.com/bananasov/LethalVibrations/commit/7e3438561bcb3c476782386a1c74fe8293f17633)) - sovnya
- Disable ping scan vibrations by default - ([65ea2e4](https://github.com/bananasov/LethalVibrations/commit/65ea2e4becc544b635693e46a5e31e6566ca151c)) - sovnya
- Fix the stupid BepInEx annotations - ([694e585](https://github.com/bananasov/LethalVibrations/commit/694e58572104c8552ce268568a657bfe87ed77ff)) - sovnya
- Tweak config to reinforce good behavior - ([0cd0557](https://github.com/bananasov/LethalVibrations/commit/0cd05577a5a973f7e19ab743c8a4b98d8854ff9c)) - sovnya
- Reduce the amount of times you get vibrated when you pick up an item - ([273673e](https://github.com/bananasov/LethalVibrations/commit/273673e4adb121c14543b3d3c8c168c791af0817)) - sovnya

### Features

- Add vibration on quota reached - ([71a56b7](https://github.com/bananasov/LethalVibrations/commit/71a56b767cd8c47fc0dee5bb15441abaf4498aa2)) - sovnya
- Add vibrate on round survival - ([96b01e8](https://github.com/bananasov/LethalVibrations/commit/96b01e8eb791527020239feab50ebe85e30fd153)) - sovnya

### Miscellaneous Chores

- Remove unused imports - ([0d0582e](https://github.com/bananasov/LethalVibrations/commit/0d0582eef8d411e01545e316e6729c0aa4356f52)) - sovnya
- Remove unused walkie talkie variables - ([2bc1c29](https://github.com/bananasov/LethalVibrations/commit/2bc1c296c575335a087f120e365ce28527df2d60)) - sovnya

---
## [0.0.4](https://github.com/bananasov/LethalVibrations/compare/v0.0.3..v0.0.4) - 2024-01-03

### Bug Fixes

- Make the changelog generator look cooler - ([c454796](https://github.com/bananasov/LethalVibrations/commit/c45479614399bf4039767935fc9984484e154835)) - sovnya
- Rename 'GoodBoy' mode to just 'Rewarding' - ([4b1a30a](https://github.com/bananasov/LethalVibrations/commit/4b1a30a0f812a9b06434742cf30520f603a1c6f8)) - sovnya
- Make patch methods private and replace info logs to debug ones - ([afa74f3](https://github.com/bananasov/LethalVibrations/commit/afa74f340a3c1c40fe529964fb4159934ccc20b9)) - sovnya
- Remove really stupid walkie talkie vibrate - ([cf3a1d4](https://github.com/bananasov/LethalVibrations/commit/cf3a1d4ca2450b05170305b98211579326c341b4)) - sovnya
- Remove reference to Walkie Talkie patches - ([ce4b6d4](https://github.com/bananasov/LethalVibrations/commit/ce4b6d44deaf4edfe6ce4f92bf901bf57ce87aba)) - sovnya
- Fix justfile `package` command removing manifest before its read - ([aab2425](https://github.com/bananasov/LethalVibrations/commit/aab242521ed2f2f2a143d31769b686623c0c76e4)) - sovnya
- Exclude Thunderstore path for git-cliff - ([cc99e16](https://github.com/bananasov/LethalVibrations/commit/cc99e1641b22dba4bd1c8dee2390e544d33310d0)) - sovnya
- Fix package command adding the `Thunderstore` folder as the root in the zip - ([44b9611](https://github.com/bananasov/LethalVibrations/commit/44b9611b7ea6e1ce2b358615e688d104b57cdcea)) - sovnya

### Features

- Add git-cliff config - ([e4d83f1](https://github.com/bananasov/LethalVibrations/commit/e4d83f1cd85b418072ae597efe9c32e1c1e9680c)) - sovnya
- Add a justfile for easy building and copying - ([4bbb073](https://github.com/bananasov/LethalVibrations/commit/4bbb0735fa0cce8353f5abe58e7127ef9a1ea447)) - sovnya
- More configuration for the Justfile - ([ff6c232](https://github.com/bananasov/LethalVibrations/commit/ff6c232966a618434249d9a5c23b9f28db45576d)) - sovnya
- Clean command for Justfile - ([17da920](https://github.com/bananasov/LethalVibrations/commit/17da92071ebd6e9f3a65cc0ce7f7e588edfe6bbe)) - sovnya
- Create FUNDING.yml - ([0e449a5](https://github.com/bananasov/LethalVibrations/commit/0e449a534f108a6463b2e772efd5299397838b69)) - bananasov
- Add `package` command to justfile - ([8f95785](https://github.com/bananasov/LethalVibrations/commit/8f957852c030e99cd1b8eac74b7a0fd45e7587a8)) - sovnya
- Add Thunderstore packaging files - ([c7629b7](https://github.com/bananasov/LethalVibrations/commit/c7629b7e8a37fa1d7e49973790f741561d2150db)) - sovnya

### Miscellaneous Chores

- Make rider shut up about inconsistent naming for harmony injection - ([d97d59c](https://github.com/bananasov/LethalVibrations/commit/d97d59c70032448accdb338cfda0bbecde1448dc)) - sovnya
- Update gitignore file - ([37e70d1](https://github.com/bananasov/LethalVibrations/commit/37e70d178652bce1f78f2732196e5604e11cf815)) - sovnya
- Beautify code - ([c6734bb](https://github.com/bananasov/LethalVibrations/commit/c6734bb3128f4500cd6fbf701566f4950e7a62ce)) - sovnya
- Remove unused build file - ([6b66ba3](https://github.com/bananasov/LethalVibrations/commit/6b66ba3b7e28f8621baa903d4470a30d635ef3de)) - sovnya
- Clean up config variables even more - ([91106d0](https://github.com/bananasov/LethalVibrations/commit/91106d06ed06c7ed0cc910a6d8d0a3bff7edbbea)) - sovnya
- Simplify client checks for PlayerControllerB patches - ([6498937](https://github.com/bananasov/LethalVibrations/commit/6498937b59dade2c63619851da9a3febdbd960d1)) - sovnya
- Clean up logging - ([b074f53](https://github.com/bananasov/LethalVibrations/commit/b074f53e665e93efb75fd9b1bef7b06024114d8b)) - sovnya

---
## [0.0.3](https://github.com/bananasov/LethalVibrations/compare/v0.0.2..v0.0.3) - 2023-12-10

### Bug Fixes

- Minor project fixes - ([e0e0222](https://github.com/bananasov/LethalVibrations/commit/e0e02220ac63c4b0be4091a8798acddfa6c1573c)) - sovnya
- Disable walkie-talkie vibrations by default - ([31f58ee](https://github.com/bananasov/LethalVibrations/commit/31f58ee3cd2ffd71c14ee7b0237fa50d57b28182)) - sovnya
- Fix the shit that broke - ([7358fb2](https://github.com/bananasov/LethalVibrations/commit/7358fb24084ad6c246344b52d1abd55bba9274e7)) - sovnya
- Fix errors relating to renamed times variables - ([1c50001](https://github.com/bananasov/LethalVibrations/commit/1c500016a06e2ad0d80a5dd7872dd23469bb739b)) - sovnya

### Features

- Add ping scan config entries and rename time variables - ([9bc2689](https://github.com/bananasov/LethalVibrations/commit/9bc26890cf427f68107387ddbadc99629baf2cbe)) - sovnya
- Add Ping scan vibration - ([8dd66a6](https://github.com/bananasov/LethalVibrations/commit/8dd66a65fa9b3252fb6aad5aae78241b3729764c)) - sovnya

<!-- generated by git-cliff -->
