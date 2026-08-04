# ZCatalyst Design System - Component & Token Registry

**File Key**: `dwQLnT4eJ3zCaOwhk7JXIn`
**Library Name**: ZCatalyst Design System
**CRITICAL**: Do NOT modify this file. READ ONLY.

## Component Sets (59 total) - Key Sets for UI Building

### Layout
- **Component Key**: `60b7dd3df3911d7f99644f1602f94daabc91543a`
- **NodeId**: `1554:19926`
- **Page**: ✅ Catalyst Layouts
- **Usage**: Import via `figma.importComponentByKeyAsync('60b7dd3df3911d7f99644f1602f94daabc91543a')`, create instance, detach top-level, build inside Container
- **Structure**: Layout → Layout with Side menu → ServiceMenu, Right Column (Header, Below Header → Sidemenu, Content Column → Sub Header, Body → Container)

#### Sub Header (inside Layout)
- **Component Key**: `ef423f31a7636493f6d094a031c0a493a94c5667`
- **Type**: Single component (NOT a variant set) — uses 12 boolean properties to toggle elements
- **Boolean Properties**:
  | Property | Default | Shows |
  |---|---|---|
  | Back Navigation | `false` | Ghost button with left arrow |
  | Avatar | `false` | User avatar icon |
  | Primary Tab | `false` | 5 primary tabs below the bar (Tab Text 1–5) |
  | Secondary Tabs | `false` | 5 secondary tabs inline within bar |
  | Help Button | `true` | "Help" button on right |
  | Button 1 | `false` | Action button on right |
  | Button 2 | `false` | Second action button |
  | Button 3 | `false` | Third action button |
  | Menu Button | `false` | Three-dot menu button |
  | Status | `false` | Status badge (text node `"1"`) |
  | Info Icon | `false` | Info icon next to title |
  | Refresh | `false` | Refresh ghost button |
- **Text Nodes**:
  | Element | Node Name | Default Text |
  |---|---|---|
  | Page title | `Feature Names` | "Feature Names" |
  | Status badge | `1` | "Status" |
  | Action buttons (1/2/3) | `Button Text` | "Button Name" |
  | Help button | `Button Text` | "Help" |
  | Secondary tab labels | `Tab Text` | "Tab Text" |
  | Primary tab labels | `Tab Text 1` | "Tab Text 1–5" |

### Buttons
- **Set Key**: `1e04478db049373eb096060a60ee7bbbc4da4e9a`
- **Set NodeId**: `728:4636`
- **Total Variants**: 760
- Variant axes: Type (Default Button, Split Button, Navigation Buttons), Variant (Fill, Outline, Grey, Ghost, Ghost Grey), Size (Default, Small, Extra Small, Large), Color (Primary, Success, Danger, Grey), Content (Default, Icon Button), State (Default, Hover, Disabled, Click)
- Boolean props: `Icon Left`, `Icon Right`
- Instance swap: `Change Icon Left`, `Change Icon Right`
- Text node: `Button Text`
- **Key Variants — Default Button / Default State / Default Radius / Default Content**:
  - Fill/Default/Primary: `30cdc2a5cef8cec1c194d46e4ab7c3670b16703c`
  - Fill/Small/Primary: `1d41188f2c4cbbda525ef438bfb4af56e9b4f6d8`
  - Fill/Large/Primary: `eab731bff757d370583ceb1d60a6762e3f0c1e66`
  - Fill/XS/Primary: `7dac51e9d8051573f6e89b14fc0df4fe39c761d3`
  - Fill/Default/Success: `aaffaad0658f93b5c6a579c4f4a8868ac5808761`
  - Fill/Default/Danger: `a849751b4561433a76f12ea146460863e831cd3f`
  - Outline/Default/Primary: `8a0ada51ba975510e367002fad3fdbf6b1770e93`
  - Outline/Small/Primary: `3ac9534a0d75c6b4f6c38b56cf02f48025b4a7ad`
  - Outline/Default/Success: `6975c2fa0ba6229ac3fef08b015ce2151b2f3161`
  - Outline/Default/Danger: `bd21e6b5caaffd36f537efe493ab15f01384297b`
  - Ghost/Default/Primary: `9f27ac4d4065cd6a5501cca7481f0b0e4bfad4ba`
  - Ghost/Small/Primary: `47859a4a879e25986af3750cc54d2b96dfbb9e98`
  - Grey/Default/Grey: `7d2a9b1131de612203bcd434c3a330161652ae0c`
  - Grey/Small/Grey: `45915b6c2fe55c7380850805255e3db57237019d`
- **Key Variants — Navigation Buttons (Icon Only, Rounded)**:
  - Ghost/Default/Primary: `3d800282879147a494999e7437cef2e2155f7a64`
  - Ghost/Small/Primary: `911dd576b2e232868e3b3fb113fb903c572a8b00`
  - Grey/Default/Grey: `568c3b1a7fb61109ba1bd556f0b0a74e62f0f700`
  - Grey/Small/Grey: `f2d06a63c252d949883e8797ce014cd1a344e009`

### Text Box (Input Fields)
- **Set Key**: `411f52c2e02879cd0cd7a259933325c7cbc04b5c`
- **Set NodeId**: `444:1420`
- **Total Variants**: 30
- Variant axes: Type (Text Field, Text area), State (Default, Hover, Active, Disabled, Completed, Error), Size (Default, Small, Extra Small)
- Boolean props: `optional`, `Label`, `Label Icon`, `Icon Left`, `Icon Right`
- Text nodes: `Text Field` (label), `Enter Label Text` (placeholder)
- **Key Variants — Text Field**:
  - Default/Default: `eec333f0fddc7c20cd07b2827a2240784af309ba`
  - Hover/Default: `46d1239e58dba14b923cdc8971b4321ac90a48cb`
  - Active/Default: `2c65689b42416d9f88482869d0c929f61f715b57`
  - Completed/Default: `88fa0a3db55c4b2791c1ce33749326250f8c51ed`
  - Disabled/Default: `e49adb46b3422c7d608f9accc8c32f9bd2f4f92f`
  - Error/Default: `8e1a050450850ed459a2f93361e8f84dea280938`
  - Default/Small: `63e59487eaa7123f718fd840dd5488f05abb435f`
  - Active/Small: `5e0334442ae5f21bfa3392dca90004a8c24bb0ca`
  - Completed/Small: `a04b2a5f4c43a620740785a3240964acebf29886`
  - Disabled/Small: `100bcc853304884a421a24a5a7df64111ae3b582`
  - Error/Small: `ccc0ea91d409a03d0e076921782cebd29818e70c`
  - Default/XS: `34cc3e9d0d9d7470aa06d56731645b5f259de336`
  - Active/XS: `b5dd747947681cef6dd2ce5022fb54d3f23b4136`
  - Completed/XS: `d5912985542c4a31e313084b564d9ae39d525806`
  - Disabled/XS: `c7aa12de46d499ad036558de9bece7162b2f4355`
  - Error/XS: `365b74b1408e584ff7aae189b4ff10c9425e3bf9`
