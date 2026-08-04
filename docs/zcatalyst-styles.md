# ZCatalyst Design System — Complete Styles Reference

> Source: ZCatalyst Design System Figma file (`dwQLnT4eJ3zCaOwhk7JXIn`)
> Collections: Mode (Light/Dark), Theme (Default Royal Blue/Purple)
> No paint styles or effect styles — all colors are variable-based.

---

## Table of Contents

- [Text Styles](#text-styles)
- [Color Variables — Mode Collection](#color-variables--mode-collection)
- [Color Variables — Theme Collection](#color-variables--theme-collection)
- [Full Variable Key Reference](#full-variable-key-reference)

---

## Text Styles

26 text styles total. Primary font: **Inter**. Code font: **Roboto Mono**.

| Style Name | Key | Font | Weight | Size | Line Height | Letter Spacing |
|---|---|---|---|---|---|---|
| Service Name | `0960212d4963bc7bb5b8c9f8166310d86cf5ffb2` | Inter | Semi Bold | 16px | 20px | 6% |
| Headlines/H1 | `25a8a1ac56ecfeab817800c7d35a0a854b4c5f17` | Inter | Semi Bold | 40px | Auto | 0 |
| Headlines/H2 | `e3c4e89c4987b83a0de01e874a704698beb2ef79` | Inter | Semi Bold | 32px | Auto | 0 |
| Headlines/H3 | `e51050207ddff0a20d1b1dae80bddbd5b34d4fb2` | Inter | Semi Bold | 24px | 30px | 0 |
| Headlines/H4 | `5773e80e10f3396d8da80218ae0e7799637c42e3` | Inter | Semi Bold | 20px | 24px | 0 |
| Headlines/H5 | `be57224f7a8d40f6fb33855456c324c6fdc58adc` | Inter | Semi Bold | 18px | 22px | 0 |
| Headlines/H6 | `5a352759b8b34ada73a6715ccfe6649bd09b8f9b` | Inter | Semi Bold | 16px | 20px | 0 |
| Body/Subtitle 1 | `51e124811b05455ba4ec2170c2d7d17c606e9850` | Inter | Semi Bold | 14px | 20px | 0 |
| Body/Subtitle 2 | `28ab09c4e20e68276cb6afa9877e62e523225126` | Inter | Semi Bold | 12px | 16px | 0 |
| Body/Subtitle 3 | `d83f1df53b390782a1002c0288f1179081395c9b` | Inter | Semi Bold | 10px | 12px | 0 |
| Body/Body 1 | `dd4a720e10df4ebca0fc96607ae81effb512009e` | Inter | Regular | 14px | 20px | 0 |
| Body/Body 2 | `3ec92fcb0c18950b4de40b4b0481d6411327af2f` | Inter | Regular | 16px | 20px | 0 |
| Body/Body 3 | `540b559794ca7eb23631093b727eddd1d41c14b7` | Inter | Regular | 12px | 16px | 0 |
| Body/Body 4 | `0141e7b3527e7438234bf07bc7279158bf13fc60` | Inter | Regular | 10px | 12px | 0 |
| Body/Body 5 | `e0738f6314e70a6ed9eceeed331fde5c1beccb48` | Inter | Regular | 18px | 22px | 0 |
| Button/Button Lg | `b6c68ad0728e0962f7eff37555924827bfac9083` | Inter | Medium | 16px | 22px | 0 |
| Button/Button Md | `58875ab6a77d036883addb9473f4272de6575482` | Inter | Medium | 14px | 20px | 0 |
| Button/Button Sm | `82dceb66c8f9c997c24907889defda24a24388e6` | Inter | Medium | 14px | 20px | 0 |
| Button/Button XS | `456336493d842efb5ab06a3f70e1f21d91c2a192` | Inter | Medium | 12px | 16px | 0 |
| Input Fields/Label Text | `cb08c2a7d6c5a22cf69315673c6bd2c083572323` | Inter | Semi Bold | 12px | 16px | 0 |
| Input Fields/Default Text | `a3cd3ef68c4573e1188d8ebb2ddf35e78de70421` | Inter | Regular | 14px | 20px | 0 |
| Input Fields/Small Text | `2e582897730de10494722094148a39d67677215b` | Inter | Regular | 14px | 20px | 0 |
| Input Fields/Extra Small Text | `6fd9460657f2f821c73f5db5c0bdff165294b11a` | Inter | Regular | 12px | 16px | 0 |
| Code Text/Code Body | `ea2637050ab70296a1ea8e78fae48b9788150f14` | Roboto Mono | Regular | 12px | 20px | 0 |
| Code Text/Code Subtitle | `9ed93cca872f5a56852b94df2c84472480ea2c02` | Roboto Mono | SemiBold | 12px | 20px | 0 |
| Service Heading/Service Heading | `fa3a3f0ae2cde538a491578bc08f45793bd43fc8` | Inter | Semi Bold | 10px | 12px | 16% |

> **Note:** Text style keys above are full bare keys, ready for `importStyleByKeyAsync(key)`.

---

## Color Variables — Mode Collection

503 total color variables across Mode + Theme collections.
Variables with *(theme)* have no resolved hex — they are **theme aliases** (bound to Theme collection).

> **Note:** Color variable keys below are truncated for readability. For full importable keys, see [Full Variable Key Reference](#full-variable-key-reference) at bottom.

### ACCORDION (14)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Background/Default | `e7a40947c5db…` | → BODY/Text/Static/White | #1A1B1D |
| Background/Hover | `f91de10dff9a…` | #FBFBFB | #1E1F21 |
| Background/Hover 2 | `8cece6799fec…` | → _Light-Colors/_Primary/Primary-4 | → _Dark-Colors/_Primay/Primary-4 |
| Background/Active | `5ff3ad66cf66…` | #F4F7FE | #242527 |
| Background/Disable | `cb1eee83ace8…` | #F7F8FB | #242424 |
| Background/Open Bg | `441bcee163ab…` | #FFFFFF | #1A1B1D |
| Background/Icon Bg | `dcf5f5308602…` | #EBEEF6 | #2F3136 |
| Text & Icon/Default | `dd5fbe76e7f4…` | #101F3E | #EEEEEE |
| Text & Icon/Secondary | `60c5b3b0439b…` | #4D618A | #AAAAAA |
| Text & Icon/Disable | `a2706d3524d2…` | #A6B1C9 | #666666 |
| Text & Icon/Secondary Dropdown | `3340e114743e…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Text & Icon/Secondary Dropdown Hover | `10d3479d2220…` | → _Light-Colors/_Primary/Primary-2 | → _Dark-Colors/_Primay/Primary-2 |
| Border/Default | `c499a100e538…` | #EBEEF6 | #2F3136 |
| Border/Disable | `3cac3c1d2eeb…` | #EFF2FA | #292A2F |

### ATTENTION (25)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Info/Background | `d62baa85304c…` | #E8F5FF | #1B2730 |
| Info/Border | `e2351aef06d3…` | #A6CBEA | #2B4254 |
| Info/Text Primary | `dc4a3525cc1f…` | #101F3E | #EEEEEE |
| Info/Text Secondary | `f8704ce97378…` | #4D618A | #AAAAAA |
| Info/Icon | `0de5021d72e7…` | #101F3E | #EEEEEE |
| Danger/Background | `424e1b41141a…` | #FFEFEF | #2C2123 |
| Danger/Border | `71c0377f3444…` | #EE7979 | #682B2D |
| Danger/Text Primary | `a42bde4fc260…` | #101F3E | #EEEEEE |
| Danger/Text Secondary | `2ba40dc770b3…` | #4D618A | #AAAAAA |
| Danger/Icon | `160a3b21ddf5…` | #101F3E | #EEEEEE |
| Success/Background | `b4d29fdf80ad…` | #EAF7EF | #1C2622 |
| Success/Border | `6757574ac37b…` | #7FD1A0 | #2F4326 |
| Success/Text Primary | `0d29ecb2f606…` | #101F3E | #EEEEEE |
| Success/Text Secondary | `705df56cd9e6…` | #4D618A | #AAAAAA |
| Success/Icon | `6de3412e5594…` | #101F3E | #EEEEEE |
| Warning/Background | `dd1e11ec5d49…` | #FFF3D7 | #27231C |
| Warning/Border | `a8281aaf031c…` | #DAB45F | #493F07 |
| Warning/Text Primary | `d9dcd7c1625c…` | #101F3E | #EEEEEE |
| Warning/Text Secondary | `13472faee698…` | #4D618A | #AAAAAA |
| Warning/Icon | `6a256d7e5a42…` | #101F3E | #EEEEEE |
| Default/Background | `50bc0bb5cc09…` | #F4F7FE | #242527 |
| Default/Border | `7b4ab38e9604…` | #EBEEF6 | #2F3136 |
| Default/Text Primary | `3b0eac94091c…` | #101F3E | #EEEEEE |
| Default/Text Secondary | `a6697465729a…` | #4D618A | #AAAAAA |
| Default/Icon | `9ceb3067d39d…` | #101F3E | #EEEEEE |

### AVATAR (5)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Bg colors/Default | `601bd9c4b76f…` | #F4F7FE | #242527 |
| Bg colors/Default 2 | `dbfb3659f730…` | #EBEEF6 | #2F3136 |
| Icon/Avatar | `1e94f40c0e84…` | #4D618A | #AAAAAA |
| Borders/Default | `a543012433a3…` | #EBEEF6 | #2F3136 |
| Borders/White | `7f4cb4123419…` | #FFFFFF | #1A1B1D |

### BADGE (22)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Background/Primary | `16089f5b5a3d…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Background/Green | `9ebef43d3e20…` | #29B260 | #3E9F64 |
| Background/Red | `1539e539c598…` | #E22020 | #DE5E60 |
| Background/Pink | `b976cf4d60b8…` | #E417B1 | #DA57B9 |
| Background/Orange | `a7f8a9015ce0…` | #C98E06 | #AE821C |
| Background/Grey | `7896b27087d7…` | #F4F7FE | #242527 |
| Background/Sec- Primary | `26d675e3e49d…` | → _Light-Colors/_Primary/Primary-4 | → _Dark-Colors/_Primay/Primary-4 |
| Background/Sec- Red | `ab8a554f6106…` | #FFEFEF | #2C2123 |
| Background/Sec- Pink | `8b775220af01…` | #FFEFFB | #2D202A |
| Background/Sec- Green | `c3db28c42246…` | #EAF7EF | #1C2622 |
| Background/Sec- Orange | `53df569e80c1…` | #FFF3D7 | #27231C |
| Background/Disable | `9ee3e1165938…` | #F7F8FB | #242424 |
| Text/Primary 1 | `df68fc80638c…` | #FFFFFF | #FFFFFF |
| Text/Sec- Primary | `52b4c9d2f698…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Text/Sec- Green | `4d7d6044e258…` | #29B260 | #3E9F64 |
| Text/Sec- Red | `67d68f487144…` | #E22020 | #DE5E60 |
| Text/Sec- Pink | `8fc6c16bdfa6…` | #E417B1 | #DA57B9 |
| Text/Sec- Orange | `283e16ca793a…` | #C98E06 | #AE821C |
| Text/Grey | `a17a93961c67…` | #101F3E | #EEEEEE |
| Text/Disable | `533300cf27df…` | #A6B1C9 | #666666 |
| Border - Removed in UI/White | `d118d64a3400…` | #FFFFFF | #1A1B1D |
| Border - Removed in UI/Disabled | `89b2609be766…` | #EFF2FA | #292A2F |

### BODY (16)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Background/Static/Container Bg | `a9b4ed83b5ad…` | #FFFFFF | #1A1B1D |
| Background/Static/Body Bg | `8a73e5eb7acb…` | #EFF2FA | #151516 |
| Border/Static/Border | `dee9b282355c…` | #EBEEF6 | #2F3136 |
| Border/Static/OuterDivider | `71abb67e5096…` | #DDE4F6 | #33373F |
| Text/Static/Primary | `923bd06a923f…` | #101F3E | #EEEEEE |
| Text/Static/Secondary | `cbc2c154ea80…` | #4D618A | #AAAAAA |
| Text/Static/Light | `7a19681638a6…` | #7988A8 | #888888 |
| Text/Static/Disable | `34cb78323c44…` | #A6B1C9 | #666666 |
| Text/Static/Theme | `0e6d1bdb08c3…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Text/Static/White | `3b9a2f87cd7c…` | #FFFFFF | #FFFFFF |
| Icons/Static/Primary | `5a84f2ed8100…` | #101F3E | #EEEEEE |
| Icons/Static/Secondary | `4b949396ae94…` | #4D618A | #AAAAAA |
| Icons/Static/Light | `b477aff637a8…` | #7988A8 | #888888 |
| Icons/Static/Disable | `b316d9615de3…` | #A6B1C9 | #666666 |
| Icons/Static/White & Black | `4ff3e20618be…` | #FFFFFF | #1A1B1D |
| Icons/Static/Theme | `ff104a7fb5d3…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |

### BRANDING ICON (2)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Icon Color/Blue | `470ccc11af67…` | #226DB4 | #226DB4 |
| Icon Color/Red | `8fa6ccab91de…` | #E42527 | #E42527 |

### BREADCRUMBS (5)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Background/Hover | `d0087fc1c5be…` | → _Light-Colors/_Primary/Primary-4 | → _Dark-Colors/_Primay/Primary-4 |
| Text & Icon/Default | `9158ef260660…` | #4D618A | #AAAAAA |
| Text & Icon/Hover | `26662bd0d528…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Text & Icon/Active | `42c876859c78…` | #101F3E | #EEEEEE |
| Text & Icon/Disable | `2a8b7855f0c3…` | #A6B1C9 | #666666 |

### BUTTONS (87)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Fill/Background/Primary | `e2c4d82f0655…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Fill/Background/PrimaryHover | `25c9436b505a…` | → _Light-Colors/_Primary/Primary-2 | → _Dark-Colors/_Primay/Primary-2 |
| Fill/Background/PrimaryClick | `78880199cfa7…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Fill/Background/PrimaryDisable | `7f53c83c5553…` | → _Light-Colors/_Primary/Primary-3 | → _Dark-Colors/_Primay/Primary-3 |
| Fill/Background/Success | `3185f64a7231…` | #29B260 | #3E9F64 |
| Fill/Background/SuccessHover | `035790398693…` | #218E4D | #3AA564 |
| Fill/Background/SuccessClick | `b31e2caa9141…` | #29B260 | #3E9F64 |
| Fill/Background/SuccessDisable | `8a04ef60cde9…` | #7FD1A0 | #2F4326 |
| Fill/Background/Danger | `ffdc74496d21…` | #E22020 | #DE5E60 |
| Fill/Background/DangerHover | `db9882600c44…` | #B51A1A | #E86E6B |
| Fill/Background/DangerClick | `3a0a14662a28…` | #E22020 | #DE5E60 |
| Fill/Background/DangerDisable | `02b1a06067cc…` | #EE7979 | #682B2D |
| Fill/Text & Icon/Default | `daed13cae3f4…` | #FFFFFF | #FFFFFF |
| Fill/Text & Icon/Hover | `d0843d6d0711…` | #FFFFFF | #FFFFFF |
| Fill/Text & Icon/Click | `e046c87763b9…` | #FFFFFF | #FFFFFF |
| Fill/Text & Icon/Disable | `8dc9aa5b6d3e…` | #E7EEFE | #FFFFFF |
| Fill/Split/Split_Line | `32ef24ba1b3d…` | #FFFFFF | #FFFFFF |
| Outline/Text & Icons/Primary | `67bb93b0273b…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Outline/Text & Icons/PrimaryHover | `c5c9bb2cc2a9…` | → _Light-Colors/_Primary/Primary-2 | → _Dark-Colors/_Primay/Primary-2 |
| Outline/Text & Icons/PrimaryClick | `e5a47572ead8…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Outline/Text & Icons/PrimaryDisable | `919c17c20bbb…` | → _Light-Colors/_Primary/Primary-3 | → _Dark-Colors/_Primay/Primary-3 |
| Outline/Text & Icons/Success | `6e9e7ff36f35…` | #29B260 | #3E9F64 |
| Outline/Text & Icons/SuccessHover | `f63b5ffa3bc1…` | #218E4D | #3AA564 |
| Outline/Text & Icons/SuccessClick | `41ea272565e7…` | #29B260 | #3E9F64 |
| Outline/Text & Icons/SuccessDisable | `c81ebd719308…` | #7FD1A0 | #2F4326 |
| Outline/Text & Icons/Danger | `42c76df6df6b…` | #E22020 | #DE5E60 |
| Outline/Text & Icons/DangerHover | `f5f4892b4a5a…` | #B51A1A | #E86E6B |
| Outline/Text & Icons/DangerClick | `a1b836582204…` | #E22020 | #DE5E60 |
| Outline/Text & Icons/DangerDisable | `be5a2aa632fb…` | #EE7979 | #682B2D |
| Outline/Borders/Primary | `8b99a5aca59e…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Outline/Borders/PrimaryHover | `aa85eb76fff3…` | → _Light-Colors/_Primary/Primary-2 | → _Dark-Colors/_Primay/Primary-2 |
| Outline/Borders/PrimaryClick | `65f542a75639…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Outline/Borders/PrimaryDisable | `eff766176216…` | → _Light-Colors/_Primary/Primary-3 | → _Dark-Colors/_Primay/Primary-3 |
| Outline/Borders/Success | `093e6e94b358…` | #29B260 | #3E9F64 |
| Outline/Borders/SuccessHover | `367b780fb238…` | #218E4D | #3AA564 |
| Outline/Borders/SuccessClick | `8bcc1560d200…` | #29B260 | #3E9F64 |
| Outline/Borders/SuccessDisable | `752675a1fee5…` | #7FD1A0 | #2F4326 |
| Outline/Borders/Danger | `870ab37dfb27…` | #E22020 | #DE5E60 |
| Outline/Borders/DangerHover | `6a751b93c4ed…` | #B51A1A | #E86E6B |
| Outline/Borders/DangerClick | `ac00f0b25cdf…` | #E22020 | #DE5E60 |
| Outline/Borders/DangerDisable | `b2d6d88e1249…` | #EE7979 | #682B2D |
| Grey/Backgrounds/Default | `5602e445838d…` | #EBEEF6 | #2F3136 |
| Grey/Backgrounds/Hover | `296e785a3e5d…` | → _Light-Colors/_Primary/Primary-4 | #292A2F |
| Grey/Backgrounds/Click | `10e7d4bd6c37…` | #EBEEF6 | #2F3136 |
| Grey/Backgrounds/Disbale | `67b41273dd73…` | #F7F8FB | #242424 |
| Grey/Text & Icons/Default | `e0fbf1503043…` | #101F3E | #EEEEEE |
| Grey/Text & Icons/Hover | `e260f04641c1…` | #101F3E | #EEEEEE |
| Grey/Text & Icons/Click | `efa1cb232023…` | #101F3E | #EEEEEE |
| Grey/Text & Icons/Disable | `ab64cc5ea3ff…` | #A6B1C9 | #666666 |
| Grey/Borders/Default | `5fd40c21c79e…` | #D6DDEF | #484D58 |
| Grey/Borders/Hover | `650ebe909e9e…` | #D6DDEF | #484D58 |
| Grey/Borders/Click | `3de259e96f4d…` | #D6DDEF | #484D58 |
| Grey/Borders/Disabled | `5a4e6f0d6476…` | #EFF2FA | #292A2F |
| Ghost/Backgrounds/Primary | `4942361d7f20…` | → _Light-Colors/_Primary/Primary-4 | → _Dark-Colors/_Primay/Primary-4 |
| Ghost/Backgrounds/Success | `8c7ab5ac43fc…` | #EAF7EF | #1C2622 |
| Ghost/Backgrounds/Danger | `e1ded229a1d8…` | #FFEFEF | #2C2123 |
| Ghost/Text & Icons/PrimaryDefault | `4fcb75f8287b…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Ghost/Text & Icons/PrimaryHover | `4f204f4ac7ae…` | → _Light-Colors/_Primary/Primary-2 | → _Dark-Colors/_Primay/Primary-2 |
| Ghost/Text & Icons/PrimaryClick | `0020665c8b03…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Ghost/Text & Icons/PrimaryDisable | `4890e731ab2b…` | → _Light-Colors/_Primary/Primary-3 | → _Dark-Colors/_Primay/Primary-3 |
| Ghost/Text & Icons/SuccessDefault | `66d6d00f1b10…` | #29B260 | #3E9F64 |
| Ghost/Text & Icons/SuccessHover | `331cb3515702…` | #218E4D | #3AA564 |
| Ghost/Text & Icons/SuccessClick | `386a5327b352…` | #29B260 | #3E9F64 |
| Ghost/Text & Icons/SuccessDisable | `4223a0365d1f…` | #7FD1A0 | #2F4326 |
| Ghost/Text & Icons/DangerDefault | `db6eeab9e3da…` | #E22020 | #DE5E60 |
| Ghost/Text & Icons/DangerHover | `30f80012aa96…` | #B51A1A | #E86E6B |
| Ghost/Text & Icons/DangerClick | `906d9261513d…` | #E22020 | #DE5E60 |
| Ghost/Text & Icons/DangerDisable | `0d0d8ed0e02e…` | #EE7979 | #682B2D |
| Link/Text & Icon/Default | `62034abc503b…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Link/Text & Icon/Hover | `57183c1b7e2f…` | → _Light-Colors/_Primary/Primary-2 | → _Dark-Colors/_Primay/Primary-2 |
| Link/Text & Icon/Click | `0456b52e177f…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Link/Text & Icon/Disable | `1b4ee9083e14…` | → _Light-Colors/_Primary/Primary-3 | → _Dark-Colors/_Primay/Primary-3 |
| Outline/Bg/PrimaryHover | `24c01c3bf8ac…` | → _Light-Colors/_Primary/Primary-4 | → _Dark-Colors/_Primay/Primary-4 |
| Outline/Bg/SuccessHover | `9fa3619c27be…` | #EAF7EF | #1C2622 |
| Outline/Bg/DangerHover | `51138d0fa076…` | #FFEFEF | #2C2123 |
| Gradient/Text & Icon/Default | `a88688946431…` | #101F3E | #FFFFFF |
| Gradient/Text & Icon/Hover | `9ba9b7fe49c2…` | #101F3E | #FFFFFF |
| Gradient/Text & Icon/Click | `b3048b7f5640…` | #101F3E | #FFFFFF |
| Gradient/Text & Icon/Disable | `0eb818b05e70…` | #A6B1C9 | #FFFFFF |
| Gradient/Bg/Gradient top | `b0404896c72b…` | #FFE1FB | #46224A |
| Gradient/Bg/Gradient bottom | `a3fac0c1a823…` | #C4E7FD | #08293E |
| Gradient/Bg/Gradient top hover | `d21ab45a3109…` | #FFD2F9 | #520D49 |
| Gradient/Bg/Gradient bottom hover | `3133834772b6…` | #B5DDF6 | #2B4B5E |
| Gradient/Bg/Gradient top Click | `4407556520ff…` | #FFE1FB | #46224A |
| Gradient/Bg/Gradient bottom Click | `3bdb4ad76db3…` | #C4E7FD | #08293E |
| Gradient/Bg/Gradient top Disable | `54b59c9aeb6f…` | #FFEFFD | #493546 |
| Gradient/Bg/Gradient bottom Disable | `fa430711322e…` | #DCF2FF | #29333A |

### CARDS (22)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Bg Default/Primary | `5f31ffd455f6…` | #FFFFFF | #1A1B1D |
| Bg Default/Secondary | `33799101f4d8…` | #FBFBFB | #1E1F21 |
| Bg Default/Teritaroy | `02db6ed6bf18…` | #F4F7FE | #242527 |
| Bg Default/Quaternary | `ba00e89b5c71…` | #EFF2FA | #292A2F |
| Bg Default/Body Bg | `f792049ac254…` | #F7FAFF | #1F2022 |
| Bg Default/Dark Bg | `49bff2d18147…` | #0F2A64 | #1F2022 |
| Bg Hovers/Primary - Hover | `c09f2fa81ddc…` | #FBFBFB | #1E1F21 |
| Bg Hovers/Secondary - Hover | `a141afdd531a…` | #F4F7FE | #242527 |
| Bg Hovers/Teritaroy - Hover | `01984f650dc5…` | #F7FAFF | #1F2022 |
| Bg Hovers/Quaternary - Hover | `ec7cd6cb5bff…` | #F4F7FE | #242527 |
| Bg Hovers/Body Bg - Hover | `21118e62127f…` | #F4F7FE | #242527 |
| Bg Selected/Primary - Selected | `9aae47b19f9b…` | → _Light-Colors/_Primary/Primary-4 | → _Dark-Colors/_Primay/Primary-4 |
| Bg Selected/Secondary - Selected | `c17dd566b39a…` | → _Light-Colors/_Primary/Primary-4 | → _Dark-Colors/_Primay/Primary-4 |
| Bg Selected/Teritaroy - Selected | `83efef3800b0…` | → _Light-Colors/_Primary/Primary-4 | → _Dark-Colors/_Primay/Primary-4 |
| Bg Selected/Quaternary - Selected | `63867f0f5b73…` | → _Light-Colors/_Primary/Primary-4 | → _Dark-Colors/_Primay/Primary-4 |
| Bg Selected/Body Bg - Selected | `af02b2b4cbef…` | → _Light-Colors/_Primary/Primary-4 | → _Dark-Colors/_Primay/Primary-4 |
| Bg Disabled/Disable | `7d80663ea944…` | #F7F8FB | #242424 |
| Borders/Default | `511f1c301280…` | #EBEEF6 | #2F3136 |
| Borders/Hover | `bacf7f302ae4…` | #DDE4F6 | #33373F |
| Borders/Selected | `fab6eed58da5…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Borders/Disable | `0b1eca41bb43…` | #EFF2FA | #292A2F |
| Borders/White | `b9620d5eae45…` | #FFFFFF | #1A1B1D |

### CAROUSAL (3)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Carosual default | `bbe5c3c7ccbd…` | #A6B1C9 | #666666 |
| Carosual hover | `93b4135fe0f6…` | #4D618A | #AAAAAA |
| Carosual Active | `21b274f1af2f…` | #101F3E | #EEEEEE |

### CHECK, RADIO, TOGGLE (19)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Backgrounds/Default | `b50f3793697d…` | #FFFFFF | #1A1B1D |
| Backgrounds/Hover | `735a4b18a925…` | → _Light-Colors/_Primary/Primary-4 | #292A2F |
| Backgrounds/Disbale | `503bf43f7928…` | #F7F8FB | #242424 |
| Backgrounds/Click | `f345fd3bda8f…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Backgrounds/Click Hover | `c1598d2ccb46…` | → _Light-Colors/_Primary/Primary-2 | → _Dark-Colors/_Primay/Primary-2 |
| Backgrounds/Click Disable | `6dd0ce21a5d8…` | → _Light-Colors/_Primary/Primary-3 | → _Dark-Colors/_Primay/Primary-3 |
| Inner For Check/White | `f782fce2c988…` | #FFFFFF | #EEEEEE |
| Inner For Toggle/Active | `66144ecdaf00…` | #FFFFFF | #EEEEEE |
| Inner For Radio/White | `707e9ebfd565…` | #FFFFFF | #EEEEEE |
| Inner For Radio/Disable | `2ed99d3d5c6b…` | #E7EEFE | #FFFFFF |
| Inner For Toggle/Active Disable | `16ce9443f70a…` | #E7EEFE | #FFFFFF |
| Inner For Toggle/Default | `f22bb5b116d4…` | #D6DDEF | #484D58 |
| Inner For Toggle/Hover | `4b6ad946463a…` | → _Light-Colors/_Primary/Primary-3 | → _Dark-Colors/_Primay/Primary-3 |
| Inner For Toggle/Disabled | `4434ed899077…` | #EBEEF6 | #2F3136 |
| Inner For Check/Disable | `33fbc5b73c3f…` | #E7EEFE | #FFFFFF |
| Borders/Default | `f30e4aa3a3bd…` | #D6DDEF | #484D58 |
| Borders/Hover | `e82732a47acc…` | → _Light-Colors/_Primary/Primary-3 | → _Dark-Colors/_Primay/Primary-3 |
| Borders/Disabled | `9f8dbb4b1eed…` | #EFF2FA | #292A2F |
| Borders/Outer Border radio | `46604bfb744d…` | #EBEEF6 | #2F3136 |

### CHIPS (12)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Background/Default | `66043fc5aded…` | #F4F7FE | #242527 |
| Background/Hover | `0ead6b920f4e…` | #F7FAFF | #2F3136 |
| Background/Disable | `56317bc6dfa9…` | #F7F8FB | #242424 |
| Borders/Default | `8d25e25ce197…` | #EBEEF6 | #2F3136 |
| Borders/Hover | `2e772c15d81b…` | #D6DDEF | #484D58 |
| Borders/Disable | `18ef846995bb…` | #EFF2FA | #292A2F |
| Text/Default | `8440e0ab23fd…` | #101F3E | #EEEEEE |
| Text/Hover | `76464ed724fd…` | #101F3E | #EEEEEE |
| Text/Disable | `e5b1cfe520b4…` | #A6B1C9 | #666666 |
| Icons/Active | `e1bd64b98e80…` | #101F3E | #EEEEEE |
| Icons/Hover | `2e08ccf1e7bb…` | #101F3E | #EEEEEE |
| Icons/Disable | `df7392f260ac…` | #A6B1C9 | #666666 |

### CODE BLOCK (3)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Bg colors/Writer | `c728f4e5b32b…` | #FFFFFF | #1A1B1D |
| Bg colors/Reader | `2307f7211812…` | #F7F8FB | #242527 |
| Borders/Default | `6f99fdb09667…` | #EBEEF6 | #2F3136 |

### DATE PICKER (12)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Background/Datepicker Bg | `be52fe1a691a…` | #FFFFFF | #1A1B1D |
| Background/Number Hover | `cf965cc3ed5c…` | #F4F7FE | #292A2F |
| Background/Number Selected | `ee9b8fb2b55d…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Background/Number Active | `750d81fd1ef4…` | → _Light-Colors/_Primary/Primary-4 | → _Dark-Colors/_Primay/Primary-4 |
| Borders/Outer | `9bec599768a7…` | #D6DDEF | #484D58 |
| Borders/Line | `04f1a3a99fce…` | #EBEEF6 | #2F3136 |
| Text/Default | `2f4bfc9d1769…` | #101F3E | #EEEEEE |
| Text/Selected | `3214d0a66d82…` | #FFFFFF | #FFFFFF |
| Text/Active | `d461dbd4816f…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Text/Disabled | `9ddea429f6b5…` | #A6B1C9 | #666666 |
| Text/Days | `7cdf0ca0675e…` | #7988A8 | #888888 |
| Text/Headings | `8527bddb8586…` | #101F3E | #EEEEEE |

### FULL PAGE POPUP HEADER (4)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Bg/Bg | `bef107aa3960…` | #F4F7FE | #292A2F |
| Bg/Bg 2 | `bcfd72e1a8d9…` | #FFFFFF | #1A1B1D |
| Border/Border 1 | `f5c07b6f0289…` | #DDE4F6 | #33373F |
| Text/Text | `29e235fe4e89…` | #101F3E | #EEEEEE |

### GRAPH (5)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Text/Text 1 | `ba4feaa74a43…` | #101F3E | #EEEEEE |
| Text/Text 2 | `80c1424f1192…` | #4D618A | #AAAAAA |
| Text/Text 3 | `a342398d7633…` | #7988A8 | #888888 |
| Lines/X&Y Axis | `b9c1eded6a48…` | #DDE4F6 | #33373F |
| Lines/Line 2 | `cd6ccd0bcd30…` | #EBEEF6 | #2F3136 |

### INPUT_FIELDS (26)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Background/Default | `6f89da5af840…` | #FFFFFF | #1A1B1D |
| Background/Hover | `e0c7191406fd…` | #F7FAFF | #1F2022 |
| Background/Active | `3bfdb15889db…` | #F7FAFF | #1F2022 |
| Background/Disable | `c9bad27be574…` | #F7F8FB | #242424 |
| Background/Error | `f35c691f188c…` | #FFEFEF | #2C2123 |
| Background/Link field Hover | `02ea99f92375…` | #F7FAFF | #1F2022 |
| Borders/Default | `64da02967013…` | #D6DDEF | #484D58 |
| Background/Key value hover | `6fe2e42911f5…` | #F4F7FE | #242527 |
| Borders/Hover | `a0e498137999…` | → _Light-Colors/_Primary/Primary-3 | → _Dark-Colors/_Primay/Primary-3 |
| Borders/Active | `c5aeea2b09a0…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Borders/Disable | `c2c17970c911…` | #EFF2FA | #292A2F |
| Borders/Error | `819a284b0c14…` | #EE7979 | #682B2D |
| Text/Place Holder | `e21567fc5e8a…` | #7988A8 | #888888 |
| Text/Active | `1a965815e3b0…` | #101F3E | #EEEEEE |
| Text/Disable | `ce2304800792…` | #A6B1C9 | #666666 |
| Text/Label | `6d7ff5416229…` | #4D618A | #AAAAAA |
| Text/Link field | `47cc0c93b5a1…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Text/Link field Hover | `39e7d9414356…` | → _Light-Colors/_Primary/Primary-2 | → _Dark-Colors/_Primay/Primary-2 |
| Text/Link Field Active | `1bbb5a756322…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Text/Link field disabled | `d320dee7ffdc…` | → _Light-Colors/_Primary/Primary-3 | → _Dark-Colors/_Primay/Primary-3 |
| Text/Optional text | `74901cd5f417…` | #7988A8 | #888888 |
| Text/Error Text | `58859395c7f4…` | #E22020 | #DE5E60 |
| Icons/Place Holder | `d19e728d0ab5…` | #7988A8 | #888888 |
| Icons/Active | `885567f6f9b9…` | #101F3E | #EEEEEE |
| Icons/Disable | `307e661335a6…` | #A6B1C9 | #666666 |
| Icons/Label | `582e9d8e2d9d…` | #4D618A | #AAAAAA |

### LINK BOX (12)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Background/Default | `fd3c75cd32e7…` | #F4F7FE | #242527 |
| Background/Hover | `154fed6aba00…` | #EFF2FA | #292A2F |
| Borders/Default | `1abe07c80a3a…` | #EBEEF6 | #2F3136 |
| Borders/Divider | `d57247d806a8…` | #D6DDEF | #484D58 |
| Borders/Hover | `89594295463f…` | → _Light-Colors/_Primary/Primary-3 | → _Dark-Colors/_Primay/Primary-3 |
| Text/Label 1 | `84515f65759a…` | #4D618A | #AAAAAA |
| Text/Label 2 | `c66004599043…` | #101F3E | #EEEEEE |
| Text/Main Text | `b45c9d749256…` | #101F3E | #EEEEEE |
| Icons/Label | `9c21cad84263…` | #4D618A | #AAAAAA |
| Icons/Default | `c5b147461232…` | #101F3E | #EEEEEE |
| Icons/Hover | `c2fbe14f0d8f…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Icons/Click | `2807479ad260…` | #101F3E | #EEEEEE |

### LOADER (7)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Content Loader/Primary | `7a3a0cef901d…` | #D6DDEF | #2F3136 |
| Content Loader/Secondary | `014f7d2521c8…` | #F7FAFF | #1F2022 |
| Round Loader/Primary | `a16236e20b8a…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Round Loader/Secondary | `d4dd59c908e5…` | #101F3E | #EEEEEE |
| Round Loader/Teritory | `580efb0db33b…` | #FFFFFF | #1A1B1D |
| Progress Loader/Primary | `c96cf9dc66f8…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Progress Loader/Primary 2 | `cc11ccf9893b…` | #EBEEF6 | #2F3136 |

### MAIN HEADER (5)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Bg/Bg | `547d945988fb…` | #FFFFFF | #1A1B1D |
| Project Name Logo/Bg | `79286b939d75…` | #EAF7EF | #1C2622 |
| Project Name Logo/Text | `292e51342d60…` | #29B260 | #3E9F64 |
| Border/Border 1 | `ad241d93ce1a…` | #DDE4F6 | #33373F |
| Text/Project text | `32cb2565a994…` | #101F3E | #EEEEEE |

### MENU LIST (14)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Background/Default | `fe46b30affd9…` | #FFFFFF | #1A1B1D |
| Background/List Hover | `664a9eeb7fb8…` | #F4F7FE | #292A2F |
| Background/List Selected | `0a4da841b9b5…` | → _Light-Colors/_Primary/Primary-4 | → _Dark-Colors/_Primay/Primary-4 |
| Background/Disable | `574364053a3d…` | #F7F8FB | #242424 |
| Borders/Border | `9ab6624a6fe2…` | #EBEEF6 | #2F3136 |
| Text/Default | `d7ac65ea1b5a…` | #101F3E | #EEEEEE |
| Text/Hover | `2e656314705b…` | #101F3E | #EEEEEE |
| Text/Disable | `5d9b846e23b2…` | #A6B1C9 | #666666 |
| Text/Heading | `d1183de6a945…` | #4D618A | #AAAAAA |
| Text/Light text | `ed36b88552e5…` | #7988A8 | #888888 |
| Icons/Active | `af23c7e39591…` | #101F3E | #EEEEEE |
| Icons/Hover | `2e444e407ff3…` | #101F3E | #EEEEEE |
| Icons/Disable | `305a5690287b…` | #A6B1C9 | #666666 |
| Icons/Check deafult | `2e8cb6a1810c…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |

### OTHER SHADES (28)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Red/Red 1 | `7da69489ce9f…` | #E22020 | #DE5E60 |
| Red/Red 2 | `3ea1defe4bb3…` | #B51A1A | #E86E6B |
| Red/Red 3 | `c736accff700…` | #EE7979 | #682B2D |
| Red/Red 4 | `5dc42d49093c…` | #FFEFEF | #2C2123 |
| Green/Green 1 | `c5b468027686…` | #29B260 | #3E9F64 |
| Theme/Theme 1 | `ce98fc917009…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Theme/Theme 2 | `724edb6d5136…` | → _Light-Colors/_Primary/Primary-2 | → _Dark-Colors/_Primay/Primary-2 |
| Theme/Theme 3 | `0efe8122b8b2…` | → _Light-Colors/_Primary/Primary-3 | → _Dark-Colors/_Primay/Primary-3 |
| Theme/Theme 4 | `73e778f18003…` | → _Light-Colors/_Primary/Primary-4 | → _Dark-Colors/_Primay/Primary-4 |
| Green/Green 2 | `40849375c329…` | #218E4D | #3AA564 |
| Green/Green 3 | `9cafffd78462…` | #7FD1A0 | #2F4326 |
| Green/Green 4 | `f83e51966951…` | #EAF7EF | #1C2622 |
| Blue/Blue 1 | `95d832925658…` | #2092EF | #4A8EFF |
| Blue/Blue 2 | `c1004017436b…` | #257EC7 | #2E88D1 |
| Blue/Blue 3 | `bda60cd8938d…` | #A6CBEA | #2B4254 |
| Blue/Blue 4 | `2b11eff9da2d…` | #E8F5FF | #1B2730 |
| Pink/Pink 1 | `885bdc052f6b…` | #E417B1 | #DA57B9 |
| Pink/Pink 2 | `8f24525c312d…` | #C51D9B | #CD75B8 |
| Pink/Pink 3 | `b62095d1546e…` | #F8B4E7 | #542F4B |
| Pink/Pink 4 | `3498a4485c80…` | #FFEFFB | #2D202A |
| Orange/Orange 1 | `d1a680043888…` | #C98E06 | #AE821C |
| Orange/Orange 2 | `828eb10cc3e1…` | #A5760C | #A1874B |
| Orange/Orange 3 | `a8c2574fd9a0…` | #DAB45F | #493F07 |
| Orange/Orange 4 | `196dd6808474…` | #FFF3D7 | #27231C |
| Purple/Purple 1 | `09b0d27004fc…` | #6E3D9E | #AD7FE4 |
| Purple/Purple 2 | `d4b9920aceae…` | #7449A4 | #B985F8 |
| Purple/Purple 3 | `da31cc0cd2ae…` | #BDA3DF | #563973 |
| Purple/Purple 4 | `d35755f99574…` | #F1EAFF | #292130 |

### PAGINATION (6)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Bg/Background | `8f22741a5c3f…` | #FFFFFF | #1A1B1D |
| Bg/Text Primary | `3d687051bfa5…` | #101F3E | #EEEEEE |
| Bg/Text Secondary | `9c27e51dc44c…` | #4D618A | #AAAAAA |
| Bg/Text Teritory | `e22a0b52a671…` | #7988A8 | #888888 |
| Bg/Theme | `c2bf50dd3c9b…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Bg/Divider | `445381ab8550…` | #EBEEF6 | #2F3136 |

### POPUP (4)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Border/Border | `c8300c44a50f…` | #EBEEF6 | #2F3136 |
| Border/OuterBorder | `b489c5076d84…` | #EBEEF6 | #2F3136 |
| Bg/Bg | `25df50a797f0…` | #FFFFFF | #1A1B1D |
| Blur Layer/Bg | `993165bacaa0…` | #101F3E | #000000 |

### PROFILE NAV (19)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Background/Profile Area | `fcae28ef23fe…` | #F4F7FE | #242527 |
| Background/Appearance Light | `e377bd909439…` | #F7F8FB | #F7F8FB |
| Background/Bg Appearance Light | `800ef8dc95a9…` | #FFFFFF | #FFFFFF |
| Background/Line Light 1 | `099b41538332…` | #D6DDEF | #D6DDEF |
| Background/Bg Appearance Light 2 | `eaed157a68e5…` | #EFF2FA | #EFF2FA |
| Background/Line Dark 1 | `a2b463796c04…` | #484D58 | #484D58 |
| Background/Bg Appearance Dark 1 | `1357acb5153a…` | #292A2F | #292A2F |
| Background/Appearance Dark | `01a52ea238c6…` | #242424 | #242424 |
| Background/Bg Appearance Dark | `b2dadeb1c2fb…` | #1A1B1D | #1A1B1D |
| Background/Theme | `786638a078e1…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Background/Theme 2 | `7ff47c93bcc0…` | #E417B1 | #DA57B9 |
| Background/Whilte | `9e5e229638e7…` | #FFFFFF | #FFFFFF |
| Borders/Border | `6a21278d173c…` | #EBEEF6 | #2F3136 |
| Borders/Outer border | `a1675c47acce…` | #D6DDEF | #484D58 |
| Text/Heading | `9cc4b2079e29…` | #101F3E | #EEEEEE |
| Text/Sub Text | `92ab28854c2b…` | #4D618A | #AAAAAA |
| Icons/Light | `729542a5383a…` | #7988A8 | #888888 |
| Icons/Whilte | `24a55028a306…` | #FFFFFF | #FFFFFF |
| Icons/Primary | `98dfb3718420…` | #101F3E | #EEEEEE |

### SERVICE_MENU (9)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Background/ServiceMenuTop | `35c328fafaf8…` | #0F2A64 | #151516 |
| Background/ServiceMenuBottom | `c0a7d098282e…` | #0A245D | #151516 |
| Background/Icon Bg Default | `cc64bcbb0cf2…` | → _Light-Colors/_Primary/Primary -20% | #242527 |
| Background/Icon Bg Active | `34e1b91449d2…` | → _Light-Colors/_Primary/Primary-4 | #242527 |
| Borders/Side Border | `b8513a014773…` | #4D618A | #33373F |
| Icons/Service icon Default | `6e2dbd99ba5f…` | #FFFFFF | #FFFFFF |
| Text/Sub Heading | `1a241e39e36a…` | #4D618A | #AAAAAA |
| Text/Default | `c029d706a612…` | #FFFFFF | #FFFFFF |
| Text/Active | `174bb7a20438…` | #101F3E | #EEEEEE |

### SHADOWS (2)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Background/Default | `9087ddd60b49…` | #EFF2FA | #292A2F |
| Background/With Opacity | `815cca3b157d…` | #EFF2FA | #292A2F |

### SIDE MENU (10)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Background/Sidemenu Bg | `eee914c636e1…` | → BODY/Text/Static/White | #1A1B1D |
| Background/Menu Hover | `ce2bab60ba07…` | #F4F7FE | #292A2F |
| Background/Menu Active | `143b5caf6af6…` | → _Light-Colors/_Primary/Primary-4 | → _Dark-Colors/_Primay/Primary-4 |
| Text & Icon/Default | `0c9c338f9336…` | #101F3E | #AAAAAA |
| Text & Icon/Hover | `26e694943442…` | → _Light-Colors/_Primary/Primary-1 | #EEEEEE |
| Text & Icon/Active | `a603977717f6…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Text & Icon/Disable | `fc1b2400830a…` | #A6B1C9 | #666666 |
| Text & Icon/Sub Heading | `f5af51bde7bd…` | #7988A8 | #666666 |
| Text & Icon/Service Name | `5fbe48b7ee43…` | #101F3E | #EEEEEE |
| Borders/Default | `f2a52ab89f98…` | #DDE4F6 | #33373F |

### STEPPER (17)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Bg colors/Default | `5bcda7175a9d…` | #F4F7FE | #242527 |
| Bg colors/Active | `b3926f9d4984…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Bg colors/Completed | `3683a86ee478…` | #29B260 | #3E9F64 |
| Bg colors/Disable | `30a4113b98e8…` | #F7F8FB | #242424 |
| Text/Default | `78a33196e051…` | #4D618A | #AAAAAA |
| Text/Sub Text | `5fde63884a39…` | #4D618A | #AAAAAA |
| Text/Active | `a80bf1f7f4dd…` | #101F3E | #EEEEEE |
| Text/Completed | `150c79ac6d7f…` | #101F3E | #EEEEEE |
| Text/Disable | `a048c6a61180…` | #A6B1C9 | #666666 |
| Text/Numbers | `ba20773e04ae…` | #FFFFFF | #FFFFFF |
| Divider/Default | `f01deeabc27d…` | #D6DDEF | #484D58 |
| Divider/Active | `026886d4cb92…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Divider/Completed | `6c39c4da90c9…` | #3E9F64 | #3E9F64 |
| Divider/Disable | `8e217d8f9402…` | #EFF2FA | #292A2F |
| Borders/Default | `4e7475919a40…` | #D6DDEF | #484D58 |
| Borders/Active | `67393a8a35cd…` | #FFFFFF | #FFFFFF |
| Borders/Disable | `ebe6232bc15c…` | #FFFFFF | #FFFFFF |

### SUB HEADERS (3)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Bg/Bg | `d01fc49e6374…` | #FFFFFF | #1A1B1D |
| Border/Border 1 | `189f79e777bc…` | #DDE4F6 | #33373F |
| Text/Border 1 | `4cc977306cf9…` | #101F3E | #EEEEEE |

### TABLE (18)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Text/Primary | `20b8e89471a8…` | #101F3E | #EEEEEE |
| Text/Secondary | `7f68959b4e43…` | #4D618A | #AAAAAA |
| Text/Light | `e7864ff431bc…` | #7988A8 | #888888 |
| Text/Disable | `7a9b38e510f0…` | #A6B1C9 | #666666 |
| Icons/Primary | `886312b190a3…` | #101F3E | #EEEEEE |
| Icons/Secondary | `7d99de0c3244…` | #4D618A | #AAAAAA |
| Icons/Light | `ce512152afe0…` | #7988A8 | #888888 |
| Icons/Disable | `a53460ff6102…` | #A6B1C9 | #666666 |
| Borders/Default | `12f8dd08bef8…` | #EBEEF6 | #2F3136 |
| Background/Row_Bg | `6d8230c98338…` | #FFFFFF | #1A1B1D |
| Background/Header_Bg | `6c29cc20c8ae…` | #F7F8FB | #1E1F21 |
| Background/Row_Hover_Bg | `955876596ab4…` | #F4F7FE | #242527 |
| Background/Row_Selected_Bg | `0b5550646efc…` | → _Light-Colors/_Primary/Primary-4 | → _Dark-Colors/_Primay/Primary-4 |
| Background/Row_Disabled_Bg | `d476e9059e1f…` | #F7F8FB | #242424 |
| Three_Dot/Icon | `8531d854dde0…` | #101F3E | #EEEEEE |
| Three_Dot/Icon_Bg | `41f973b38a50…` | #F7F8FB | #242424 |
| Three_Dot/Icon_Bg_Hover | `9f074f54532b…` | #EBEEF6 | #2F3136 |
| Three_Dot/Icon_Bg_Active | `643194cf8449…` | → _Light-Colors/_Primary/Primary-4 | → _Dark-Colors/_Primay/Primary-4 |

### TABS (28)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Primary/Background/Hover | `965755385dab…` | → _Light-Colors/_Primary/Primary-4 | → _Dark-Colors/_Primay/Primary-4 |
| Primary/Borders/Default | `f4a1f532c0fa…` | #DDE4F6 | #33373F |
| Primary/Borders/Hover | `74965b821948…` | → _Light-Colors/_Primary/Primary-3 | → _Dark-Colors/_Primay/Primary-3 |
| Primary/Borders/Active | `30a603846777…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Primary/Borders/Disable | `8a2105ec3c9d…` | #EFF2FA | #292A2F |
| Primary/Text & Icon/Default | `f5fc0c507baf…` | #4D618A | #AAAAAA |
| Primary/Text & Icon/Hover | `d2e15c37a44b…` | #101F3E | #EEEEEE |
| Primary/Text & Icon/Active | `ca6d55766091…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Primary/Text & Icon/Disable | `b094ebbe0652…` | #A6B1C9 | #666666 |
| Primary/Background/Disable | `d79dd62c94cf…` | #F7F8FB | #242424 |
| Secondary/Background/Active | `78b052b6a340…` | #FFFFFF | #1F2022 |
| Secondary/Background/Hover | `e42420a1f462…` | #FFFFFF | #292A2F |
| Secondary/Text & Icon/Default | `4fb70763520a…` | #4D618A | #AAAAAA |
| Secondary/Text & Icon/Hover | `95e7577e6b2d…` | #101F3E | #EEEEEE |
| Secondary/Text & Icon/Active | `f3a15a84ceb0…` | → _Light-Colors/_Primary/Primary-1 | #EEEEEE |
| Secondary/Text & Icon/Disable | `25ab611fdc26…` | #A6B1C9 | #666666 |
| Secondary/Background/Disable | `3c5ce580839b…` | #F7F8FB | #242424 |
| Secondary/Background/BG Default | `7fec9035d199…` | #EFF2FA | #33373F |
| Secondary/Border/Default | `aa5903f06837…` | #DDE4F6 | #33373F |
| Code Tab/Background/Active | `250e8bd2d697…` | #FFFFFF | #1F2022 |
| Code Tab/Background/Hover | `bbf8fd0eaf02…` | #FFFFFF | #292A2F |
| Code Tab/Text & Icon/Default | `c95916476958…` | #4D618A | #AAAAAA |
| Code Tab/Text & Icon/Hover | `9ba58d097823…` | #101F3E | #EEEEEE |
| Code Tab/Text & Icon/Active | `76bddc950f85…` | → _Light-Colors/_Primary/Primary-1 | #EEEEEE |
| Code Tab/Text & Icon/Disable | `7a098792c1d9…` | #A6B1C9 | #666666 |
| Code Tab/Background/Disable | `d8dc0b0076a3…` | #F7F8FB | #242424 |
| Code Tab/Background/BG Default | `fcb7968552cd…` | #EFF2FA | #292A2F |
| Code Tab/Border/Default | `75b5e93945da…` | #DDE4F6 | #33373F |

### TIMELINE (11)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Background/Green | `056da3a853ef…` | #EAF7EF | #1C2622 |
| Background/Green Dot | `162e9615f8b2…` | #29B260 | #3E9F64 |
| Background/Orange | `d2e4a3fc41d2…` | #FFF3D7 | #27231C |
| Background/Orange dot | `176c3d86f51c…` | #C98E06 | #AE821C |
| Background/Blue | `2c41a0f65cdf…` | #E8F5FF | #1B2730 |
| Background/Blue Dot | `c8cc67edc1c7…` | #2092EF | #4A8EFF |
| Background/Red | `49c52d0f4462…` | #FFEFEF | #2C2123 |
| Background/Red Dot | `ddde92de0050…` | #E22020 | #DE5E60 |
| Background/Grey | `1360bee496b2…` | #EBEEF6 | #2F3136 |
| Background/Grey Dot | `312d4c73cbed…` | #4D618A | #AAAAAA |
| Line/Default | `315da92de675…` | #D6DDEF | #484D58 |

### TOAST (8)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Default/Background | `7556cc809c5f…` | #FFFFFF | #1A1B1D |
| Default/Border | `f40ad4bda3e5…` | #EBEEF6 | #2F3136 |
| Default/Icon, Line Success | `1169fac02adc…` | #29B260 | #3E9F64 |
| Default/Icon, Line Danger | `4a4203f61a7c…` | #E22020 | #DE5E60 |
| Default/Icon, Line Info | `5b95ca5839f2…` | #2092EF | #4A8EFF |
| Default/Icon, Line Warning | `87144bd21f1d…` | #C98E06 | #AE821C |
| Default/Text Primary | `54b626c9b5bd…` | #101F3E | #EEEEEE |
| Default/Text Secondary | `c5dbd56e8b33…` | #4D618A | #AAAAAA |

### TOOLTIP (4)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Static/Background | `825c222acb6a…` | #101F3E | #2F3136 |
| Static/Text Primary | `81a642904fcc…` | #FFFFFF | #FFFFFF |
| Static/Border | `50bdb8009e65…` | #EBEEF6 | #484D58 |
| Static/Text Secondary | `cebe62e055c6…` | #4D618A | #AAAAAA |

### TOUR (6)

| Variable | Key | Light | Dark |
|---|---|---|---|
| Background/default | `e8b7b291141d…` | #FFFFFF | #1A1B1D |
| Background/Blink bg | `0f91ea3de06f…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Borders/Outer | `a5edfb9be662…` | #EBEEF6 | #2F3136 |
| Borders/Blink Border | `60cde610bc97…` | → _Light-Colors/_Primary/Primary-1 | → _Dark-Colors/_Primay/Primary-1 |
| Text/Heading | `f099aa0ba979…` | #101F3E | #EEEEEE |
| Text/Sub Text | `67c64a0f62ad…` | #4D618A | #AAAAAA |

---

## Color Variables — Theme Collection

10 theme variables. Modes: **Default Royal Blue** / **Purple**.

| Variable | Key | Default Royal Blue | Purple |
|---|---|---|---|
| Default - RoyalBlue/L Primary | `0017910cc3ec…` | #2A65F0 | #6E3D9E |
| Default - RoyalBlue/L Primary 2 | `702c6244c327…` | #0755F2 | #7449A4 |
| Default - RoyalBlue/LPrimary 3 | `50796799a532…` | #7DA2FB | #BDA3DF |
| Default - RoyalBlue/L Primary 4 | `d4a1d439b9fa…` | #E7EEFE | #E9DEFF |
| Default - RoyalBlue/L Primary 20% | `7b68557c4811…` | #2A65F0 | #6E3D9E |
| Default - RoyalBlue/D Primary | `111e066b869b…` | #458BFF | #AD7FE4 |
| Default - RoyalBlue/D Primary 2 | `62e1772fb2f4…` | #5A97FB | #B985F8 |
| Default - RoyalBlue/D Primary 3 | `44bc818f88de…` | #355A8D | #563973 |
| Default - RoyalBlue/D Primary 4 | `98ea108edb80…` | #1A273D | #2B1B3A |
| Default - RoyalBlue/D Primary 20% | `855a0973d201…` | #2074FF | #582B84 |

---

## Full Variable Key Reference

> **Usage**: `await figma.variables.importVariableByKeyAsync(fullKey)`
> Only the ~50 variables used in 90%+ of screen builds are listed. For any other variable find its truncated key in the tables above — the first 8 chars uniquely identify it in the DS file.

### BODY

| VK Alias | Variable | Full Key |
|---|---|---|
| `txtPrimary` | Text/Primary | `923bd06a923fee3c9811bed53c2e1023d667e99f` |
| `txtSecondary` | Text/Secondary | `cbc2c154ea80793b1cc0707f853d43e59a96cf04` |
| `txtLight` | Text/Light | `7a19681638a68e906bddd75586271d7836762473` |
| `txtWhite` | Text/White | `3b9a2f87cd7cb2db22e52bba6c1fe2ba97a31b0e` |
| `txtTheme` | Text/Theme | `0e6d1bdb08c318e876eafd4be5915c3266191fae` |
| `txtDisable` | Text/Disable | `34cb78323c4482bb9ddd65aa567b609282734f7b` |
| `bodyBg` | Background/Body Bg | `8a73e5eb7acb073d9207bddf09a19287115b4cfd` |
| `containerBg` | Background/Container Bg | `a9b4ed83b5ad5b5fe00bc4e56a141e92ad8dae02` |
| `borderDefault` | Border/Border | `dee9b282355cc41a5865a29cc8fc48d6b80484ec` |
| `outerDivider` | Border/OuterDivider | `71abb67e509670e8bc2a18aecd730ae64a7eb0d7` |
| `iconPrimary` | Icons/Primary | `5a84f2ed810016b3efb87e427e84cc49562309fa` |
| `iconSecondary` | Icons/Secondary | `4b949396ae9456a5e3e8c5f211b2904a88ac33c0` |
| `iconTheme` | Icons/Theme | `ff104a7fb5d301d5943d7172ed0beef76aa1fece` |
| `iconLight` | Icons/Light | `b477aff637a8016f87deb55b8d1aa6a43b0f5e6e` |

### CARDS

| VK Alias | Variable | Full Key |
|---|---|---|
| `cardsBgPrimary` | Bg Default/Primary | `5f31ffd455f693c79bb692d089dc99c045508bde` |
| `cardsBgSecondary` | Bg Default/Secondary | `33799101f4d87567229f94849487afeffa6750c0` |
| `cardsBgTertiary` | Bg Default/Teritaroy | `02db6ed6bf18105b51bf83233ba8e4e8a74cd7ac` |
| `cardsBorderDefault` | Borders/Default | `511f1c30128041f0816ec4025aed7cc050584519` |
| `cardsBorderHover` | Borders/Hover | `bacf7f302ae4d0159192d51a810e5912e7f20d89` |

### OTHER SHADES (semantic colors — these import correctly; BADGE/TIMELINE keys do NOT)

| VK Alias | Variable | Full Key |
|---|---|---|
| `theme1` | Theme/Theme 1 | `ce98fc91700925c5828b0649694ce8d694537610` |
| `theme2` | Theme/Theme 2 | `724edb6d513653fe7c756c00ced1f1c64442a62f` |
| `theme3` | Theme/Theme 3 | `0efe8122b8b247c501d7c3b86d7b86778da39c5b` |
| `theme4` | Theme/Theme 4 | `73e778f18003828628514fd853d9c370db0f4ae3` |
| `green1` | Green/Green 1 | `c5b468027686a2c9dc6e05aeac52f132148b8770` |
| `green4` | Green/Green 4 | `f83e5196695146c60ada6141fc9037940c520346` |
| `red1` | Red/Red 1 | `7da69489ce9f98f8ddfb85a66724a1d6d74fb409` |
| `red4` | Red/Red 4 | `5dc42d49093cedf272fbcf74f6da1009406fd2b8` |
| `orange1` | Orange/Orange 1 | `d1a680043888628f6988e070a825a235984cc094` |
| `orange4` | Orange/Orange 4 | `196dd6808474b55bb51f7959f6884c003909651c` |
| `blue1` | Blue/Blue 1 | `95d832925658f8f91a44bb6412c1d3eb2ac85191` |
| `blue4` | Blue/Blue 4 | `2b11eff9da2daccccafb0366cfa08147a754707f` |
| `purple1` | Purple/Purple 1 | `09b0d27004fca34fdd00443ead114b1ee8b43a3e` |
| `purple4` | Purple/Purple 4 | `d35755f99574efc476cc4401744ef612fcae2291` |
| `pink1` | Pink/Pink 1 | `885bdc052f6b6a913b694836d2c63fff40932309` |
| `pink4` | Pink/Pink 4 | `3498a4485c80b7156b74a80af5f9d0e792759554` |

### TABLE

| Variable | Full Key |
|---|---|
| Text/Primary | `20b8e89471a8942a5f9d7be6d7b991dcf3f874d0` |
| Text/Secondary | `7f68959b4e43f477ca3d708b4c70760365ec8a38` |
| Icons/Primary | `886312b190a3856a721c6010b3ccb080382301be` |
| Background/Row_Bg | `6d8230c98338cb82637668ac9aaa8d5de38fe394` |
| Background/Header_Bg | `6c29cc20c8aeced013d0864c4dcce61571621a38` |
| Background/Row_Hover_Bg | `955876596ab47d203c76963f9ab187f598c824e7` |
| Background/Row_Selected_Bg | `0b5550646efc37398b96251e66ea072a62c24411` |
| Borders/Default | `12f8dd08bef851c584bb7c98e7dd08531a8b7fdc` |
| Three_Dot/Icon | `8531d854dde0b8a17cff0b2ad6861cd92df45d52` |
| Three_Dot/Icon_Bg_Hover | `9f074f54532b2b54754d0920077d6efcae05db10` |

### PAGINATION

| Variable | Full Key |
|---|---|
| Bg/Background | `8f22741a5c3fb9b5a499750726ec88a9ec172317` |
| Bg/Text Primary | `3d687051bfa5cde604fc3e5ec013883c9e2e7539` |
| Bg/Text Secondary | `9c27e51dc44ccf667622c7c00163df3e2ade2877` |
| Bg/Text Teritory | `e22a0b52a671f30d0518394095f69134d167eb26` |
| Bg/Theme | `c2bf50dd3c9b7a495bab94d7087678f7ab1f9bc7` |
| Bg/Divider | `445381ab8550bda0a9d8817c60d5748ead26e93e` |