- **Key Variants — Text Area**:
  - Default/Default: `98c705a12714f754da7bf51d318366f88ad718a2`
  - Hover/Default: `c2a900d1190a590b890bc61490f5e0202bc67284`
  - Active/Default: `c5c659292781d7eff6d6fe4f23972390b204abd4`
  - Completed/Default: `2a089c864f5cd004ea6198466e18af1eb4d616da`
  - Default/Small: `3ea118e354ef4fb1ea3f9d6ba72f95376c581b7d`
  - Active/Small: `f3e4f7fc543d8ce2943bf12c47698aef0441c486`
  - Completed/Small: `2ac2c2986fdd903b79393b9c2a78b9c765a4ea1e`
  - Default/XS: `b73e4bca97dd587964f6a768fb04058d9a2d10c8`
  - Active/XS: `cddda5ec87bf9aacef3d91dc6382af89dddb09a5`

### Link
- **Set Key**: `15293c62ec6b1e82d6635302c34f128a77aa14f7`
- **Set NodeId**: `738:64747`
- **Total Variants**: 16
- Variant axes: Type (Link Text), State (Default, Hover, Click, Disable), Size (Default, Small, Large, Extra Small), Color (Default, Primary)
- Boolean props: `Show Text`, `Show Icon`
- Instance swap: `Change Icon Left`
- Text node: `Button Text`
- **Key Variants**:
  - Default/Default/Primary: `f577977a5f1c87652f614cd38e6364ff7efd53cc`
  - Default/Small/Default: `30e046ce604fd8e018149f8dcb3263d25d88b005`
  - Default/XS/Default: `90fdfa085fdfac262d5cc6b412fb58632e75d036`
  - Default/Large/Default: `d0138028c3a7c212d4e7d975f7fc5d4e21e95115`
  - Hover/Default/Default: `657ec10eac16ad254ce2dfec9d77f32dcf043e9f`
  - Hover/Small/Default: `24ce157885cda882c9497312f17eb2441f970ef8`
  - Hover/XS/Default: `e4ebc9c702e50b4cb1eea8927a59df05155424fe`
  - Hover/Large/Default: `99a5f0eb6f82a144c39d86a7e3cb488c8d85cfca`
  - Click/Default/Default: `87b885c3b3e51612bd686bd95159bfc3587d588b`
  - Click/Small/Default: `11dd76fec00983556e8861967939be92132d7fac`
  - Click/XS/Default: `6f5702229e575bcee8a71add40177897d6fb312e`
  - Click/Large/Default: `8924480eb3c9b2362d4d033b12dcf8a3c8959dd0`
  - Disable/Default/Default: `0763cac40b90d0e77cbd1f00fbbf0d897cd1043b`
  - Disable/Small/Default: `f302cb9ed3baba3fec69cc9947fc5c8e50b8eb46`
  - Disable/XS/Default: `1d6b4d92de9a8805470ba609e04ace9939ef829c`
  - Disable/Large/Default: `e9f5301f45b012c6b3cd4594da03e690a1b10c02`

### Drop down
- **Set Key**: `021a6653c106f277f2481ee722ed93d4137dc3a6`
- **Set NodeId**: `540:1338`
- **Total Variants**: 36
- Variant axes: Type (Default, Link Dropdown), State (Default, Hover, Disable, Default Completed, Chips Completed, Error, Active), Size (Default, Small, Extra Small)
- Boolean props: `Label Icon`, `Show Chip 2`, `Show Chip 3`, `Label`, `Icon Left`, `Optional`
- Text nodes: `Drop down` (label), `Select List` (placeholder)
- **Key Variants — Default Type**:
  - Default/Default: `268ef50c7501a029a7b5179168be06dd7ee0fc3e`
  - Hover/Default: `345cf9126b328e3b65c97ed7eb3cf800e6baf580`
  - Active/Default: `c381105f72426c2520b1e8a93503d42099f058de`
  - Completed/Default: `6cd235caeb4a3acd6cea7abf74a963b9fe6a427f`
  - Chips Completed/Default: `8a8c5763a3a72207697b5d0373c3feefd8a37ade`
  - Disable/Default: `c0b7e3fc369f3280c0bd3865b226606e72be7420`
  - Error/Default: `a9981264ae3dda473baacce10d423e6abaeb2667`
  - Default/Small: `533142846bca6107294e1d54c856760c5935e07a`
  - Hover/Small: `2305c12abe29f20fd4c58ed695330087391b237a`
  - Active/Small: `b28b0a829f1947d7600825fa469ab7d6813fe351`
  - Completed/Small: `88b7fbe9304df510dc225ad40ba9ae00dfe0fdad`
  - Chips Completed/Small: `2e11d5e8890f95f1d080a4ecf3056ba8b8e432f8`
  - Disable/Small: `cab97f5d10ad542f9c57d8e3ae41fe691a225121`
  - Error/Small: `11d5e11bd8fc0064c0dc3d18ef381f781d0f755c`
  - Default/XS: `bbeb36ae792006a07e8c253aa560035718cdd0d1`
  - Hover/XS: `112f704c8ca76be96ffec1881c2f384e95ef4e35`
  - Active/XS: `c757c9bfbbe7014ce3be676201303e316acb478b`
  - Completed/XS: `81aa9981b933486fcb6d3de40409f8cdc0ea4da0`
  - Chips Completed/XS: `9ce08040c1190f81b4a1af7db34045dfad61fcdb`
  - Disable/XS: `e538918f37c753141dad8269ede7319f2e5f45cf`
  - Error/XS: `5e240e861e6d8d509427f3f9a70d1a144c02132b`
- **Key Variants — Link Dropdown**:
  - Default/Default: `b0e6e1621b1b63539a6445edfd376d6052963f47`
  - Hover/Default: `e1f293c90c0cb44d036dd41329c460f4d4f40916`
  - Active/Default: `8f557fde12d800e60056f8a7ac4bcb4f1bdc8477`
  - Completed/Default: `028fd19bee393d02495f94e965d7cac6c5d16088`

### Check Box
- **Set Key**: `f6f4ae2426b2e9d6c3ee7fc3727e06054b0f5d58`
- **Set NodeId**: `429:7790`
- **Total Variants**: 9
- Variant axes: Check type (Default, Partially Checked, Checked), Status (Default, Hover, Disable)
- Boolean props: `Title Text`, `Sub Text`
- Text node: `size: 64 / l-height:` (title + description)
- **Key Variants**:
  - Default/Default: `e62e52a525c51cf6ec6d1a4f2c41fbc73344a74f`
  - Default/Hover: `51ee289c92bfc3b511e32bcca3056c48715df7c5`
  - Default/Disable: `181b62d321a0cf6720e4f157b0c55fb2fc2b27fb`
  - Checked/Default: `2c34bbe485c56405ceece4b58e5269e610c17043`
  - Checked/Hover: `1d9465777fe162a05ded0951110ad063350dd664`
  - Checked/Disable: `07195374d014f6d6e117ce047b0a24c18f98714c`
  - Partially Checked/Default: `419e5760e04af53add34f841ab2a3ad544f8d590`
  - Partially Checked/Hover: `867e935096e67e327b02168056677a05d70f7de8`
  - Partially Checked/Disable: `72c14e777306023732dd12e3beb19d42ce21b316`

### Radio button
- **Set Key**: `be8763a756a299944aba5cc764d46ad6cec24bdb`
- **Set NodeId**: `776:4888`
- Variants: Type (Default, Checked), Status (Default, Hover, Disabled)
- Boolean props: `Title text`, `Sub Text`
- Text node: `size: 64 / l-height:` (title + description)
- **Key Variants**:
  - Default/Default: key=`3f130d1b8cb9fac241fbbd7ea7d5f21434dc8fd5`
  - Default/Hover: key=`9ba93d1b6e89cecaa0e33e8f3da79f1ebee7d242`
  - Default/Disabled: key=`e5b56cd13f31bf82f438d0361251b7e7b7fa34cc`
  - Checked/Default: key=`5d1e0d7bcf92e09dfeec7f9aa03b6515848d41e4`
  - Checked/Hover: key=`e2cb6a6f0bb5c8f16a2e51ccb4f82646ed423771`
  - Checked/Disabled: key=`bb6e8affeff4d663bd07e2151a929562bd2a7428`

### Toggle button
- **Set Key**: `35016f9e4ebd41a83c952fa04c3c47a1f36d0ec4`
- **Set NodeId**: `776:4939`
- Variants: Type (Default, Active), State (Default, Hover, Disabled)
- Boolean props: `Title text`, `Sub text`
- Text node: `size: 64 / l-height:` (title + description)
- **Key Variants**:
  - Default/Default: key=`c7282a51cc5d13785e873db189578789908239a6`
  - Default/Hover: key=`8f976462422adfee029cb1f55de4818571ac2049`
  - Default/Disabled: key=`cf1eb57b589e30e7f7eca4c9fe8bf0e3f09f642c`
  - Active/Default: key=`e5fa8aa4847d050ef1ca7a0c5b2a96e8b5a51b4b`
  - Active/Hover: key=`c007a18c46ea4ff3dca2946edc612b724a3ddc40`
  - Active/Disabled: key=`dc6c140faf74f88b9cfb9b1fb93149c7a37ae4dd`

### Card BG
- **Set Key**: `0a6610b4540cec27f39b38930dbeae02fbecfabe`
- **Set NodeId**: `448:704`
- Variants: Property 1 (Default, Hover, Selected, Disable)
- **Key Variants**:
  - Default: key=`8282a02c8fe5077c0859bd8adaa71d530b1602c8`
  - Hover: key=`36c2b023c19fd4c7a255bc95e3d17484cb5fafb7`
  - Selected: key=`21b500580cff1ca12ac344e57b43c524b0dc34b1`
  - Disable: key=`b9f155765e31fa129afb346caa16e74b2c24511c`

### Badges
- **Set Key**: `158e4b6d656a62d4244efc4e5583794044328d3a`
- **Set NodeId**: `461:767`
- Variants: Type (Primary, Secondary), Color (Primary, Green, Red, Disable, Pink, Orange, Grey, Purple), Size (Default, Small, Dot)
- Text node name: `1`
- **Key Variants (Primary type)**:
  - Primary/Default: `5d541380661e1a2de2cfb5557b50b58d8ff53425`
  - Green/Default: `8ca7161ecb86188fe2ab3881babe81a04c22c56c`
  - Red/Default: `e25c954ef6fdb7830d089cb529d3122e554fbd7b`
  - Orange/Default: `67c996cc2e2e5af5cd59e9a4ea521693096370bc`
  - Grey/Default: `97e1c6fb2b071a83dbaf197ba25a214cf0ef0a55`
  - Purple/Default: `c09fe6f42b2ee25ce781bc0cf29eaf4469a335cc`
  - Pink/Default: `ddc90a66a371fb8280b7c0e3bc0cf85c4d6f756b`
  - Disable/Default: `e5bc5c8b7e0f8fa217ab047e70b71a8f3a9d5749`
  - Primary/Small: `7e9959c67a04d3bc86d044d6c7ff0ec5c0c40e46`
  - Green/Small: `b6387e358b9fa3b26b1253ca8d19050c6d6582a4`
  - Red/Small: `901b403c42eed59e985407a60d0fc88254940dbb`
  - Orange/Small: `541fcffc7b2c3a17a386e4787733dc5b17b32378`
  - Purple/Small: `1ea3aff575f3fa55c63b6b27952f104fdcc46873`
  - Pink/Small: `695322e558eba8f6c1cb793db7acf6ca832eab29`
  - Grey/Small: `1c983b8dbd7dc166da1bc020e40456f5c1d49c93`
  - Disable/Small: `ad31e948ea14aed8779e6225b84c6d2552ac786f`
  - Primary/Dot: `32eb7f5e36be45eafc9b50ca25c371bbf1c4b17e`
  - Green/Dot: `e3ed01f887449258bc7b4307cf0160472fe8b6c3`
  - Red/Dot: `e3a7f9b82d19a1166afbe3bd75678330fab9408b`
  - Orange/Dot: `a9a7d7ab5bec13e8d0580c9f2029cf6b65f1ca13`
  - Purple/Dot: `bac9e7bb8bcb17fb6c52437a70449bece0a66166`
  - Pink/Dot: `6034e3f4dc64a31bd54e1f44a0e9c7d3e807d461`
  - Grey/Dot: `dca49157612adcb7cb4138c9edc4389b869d202f`
  - Disable/Dot: `a6fa476448c213caac8894d125769761f25b9411`
- **Key Variants (Secondary type)**:
  - Primary/Default: `9bfd00fa1178b4cfc90ef77c795f131113dbc025`
  - Green/Default: `f7907755e97969b4eb4cd81bd59caf4953783281`
  - Red/Default: `aaa0908c4fefde62401e4dc819b92170e34fe7a4`
  - Orange/Default: `2ee502ff7f857dff358529f533a5c19b99d2d138`
  - Grey/Default: `a5ff951d0bed91a1245da50e8d15f5a304b6d201`
  - Purple/Default: `f3e32e69f118d5ed47d75c6294de3a0046ad133f`
  - Pink/Default: `e0ba0d8bad0fcb9aa9ad0ea08d3a5e79d738a7cc`
  - Disable/Default: `aee1a15e087e5f196ab71984cc848c92e7725db5`
  - Primary/Small: `083b580a40a0d7cf1d7f9feafafa8ba91bd503de`
  - Green/Small: `12b724bcd571d80b698d1a8e9d57931b920e5352`
  - Red/Small: `ae4d280bb9ef5350eebf53d755e067d7946ac96f`
  - Orange/Small: `8c0de88d40b57baa10e1167b0f7ca068477c0734`
  - Purple/Small: `fb57aa6418e10835e04a2fd21ce211eabd5c4924`
  - Pink/Small: `550897ce5bef5248f803f71b424ba65ad4df589e`
  - Grey/Small: `8e3dbde5b109c0370dec1b8f269d4eb6d6391d8e`
  - Disable/Small: `7a6f66642e24b07dcebd2b58f0452383d24e99c9`

### Breadcrumbs
- **Set Key**: `0a3311e7b166996622dc853a63d3c51cb26b13b2`
- **Set NodeId**: `541:1001`
- Boolean props: `Breadcrumb 2`, `Breadcrumb 3`, `Breadcrumb 4`, `Breadcrumb 5`, `Breadcrumb 6`
- Text nodes: `Breadcrumb Link` (6× segment text), `/` (separators)
- **Key Variants**:
  - Default: key=`781af480e56215ec5d7bcad48bf9fd7af288d784`

### Divider
- **Set Key**: `f301e08fa28bfa77c8bf150314425aafc3f3a66c`
- **Set NodeId**: `1069:8540`
- Variants: State (Default, Active, Completed, Disabled)
- **Key Variants**:
  - Default: key=`f72c745f6cb854f7aa17f057f65855d67ab9dbaf`
  - Active: key=`633f95a7e46c016afa445fb3ccc96862bbe06b67`
  - Completed: key=`671a7c8e35cac6ed08497f9e0bde38e620f73987`
  - Disabled: key=`0c6c442fbc18eb27818ab6dcaa231fed1017e85a`

### Search
- **Set Key**: `422a135a95c3e8569843d9c6fb7c69aa0885c10e`
- **Set NodeId**: `447:6724`
- Variants: State (Default, Hover, Active, Variant4, Disbale, Completed), Size (Default, Small)
- Text node: `Search Here`
- **Key Variants**:
  - Default/Default: key=`edbdd857fcaad423c6dfb455e9c3d4663d8e1039`
  - Default/Small: key=`5e5076aa036c2e353cc520e750d154a8017922f1`
  - Hover/Default: key=`74737aac7b97e5786dc8a145c131449a2af8b15a`
  - Hover/Small: key=`6453b88cb68748b53c7768fbea0167bc140e3c81`
  - Active/Default: key=`e1880816d9631605d376a05f41028f379015784a`
  - Active/Small: key=`db8d0a44b53e67e353398d7016a53d500769b3b4`
  - Completed/Default: key=`c0fc73ecdc6457e89152a41ecb8728ffdb56dce0`
  - Disbale/Default: key=`fff2781864910ef892f7a573ad76bf63b7279fa7`
  - Disbale/Small: key=`313aef208b2c73ad8469d122867093e41a1095c7`
  - Variant4/Small: key=`fc79cabe2548a107fd133c0ce3b7e681c2baa264`

### Gradient Button
- **Set Key**: `86fe8b75bd17c1bb5f6116cb827aad942a934012`
- **Set NodeId**: `1305:10534`
- Text node: `Button Text`
- Boolean props: `Icon Left`, `Icon Right`
- Instance swap: `Change Icon Left`, `Change Icon Right`
- **Key Variants**:
  - Default: key=`8a5cfe42725cbf63da3f1791c5fe1fa543884210`
  - Hover: key=`4bade57fa34b805b8f40e41602f4a1247a814a73`
  - Click: key=`49da598faf0dc07012ab7a4353326f5831de691d`
  - Disable: key=`cda8fd6fd318c1f73e4ff85c1a0aa0d08e47d46c`

### Link Box
- **Set Key**: `723d10821d635cb25626fc7e8545b389dbe97bdb`
- **Set NodeId**: `1319:43268`
- Variants: Lable Type (Top, Left, No Label, Label Inside), State (Default, Hover), Size (Default, Small)
- Text nodes: `URL` (label), URL text (long URL value)
- Boolean props: `Label`, `Info Icon`
- **Key Variants**:
  - Top/Default/Default: key=`9fbf4fca3a034d19feaee4cde4ab05b3185c2284`
  - Left/Default/Default: key=`85439b9d41fb8ab6b126543e2a8ba51ba9bce1ff`
  - Label Inside/Default/Default: key=`fad0f8817f567cbccb46ee5a51572fa7daceafc2`
  - No Label/Default/Default: key=`b3d6ab6ddfa3c132c089be3974f76faec62cd64b`
  - Top/Default/Small: key=`4cade09cb16cea00f812f0b9c59f44cd2aa35777`
  - Left/Default/Small: key=`cf6ddb44276c6f8810c80018b9b27b8aa96bff50`
  - Label Inside/Default/Small: key=`3d309fc860de4716737483a60d6da3e14ae697c3`
  - No Label/Default/Small: key=`56aa99e471fbfd2d3bb4136e54addd45f5648d19`

### Tabs
- **Set Key**: `4851c5917e3ca7aca6aa65f44d49d83b9594f3f0`
- **Set NodeId**: `456:743`
- Text nodes: `Tab Text 1` (all tabs named this, use index order)
- Badge text node: `1` (per tab)
- Boolean props: `Show Tab 3`, `Show Tab 4`, `Show Tab 5`
- **Key Variants**:
  - Primary: key=`043ae53648d3f06258b07ce5b744c6585ce3ce22`
  - Secondary Default: key=`22186b24b4069f721a671b06b37e2b2ba846401e`
  - Secondary Small: key=`8ef78be0d4cb052897650b1b10ae2309edfde62e`
  - Secondary Extra Small: key=`d9296501637c79dd3fe7f0fc60754d5ba6ae6acf`
  - Code Tab: key=`e5c90e763b065cfd197b751e0ec875bfd151b0d8`

### Chip
- **Set Key**: `69274b61923231a45f559e59bed169c121d9bc45`
- **Set NodeId**: `429:2608`
- Variants: State (Default, Hover, Disabled), Size (Default, Small)
- Text node: `Active list`
- Boolean props: `Icon Left`, `Close`, `Text`
- **Key Variants**:
  - Default/Default: key=`2cefc27769a90003228345b03c46e3788dfc35bd`
  - Hover/Default: key=`5500398e55f6b4b88f2a48a46e71cd1e7af33f9f`
  - Disabled/Default: key=`95fcf1758b19f900c1abe6b9e55e567001e2ef44`
  - Default/Small: key=`cd9493ea886700ce7a6ea507c9f262a8a5464088`
  - Hover/Small: key=`67598a59d590577e738f4f31a005dba24160a23b`
  - Disabled/Small: key=`4f6dc18b0c11f4514f189314ac44360242f31daf`

### Accordion
- **Set Key**: `de19e2bef81becf98aa6f4d504439160d621911b`
- **Set NodeId**: `544:4715`
- Variants: State (Default, Hover, Active)
- Text nodes: `Main Text` (heading), `Sub Text` (description)
- Boolean props: `Show Icon`, `Sub Text`, `Heading`
- **Key Variants**:
  - Default: key=`5ddd9828ed6720fd91fadc1789d6cab89f7f73a9`
  - Hover: key=`c97b2351fc37791ff8658d5e5dfa20b4d90f9f60`
  - Active: key=`b908c22dee81ab782fc6ec419f74a8abd9313d3a`

### Alerts
- **Set Key**: `6a8d01cc94edca858392f02daad5cebb99aca7d0`
- **Set NodeId**: `762:19318`
- Variants: Type (Alert with heading, Message), Color (Success, Info, Danger, Warning)
- Text nodes: heading text (varies), long description text, `Button Text` ("Learn More")
- Boolean props: `Show Icon`, `Hide Button`, `Show Sub Text`
- **Key Variants**:
  - Alert/Success: key=`4c9c5fc6f1044aa5d99a05a5b7bcb2e75a44de8d`
  - Message/Success: key=`e1deb378fcd81c41af90af495adb4cef60816ade`
  - Alert/Info: key=`4385a4f9b39a1ea4854432624ac5fd2121b81abc`
  - Message/Info: key=`a870b725fb94864a2be8f5800989131b1c1beb4c`
  - Alert/Danger: key=`59ffd30443f7ee3f216aaa68f4e16f100899e0f3`
  - Message/Danger: key=`8740384eef1ddd08f157db005b25ec4d1fd7aaf4`
  - Alert/Warning: key=`1d32727ded7c95c51e67420e50258ac3b9a8b0fd`
  - Message/Warning: key=`039bf30da346a809b1cae1c5a871b7116027b0ed`

### Attention box
- **Set Key**: `3c58dee55668c602ac70872f8878dfc0e4b0e0f0`
- **Set NodeId**: `776:4315`
- Variants: Type (Alert, Message), Color (Info, Danger, Success, Warning, Default)
- Text nodes: `Attention Heading`, long description text, `Button Text` ("View More")
- Boolean props: `Hide Button`, `Show Icon`, `Show Sub Text`
- **Key Variants**:
  - Alert/Info: key=`db85a91915fd9660b7ea15204140fe03c254796b`
  - Message/Info: key=`ca764d1e8d32a274ddf036ba675ac0b84d0b3002`
  - Alert/Danger: key=`a68862e1116052cac2308f05f713ec906ad584cc`
  - Message/Danger: key=`5186ec7d53f4df1c685a2d501698c16377bf61b1`
  - Alert/Success: key=`97577d8b6d9c602bedfc3e6d2be80f6a5957d962`
  - Message/Success: key=`8d7cab5cea0dc62ee5da2f3d95115d5f0cb80b74`
  - Alert/Warning: key=`5a2fa49f9f6c057e2e6eb9d4e79cc03dd14dc3de`
  - Message/Warning: key=`a4835dcbbabaed464536d0f4cf37a7b62dc29d14`
  - Alert/Default: key=`dcd23663b651d7fc20a830fcdc2669787b085e13`
  - Message/Default: key=`0e99a6a19b97963403ada4b2fc051968d9d09301`

### Tooltip
- **Set Key**: `ee9488a518bfa321bec5233b512327004534c226`
- **Set NodeId**: `779:4711`
- Variants: Side (Left, Right, Side3, Side4)
- Text nodes: long tooltip text, `Button Text` ("Learn More")
- Boolean props: `Show Icon`, `Show Link Button`
- **Key Variants**:
  - Left: key=`959b2183ff56f7ea4c9babb3f927f735abdcde20`
  - Right: key=`048f6b2a324bdc000c8af1109186e7824de64d05`
  - Side3: key=`c3b9007f28924299e8b2962ae922985bafe6b1e1`
  - Side4: key=`350498eb4d3a83fe63cb17134cbc7cfcc8bef5d5`

### Avatar
- **Set Key**: `928239e0d3b1666d7ab0d26c42c71ab8a2fd3233`
- **Set NodeId**: `1173:15428`
- Variants: Image Type (Men, Women, No_Img, Letter, No_img_Fill), Size (Small, Medium, Large), State (Default, Disable)
- Boolean props: `Status`
- **Key Variants (Default state)**:
  - Men/Medium: key=`8995940d151b85607f962b236b467e8818991e32`
  - Men/Small: key=`f5e644431eb1c7caef432e1018b6cb78b73046ea`
  - Men/Large: key=`85265f0417068d492d7bac80b736286778a178ec`
  - Women/Medium: key=`ca700d71fa568cb4cec3eba2843065120f69c20e`
  - Women/Small: key=`69991d437a3d5f00db878c45520e32b3fd745b1b`
  - Women/Large: key=`953a07bf6f24f2c27eb9bfb2a9bd8017c139cbb9`
  - No_Img/Medium: key=`6f8232bccf1064410043882f1fbf0ed10c4eb331`
  - No_Img/Small: key=`6342d7bb0c602ed393aa02139c8b154b421fb8a1`
  - No_Img/Large: key=`cbcf8882ad4a19535628fd173c5261d3aff454bc`
  - Letter/Medium: key=`8b8c956d97305223f2e21577dbd34d6d94aaad15`
  - Letter/Small: key=`e7984d19183993bc4101ad9bbabb6e3c9ae7f6d2`
  - Letter/Large: key=`3e1e0199505db3cc12a0bfcb3628773e52efbef2`
  - No_img_Fill/Medium: key=`aa10f57ffea1e25b1b8ffec41b12fb326d609774`
  - No_img_Fill/Small: key=`a357d4ee80d68efeda9fc72780d84d8d8bdd4186`
  - No_img_Fill/Large: key=`91bbe6195bc81c8050fb7aecf0c7e8c7962cae8b`

### Date Picker
- **Set Key**: `cb96d28ec44bbdff5cb9360405a7931f0df08d1a`
- **Set NodeId**: `1508:28577`
- Variants: State (Default, Range Selected)
- Text nodes: `Select Date`, `Select Time`, `Button Text` (Reset/Close/Apply)
- Boolean props: `Time Range`, `Time Zone`, `Show Date Range`, `Show time Picker`
- **Key Variants**:
  - Default: key=`a0e0eae9cbfc7a1aec7887f8ad4a354a2f3fc284`
  - Range Selected: key=`5d941897708c16cbbbf210406e6a3756b52f564c`

### Sidemenu
- **Set Key**: `c5cc6958acc9fa1c180d3d51c383d355547c634f`
- **Set NodeId**: `1398:5837`
- Variants: Type (Default, Icon Only)
- **Key Variants**:
  - Default: key=`c9b020af66d669fa9de52bae37d7bb8bf902afd5`
  - Icon Only: key=`0bacaf0146f19f46d3c65e78288204c43f308310`

### Table
- **Set Key**: `651b0fc7a3921dfc45c0d7f0f77ef434aa0dc4fb`
- **Set NodeId**: `491:6245`
- Variants: Property 1 (Boxy, Stretch)
- Text nodes: `size: 64 / l-height:` (column header + cell text)
- Boolean props: `Col - 1` through `Col - 9` (toggle columns; 1-4 default true)
- **Key Variants**:
  - Boxy: key=`f5c2c94ee6b8bddb779ff1d82125cc73b044fdfd`
  - Stretch: key=`ccaff166b021b69c24a3e554ea7e10e06c7609b9`

### File Upload
- **Set Key**: `8d62af0123566965167299d70fca5984d2b1ebd0`
- **Set NodeId**: `780:21060`
- Variants: Type (Single Upload, Multiple File), State (Default, Hover, Click, Uploading, Error, Completed), Size (Default, Large)
- Text nodes: `Upload File` (label), `Select a file or drag and drop here` (placeholder)
- Boolean props: `show label`
- **Key Variants**:
  - Single/Default/Default: key=`cf3c67b4f898d6d64de12553d7d2fb5af155fea3`
  - Single/Hover/Default: key=`ea50e8418a95b9be5672c727db0d449ac6b59562`
  - Single/Uploading/Default: key=`843bd65fc998b5f0834cb66d2c677f8c8c3a5bda`
  - Single/Error/Default: key=`839db0ec9e9f1adc95075d74a90850a7e9f01243`
  - Single/Completed/Default: key=`147af06619440005343f1dced72f88f5a89cf68e`
  - Multiple/Default/Default: key=`b080d0d9119320bc9e09cd81446a0d214ac69cc5`
  - Multiple/Uploading/Default: key=`47e53e19103ebd173f09ed105c934290be04d0e4`
  - Multiple/Completed/Default: key=`da7187bd8accb838828485f383e43ed57364e0e2`
  - Single/Default/Large: key=`f9e9d474926bdfbda98686ad3ed8c72d64f20f45`
  - Multiple/Default/Large: key=`73d0502864936032ca447fc1fd8c07e5e6d55072`

### Dropdown Menu
- **Set Key**: `60c79101cb2a0399f9239bd2477634e0591d2e85`
- **Set NodeId**: `444:4342`
- Variants: Type (Default, Deafult with button, Multi Select, Multi Select with Button, Empty 1, Empty 2), Size (Default, Small)
- Text nodes: `Default` (title), `Search Here`, `Hello Im Action` (menu items)
- Boolean props: `Show Search box`
- **Key Variants**:
  - Default/Default: key=`3d1ebf3b6922fd83cc105463336fcfa86ff22ee2`
  - Default with button/Default: key=`caa713142df4bb56fc77beda943be76796c227a2`
  - Multi Select/Default: key=`adaf8815d267e85cf95fee7b156965db4030b3b4`
  - Multi Select with Button/Default: key=`e6cf42b1db07deb03bff088dde9f20ec9fe4940d`
  - Default/Small: key=`7739ae70952371c0240a11e1b36455be492551fe`
  - Default with button/Small: key=`fc8be6c4674b87871345fb56e2dbfe43f196e961`
  - Multi Select/Small: key=`d8b60b339e7348d55d216937072ed41cdb2af33d`
  - Multi Select with Button/Small: key=`d314e9739617a57b99799fe77e48e6edd59f0e68`
  - Empty 1/Default: key=`47cff4e4c5bf02af575c7fe8fbf28ebe7bbc63a7`
  - Empty 2/Default: key=`a2b55414906717de7b29485037ce60f1d6dc9906`
- **Set Key**: `60c79101cb2a0399f9239bd2477634e0591d2e85`

---

## Other Component Sets (internal/helper)
- _Table_Cells_Main: `ba9b711001fc37458f9397f41b1de64844513350`
- _Table_Col: `c489e08242e786c6dd9dd0c671db8147c8e4f773`
- _Row Bg: `9fe92e5443330a353e265cbd1355d347d4a10e27`
- _ThreeDot: `8bbd9103e6336e6fb71cb81fd5a1c5dda25f62cc`
- _Only Icon: `d496dde06f1d51f4c727066edbc9cb639f73a551`
- _Sorting: `918a49b40405f34902708a7098d264f22086f53c`
- _Header: `6a3caa79ee2538b5d123abcc0d74ae5cb98adadd`
- _Breadcrumbs_Source_Basic: `5851f1ebfd409f673f3d6315ad932d1e0d50b231`
- _Stepper_Source: `ef09b7057082b5123747d58b284d620b77edb049`
- _Sub_Header: `9409ac8e1794d2d056de094a2e88378ed004be4e`
- _Sidemenu Source: `e03cde69048477572b363173e0323e44913be560`
- _Service_Icon: `15ac5dd4711e1877e16b10960961e05ae4ea8284`

### Key Value Pair
- **Set Key**: `d35e27d088cd88bd9f860992d5f551a3a3c66086`
- **Set NodeId**: `3850:3408`
- Variants: State (Default, Hover, Error, Disabled)
- Boolean props: `info`, `Optional`, `Third filed`, `Label`, `Manual Add`, `Drag and drop`, `Minus`
- **Key Variants**:
  - Default: `de31abbb2e28db1bb0028dfe9a8450db5976e3e0`
  - Hover: `a7fd44d35b8ec30ca9472bc96aaa4742dd7cf980`
  - Error: `3c3ddb3d26bd6cbd4e14db52cd1b65edb9f0c214`
  - Disabled: `474e3564f484d2a49b1ab6a713c9a5a63251f17a`

### Double Field
- **Set Key**: `27388328932ea8eaa0f60d1ae15c8c52457aea13`
- **Set NodeId**: `3850:4144`
- Variants: Type (Front, Backside)
- **Key Variants**:
  - Front: `3632bc49650bee4210ee93e3e74f9f7671c473b5`
  - Backside: `9ee03d57ad86fc857da38b4c2b918fed82572659`

### Grey Ghost Dropdown
- **Set Key**: `98b11326070ccdc9e9bf4437fb9d63fd99f4f6ea`
- **Set NodeId**: `1250:11160`
- Variants: State (Default, Hover, Active), Size (Default, Small)
- Boolean props: `Show Badge`
- **Key Variants**:
  - Default/Default: `4a5bcf9ffa1a70c39a5f244adf959bb76b046d7c`
  - Hover/Default: `2067b22f4f5c584df3161a34493d53d265090b05`
  - Active/Default: `65cc7b4dfc374add7f50b81ab0c98defa4a5c1ea`
  - Default/Small: `3fd2ad6ca85770d7a1e2d10c235947bd446e5e4e`
  - Hover/Small: `b431ca0e8a5433655718527e9e00c6eb43bc8b64`
  - Active/Small: `fb769208e34cb35516aa55886cc20bdfc64895dd`

### Accordion 2
- **Set Key**: `711879442ba32efdf1b7926cccb484854d80ad8b`
- **Set NodeId**: `3265:20605`
- Variants: State (Default, Hover, Active)
- **Key Variants**:
  - Default: `c673ef4cb2fa4972953d86c02adfba59d4d83088`
  - Hover: `cf721f71c7a629badaa152eb5e4e95cc8af60bda`
  - Active: `929999ab5276fd33f0f45cab329330da5bc57cb5`

---

## Standalone Icons (in "Headlines" frame)
- Plus: key=`0353e0bef07a3262609f262e9050788182c5d1ae`
- Minus: key=`8021b78ec63a9fe44cad57941922d6b6e1e06998`
- Arrow Right: key=`44e77c6d9caf9469874a2f93e14dbc78faefd7e8`
- Arrow Left: key=`107e6552f7200e0fe2e80f07109e343ed57c8c51`
- Arrow Up: key=`95d355a9667b741ac9077f4e401aab1f6f8fcec6`
- Arrow Down: key=`7007a026a707b3cd1bc1f751032e6cdd0d79c805`
- Alert Round: key=`58ff2f105121d1267c6d692b663428b016ec4e3f`
- Alert Triangle: key=`77866cb6c4901fa06cba46bd483a31a642426ae9`
- Right: key=`287003a608f2a9b64b07decabdfa38f821fa5fc4`
- Left: key=`2cb675ddb314ced99f0f6cff6465533ca7cfab16`
- Up: key=`e180c5d201b234396da6897482aa5857695ca93e`
- Down: key=`3048845dcba4d1e8cac4f5b50aca390e1c27ec3a`
- Loading 1: key=`33ffc708ae95d6d50495f1a445543f5393b8787a`
- Tick: key=`5656c96f4fa0d362a5acedfecfba921125b1d6fc`
- Three dot 1: key=`28ee9e6ed927d74b8a4a08cc0dff4f3439763f73`
- External Link 1: key=`7b5d1b9bdfc0e941829bea992846d2dc63b33385`
- Rocket 1: key=`aaff7ee3822454e541bfa0b57d879cfb1cf39431`
- Info Round: key=`0a1ad8c44abeb428a6de82505df216c36bf7804e`
- Dollar Round: key=`8dfcd097b00cd4afb61c773bbf840cadbbac8b7e`
- Percentage: key=`81020cc3d361400b9b27c9075205bd40910419f4`
- X: key=`0637a1359b097de0eb80f76570b15334413c7316`
- Search: key=`d1e4a696fa94574707f78036b67177210bf77fc3`
- Question Round: key=`db338c3be63f3f3f1357537d93accfd316937b6a`
- Home: key=`84d6d05ac02affc0590f500dca62dcb3f9ff4d14`
- File: key=`5b9f71f998b4a5609c1dce4877c5bb696782666d`
- Eye Open: key=`d3cff6ffeb33596f9998f356f0aee1410984f689`
- Upload Cloud: key=`c4d2e4d41d1e515d493bf84f2a05efce455263d5`
- Folder: key=`147155feaae84057aa421c7bfd902c5cbadd838c`
- User: key=`374b68ee05be90d8b8f54e67e87f9e100b0d3d55`
- Star: key=`cfa75b6198fa03676a66caae01d7b5ca873376c5`
- Nine Dot: key=`332a8c880bbbae9a0e6ca59ee01103b82c338905`
- Refresh: key=`95a8b64f46e2057d5039de856f7e14f216d96fa2`
- Edit boxy: key=`ec2766bea4123b3603080edc59b7a6ff20e0c5ec`
- Download Cloud: key=`e01bbe03abdeefb34c40f0d1d15cd2b3dd03ae71`
- Delete: key=`f90298d150aea6f0a3363c020774d6b2bda0519c`
- Copy: key=`bf61e378330f2257af023cb6db96202828cb98a8`

---

## Text Styles (26 total)
- Headlines/H1: key=`25a8a1ac56ecfeab817800c7d35a0a854b4c5f17` (Inter SemiBold 40, auto LH)
- Headlines/H2: key=`e3c4e89c4987b83a0de01e874a704698beb2ef79` (Inter SemiBold 32, auto LH)
- Headlines/H3: key=`e51050207ddff0a20d1b1dae80bddbd5b34d4fb2` (Inter SemiBold 24, LH 30)
- Headlines/H4: key=`5773e80e10f3396d8da80218ae0e7799637c42e3` (Inter SemiBold 20, LH 24)
- Headlines/H5: key=`be57224f7a8d40f6fb33855456c324c6fdc58adc` (Inter SemiBold 18, LH 22)
- Headlines/H6: key=`5a352759b8b34ada73a6715ccfe6649bd09b8f9b` (Inter SemiBold 16, LH 20)
- Body/Subtitle 1: key=`51e124811b05455ba4ec2170c2d7d17c606e9850` (Inter SemiBold 14, LH 20)
- Body/Subtitle 2: key=`28ab09c4e20e68276cb6afa9877e62e523225126` (Inter SemiBold 12, LH 16)
- Body/Subtitle 3: key=`d83f1df53b390782a1002c0288f1179081395c9b` (Inter SemiBold 10, LH 12)
- Body/Body 1: key=`dd4a720e10df4ebca0fc96607ae81effb512009e` (Inter Regular 14, LH 20)
- Body/Body 2: key=`3ec92fcb0c18950b4de40b4b0481d6411327af2f` (Inter Regular 16, LH 20)
- Body/Body 3: key=`540b559794ca7eb23631093b727eddd1d41c14b7` (Inter Regular 12, LH 16)
- Body/Body 4: key=`0141e7b3527e7438234bf07bc7279158bf13fc60` (Inter Regular 10, LH 12)
- Body/Body 5: key=`e0738f6314e70a6ed9eceeed331fde5c1beccb48` (Inter Regular 18, LH 22)
- Button/Button Lg: key=`b6c68ad0728e0962f7eff37555924827bfac9083` (Inter Medium 16, LH 22)
- Button/Button Md: key=`58875ab6a77d036883addb9473f4272de6575482` (Inter Medium 14, LH 20)
- Button/Button Sm: key=`82dceb66c8f9c997c24907889defda24a24388e6` (Inter Medium 14, LH 20)
- Button/Button XS: key=`456336493d842efb5ab06a3f70e1f21d91c2a192` (Inter Medium 12, LH 16)
- Input Fields/Label Text: key=`cb08c2a7d6c5a22cf69315673c6bd2c083572323` (Inter SemiBold 12, LH 16)
- Input Fields/Default Text: key=`a3cd3ef68c4573e1188d8ebb2ddf35e78de70421` (Inter Regular 14, LH 20)
- Input Fields/Small Text: key=`2e582897730de10494722094148a39d67677215b` (Inter Regular 14, LH 20)
- Input Fields/Extra Small Text: key=`6fd9460657f2f821c73f5db5c0bdff165294b11a` (Inter Regular 12, LH 16)
- Code Text/Code Body: key=`ea2637050ab70296a1ea8e78fae48b9788150f14` (Roboto Mono Regular 12, LH 20)
- Code Text/Code Subtitle: key=`9ed93cca872f5a56852b94df2c84472480ea2c02` (Roboto Mono SemiBold 12, LH 20)
- Service Name: key=`0960212d4963bc7bb5b8c9f8166310d86cf5ffb2` (Inter SemiBold 16, LH 20, LS 6%)
- Service Heading: key=`fa3a3f0ae2cde538a491578bc08f45793bd43fc8` (Inter SemiBold 10, LH 12, LS 16%)

---

## Variable Tokens (available via library import)

### Mode Collection (71 color tokens) - key=`3b4b2cc7462fe6f0ca5d74432cef3edf1e386712`
- BODY/Text/Static/Primary: `923bd06a923fee3c9811bed53c2e1023d667e99f`
- BODY/Text/Static/Secondary: `cbc2c154ea80793b1cc0707f853d43e59a96cf04`
- BODY/Text/Static/Light: `7a19681638a68e906bddd75586271d7836762473`
- BODY/Text/Static/White: `3b9a2f87cd7cb2db22e52bba6c1fe2ba97a31b0e`
- BODY/Text/Static/Disable: `34cb78323c4482bb9ddd65aa567b609282734f7b`
- BODY/Text/Static/Theme: `0e6d1bdb08c318e876eafd4be5915c3266191fae`
- BODY/Background/Static/Body Bg: `8a73e5eb7acb073d9207bddf09a19287115b4cfd`
- BODY/Background/Static/Container Bg: `a9b4ed83b5ad5b5fe00bc4e56a141e92ad8dae02`
- BODY/Border/Static/Border: `dee9b282355cc41a5865a29cc8fc48d6b80484ec`
- BODY/Border/Static/OuterDivider: `71abb67e509670e8bc2a18aecd730ae64a7eb0d7`
- BODY/Icons/Static/Primary: `5a84f2ed810016b3efb87e427e84cc49562309fa`
- BODY/Icons/Static/Secondary: `4b949396ae9456a5e3e8c5f211b2904a88ac33c0`
- BODY/Icons/Static/Theme: `ff104a7fb5d301d5943d7172ed0beef76aa1fece`
- BODY/Icons/Static/Light: `b477aff637a8016f87deb55b8d1aa6a43b0f5e6e`
- BODY/Icons/Static/Disable: `b316d9615de355d47faaf643baad606d3bc7efe5`
- BODY/Icons/Static/White & Black: `4ff3e20618be8f9b55ba4a4449f8c6355442adc5`
- CARDS/Bg Default/Primary: `5f31ffd455f693c79bb692d089dc99c045508bde`
- CARDS/Bg Default/Secondary: `33799101f4d87567229f94849487afeffa6750c0`
- CARDS/Bg Default/Teritaroy: `02db6ed6bf18105b51bf83233ba8e4e8a74cd7ac`
- CARDS/Bg Default/Quaternary: `ba00e89b5c711bf24e1968fa24271ef59f95c4e2`
- CARDS/Bg Default/Body Bg: `f792049ac254d1470ff270909b54301a96b90065`
- CARDS/Borders/Default: `511f1c30128041f0816ec4025aed7cc050584519`
- CARDS/Borders/Hover: `bacf7f302ae4d0159192d51a810e5912e7f20d89`
- CARDS/Borders/Selected: `fab6eed58da56edd8dc4647b8ad971892fcaf4d0`
- CARDS/Borders/Disable: `0b1eca41bb434fb789473e378b2a1a661bfe6a2d`
- CARDS/Borders/White: `b9620d5eae45f0e705bf594024073e673959dcc2`
- SHADOWS/Background/Default: `9087ddd60b49acf3baa5d2752af9ed43da350800`
- SHADOWS/Background/With Opacity: `815cca3b157d974378255bdc699c951143f3a44a`
- OTHER SHADES/Theme/Theme 1: `ce98fc91700925c5828b0649694ce8d694537610`
- OTHER SHADES/Theme/Theme 2: `724edb6d513653fe7c756c00ced1f1c64442a62f`
- OTHER SHADES/Theme/Theme 3: `0efe8122b8b247c501d7c3b86d7b86778da39c5b`
- OTHER SHADES/Theme/Theme 4: `73e778f18003828628514fd853d9c370db0f4ae3`
- BRANDING ICON/Icon Color/Red: `8fa6ccab91def9f2e89117ed6cd2e9292433460b`
- BRANDING ICON/Icon Color/Blue: `470ccc11af67b94d38375c655263d2d2dd923b2d`

### Typography Collection (55 tokens) - key=`a50d52bbc62df82bca7cf7cb4a08936642585d13`
- Size/Headlines/H1: `1f57f4082701309ceb8a33286496b80e0efb8f4e`
- Size/Headlines/H2: `14c2b91728c7d6b0e0c7b9f56a2c832cdfd5190f`
- Size/Headlines/H3: `3f96585a1093083b0c1c7d22b4c48068320147d0`
- Size/Headlines/H4: `751219e36da555ca7ee22e1b1561993154baf457`
- Size/Headlines/H5: `ec5e1358b04c0b2b77a5eb120893f983a902b5d6`
- Size/Headlines/H6: `95534647073c5cf7f52573cbd565474edf620e4b`
- Size/Body Text/Subtitle 1: `0ae37832c4ccbd03f172a3b87c601e7ee76a7398`
- Size/Body Text/Subtitle 2: `d975a692b9f6c58e8f35e565aa9a147aff41fcc5`
- Size/Body Text/Subtitle 3: `3df29947745c2e5d7ab09ff2c3dd6a1aa3b79dde`
- Size/Body Text/Body 1: `502627b7d53c9057e377b03957b3d464898f2a3c`
- Size/Body Text/Body 2: `7af7f57ba9138110f4367e7b08941a4276bfeb7b`
- Size/Body Text/Body 3: `c2c27df7f2810c1d33890150987d5da3e7ebf890`
- Size/Body Text/Body 4: `c63599d9aeffe257a0deef52edb5296a44a9f898`
- Size/Body Text/Body 5: `4afc36a0825a606892a77cd80dadad7614615479`
- Size/Button Text/Button Lg: `acf2759063cc228eb5881fa1c76b9f3fa6b07824`
- Size/Button Text/Button Md: `0f64057f19e45fc8a1b7eb3358190c7c79b37011`
- Size/Button Text/Button Sm: `f3f62b6586ac63a1ee12bd0554e5c27e378652e6`
- Size/Button Text/Button Xs: `4dd7951e52a532bc6c03a52426225acfaeddc028`
- Size/Input Fields/Label Text: `fd8198d7fdd47053b57ccf7201432eba0dd7fd92`
- Size/Input Fields/Placeholder and default: `575e10744458ff74570edfddd65d572744ebd756`
- Size/Input Fields/Small Text: `22073d19be3b0251c7e258358aa721b2b9f255c9`
- Size/Input Fields/Extra Small Text: `99c14c05f67d112a5ba4370a8a69e4d9c967986d`
- Line Height/Headlines/H3: `bbcf8cf8668f6edea05369c634451f9d905a7169`
- Line Height/Headlines/H4: `e4c715c11062a102e3ba1f68ef7577a41ac87657`
- Line Height/Headlines/H5: `07a4fcd36df252558200b5e277987f661aeccc92`
- Line Height/Headlines/H6: `86a187adb1311e6129c3d00af050f77eefb666e7`
- Line Height/Body Text/Subtitle 1: `a02e9ef35b2206003f3607bef7997bf9b7260d31`
- Line Height/Body Text/Subtitle 2: `df70d0f471d2c8cafd7a5459f2fa22fca8ba5891`
- Line Height/Body Text/Subtitle 3: `c53234274606aee69b673cceecbcc0744e2909b0`
- Line Height/Body Text/Body 1: `866480ac08b83a715f40240d2de220a2da22b043`
- Line Height/Body Text/Body 2: `a57e84d728e6af37f33dc8a7b227686576e08773`
- Line Height/Body Text/Body 3: `d56b13ca63d4273e0d37e7e19aa6d00915eb61cd`
- Line Height/Body Text/Body 4: `fbe7a781acf298e1a71db47940b338ceeffced7b`
- Line Height/Body Text/Body 5: `786a65bbeafeec9928b8f2d8ff5b7a7dd406c5af`
- Line Height/Button Text/Button Lg: `a0d4968ddfbdc3edc4af5431664a4f2427dce5da`
- Line Height/Button Text/Button Md: `f2c247d5cad8c3b84e20091ce49740b51f39f727`
- Line Height/Button Text/Button Sm: `77eeac63b44ec6b47e97271486190b9cb81e90b4`
- Line Height/Button Text/Button Xs: `b010ea2883d1a85fa3e22c2752ea57f820cf9217`
- Line Height/Input Fields/Label: `ae5f97e1afad53ee2377c394a7f12c8836b91230`
- Line Height/Input Fields/Place holder and default: `19c81c86a71164e8ab78a3232bc255a030516b0b`
- Line Height/Input Fields/Erorr Text: `7fe5b0e167e23be59edb18079be5b1ff6b86fa4f`
- Font/Family: `6b1a530d1349bf1f8e4849ebb3c8db62b383d65a` (STRING)
- Font Weight/Regular: `24c90391c7283d7087623024c94cc9d8c3421c7c` (STRING)
- Font Weight/Medium: `d17cff873ac766f069e1233447630c3d746f53cf` (STRING)
- Font Weight/Semi Bold: `8eb74989de1ebf153de1e2c4d817ebb5326997ef` (STRING)

### Theme Collection - key=`2d882bc4867df9ea5b355939c139de0617c744b8`
(Empty - no variables)

---

## API Patterns for Using Components

### Import & instantiate a component variant:
```js
const component = await figma.importComponentByKeyAsync('COMPONENT_KEY');
const instance = component.createInstance();
parentFrame.appendChild(instance);
```

### Import & apply a text style:
```js
const style = await figma.importStyleByKeyAsync('STYLE_KEY');
textNode.textStyleId = style.id;
```

### Import & bind a variable for fill:
```js
const variable = await figma.variables.importVariableByKeyAsync('VARIABLE_KEY');
node.fills = [figma.variables.setBoundVariableForPaint(
  { type: 'SOLID', color: { r:0, g:0, b:0 } }, 'color', variable
)];
```

### Set variable for fontSize/lineHeight:
```js
const sizeVar = await figma.variables.importVariableByKeyAsync('SIZE_KEY');
textNode.setBoundVariable('fontSize', sizeVar);
```
