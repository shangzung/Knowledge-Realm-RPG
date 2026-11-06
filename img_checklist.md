# 知識之城 RPG — 圖片製作清單

## 規格(全部通用)

- 格式:**PNG,透明背景**(沒有透明背景,角色會帶著白色方框)
- 尺寸:**512 × 512 像素**正方形,角色置中、四周留約 8% 空白、腳踩在底部
- 大小:每張建議 **300KB 以內**(可用 tinypng.com 壓縮)
- 檔名:**全小寫英文 + 數字,不要空格、不要中文**
- 資料夾:在 `index.html` 旁邊建立 `img` 資料夾,所有圖片放進去

```
你的資料夾/
├─ index.html
└─ img/
   ├─ hero_warrior.png
   ├─ mon_m01.png
   └─ ...
```

**不用一次做完**:有哪張圖就換哪張,沒有的圖遊戲會自動用現有的插圖(Boss 則用 emoji)。

## 統一畫風提示詞(每張都加在最前面,畫風才會一致)

```
cute chibi children's game character illustration, storybook watercolor style, soft thick outline, vibrant warm colors, big sparkling eyes, full body, single character, centered, plain white background, no text, no shadow
```

接著在後面加上角色描述,例如:`a brave boy warrior with brown hair, blue armor, red cape, holding a sword`

去背小技巧:生成時用純白背景,再丟進 remove.bg 或 Photoshop / Photopea 去背,存成 PNG。

## 第一批(最優先,共 14 張)

| 檔名 | 內容 |
|---|---|
| hero_warrior.png | 戰士:棕髮男孩、藍色盔甲、紅披風、拿劍 |
| hero_mage.png | 魔法師:粉紅長髮女孩、紫色尖帽、拿法杖 |
| hero_archer.png | 弓箭手:綠色兜帽、拿弓 |
| hero_engineer.png | 工程師:戴護目鏡的帽子、吊帶褲、拿扳手 |
| hero_conductor.png | 列車長:深藍制服與制帽、拿小旗 |
| mon_m01.png | 加法史萊姆:藍色史萊姆,頭上有嫩芽 |
| pet_p1_0.png | 小貓(第一階) |
| pet_p2_0.png | 小狗(第一階) |
| pet_p3_0.png | 企鵝(第一階) |
| pet_p4_0.png | 狐狸(第一階) |
| pet_p5_0.png | 兔子(第一階) |
| pet_p6_0.png | 貓頭鷹(第一階) |
| pet_p7_0.png | 小恐龍(第一階) |
| pet_p8_0.png | 小火車精靈(第一階) |

## 寵物(共 24 張:8 種 × 3 階段)

檔名格式:`pet_寵物編號_階段.png`,階段 0 = 第一階、1 = 第二階、2 = 第三階

| 檔名 | 進化線 |
|---|---|
| pet_p1_0 / pet_p1_1 / pet_p1_2 | 小貓 / 劍士貓 / 聖光獅王 |
| pet_p2_0 / pet_p2_1 / pet_p2_2 | 小狗 / 巡邏犬 / 皇家聖伯納 |
| pet_p3_0 / pet_p3_1 / pet_p3_2 | 企鵝 / 紳士企鵝 / 冰晶帝王企鵝 |
| pet_p4_0 / pet_p4_1 / pet_p4_2 | 狐狸 / 九尾靈狐 / 天狐仙子 |
| pet_p5_0 / pet_p5_1 / pet_p5_2 | 兔子 / 月光兔 / 星辰玉兔 |
| pet_p6_0 / pet_p6_1 / pet_p6_2 | 貓頭鷹 / 博士貓頭鷹 / 智慧大賢梟 |
| pet_p7_0 / pet_p7_1 / pet_p7_2 | 小恐龍 / 暴龍 / 知識龍 |
| pet_p8_0 / pet_p8_1 / pet_p8_2 | 小火車精靈 / 蒸汽機神 / 銀河超特快精靈 |

## 區域 Boss(共 9 張)

| 檔名 | Boss |
|---|---|
| boss_0.png | 第1章 初心村:初心守護木偶王 |
| boss_1.png | 第2章 注音森林:聲調精靈女王 |
| boss_2.png | 第3章 數學平原:四則運算巨像 |
| boss_3.png | 第4章 閱讀峽谷:古卷奇美拉 |
| boss_4.png | 第5章 英文港口:深海字母克拉肯 |
| boss_5.png | 第6章 科學研究所:知識機器人 Mk-II |
| boss_6.png | 第7章 知識王國:皇家博學黃金龍 |
| boss_7.png | 第8章 智慧神殿:全知智慧大天使 |
| boss_weak.png | 錯題大魔王(紫黑色的小惡魔大王) |

## 52 隻怪物

檔名格式:`mon_編號.png`,編號和下表一致

| 檔名 | 怪物 | 出沒區域 |
|---|---|---|
| mon_m01.png | 加法史萊姆 | 初心村 |
| mon_m02.png | 減法史萊姆 | 初心村 |
| mon_m03.png | 色彩小蘑菇 | 初心村 |
| mon_m04.png | 形狀方塊怪 | 初心村 |
| mon_m05.png | 蘋果精靈 | 初心村 |
| mon_m06.png | 初心小木靈 | 初心村 |
| mon_m07.png | ㄅㄆㄇ樹精 | 注音森林 |
| mon_m08.png | 拼音松鼠 | 注音森林 |
| mon_m09.png | 二聲飛鳥 | 注音森林 |
| mon_m10.png | 三聲跳跳蛙 | 注音森林 |
| mon_m11.png | 四聲閃電蜂 | 注音森林 |
| mon_m12.png | 輕聲棉花怪 | 注音森林 |
| mon_m13.png | 生字小書蟲 | 注音森林 |
| mon_m14.png | 乘法哥布林 | 數學平原 |
| mon_m15.png | 除法騎士 | 數學平原 |
| mon_m16.png | 九九乘法狼 | 數學平原 |
| mon_m17.png | 時鐘貓頭鷹 | 數學平原 |
| mon_m18.png | 金幣寶箱怪 | 數學平原 |
| mon_m19.png | 分數飛龍 | 數學平原 |
| mon_m20.png | 小數刺蝟 | 數學平原 |
| mon_m21.png | 閱讀蝙蝠 | 閱讀峽谷 |
| mon_m22.png | 成語石像鬼 | 閱讀峽谷 |
| mon_m23.png | 標點符號妖 | 閱讀峽谷 |
| mon_m24.png | 修辭火狐 | 閱讀峽谷 |
| mon_m25.png | 詩詞仙鶴 | 閱讀峽谷 |
| mon_m26.png | 故事羊皮紙 | 閱讀峽谷 |
| mon_m27.png | 寓言穿山甲 | 閱讀峽谷 |
| mon_m28.png | 英文企鵝 | 英文港口 |
| mon_m29.png | 單字海鷗 | 英文港口 |
| mon_m30.png | 文法寄居蟹 | 英文港口 |
| mon_m31.png | 句型海豚 | 英文港口 |
| mon_m32.png | ABC水母 | 英文港口 |
| mon_m33.png | 發音海豹 | 英文港口 |
| mon_m34.png | 航海燈塔怪 | 英文港口 |
| mon_m35.png | 自然機器人 | 科學研究所 |
| mon_m36.png | 磁力線圈怪 | 科學研究所 |
| mon_m37.png | 光學稜鏡獸 | 科學研究所 |
| mon_m38.png | 齒輪守衛 | 科學研究所 |
| mon_m39.png | 電流精靈 | 科學研究所 |
| mon_m40.png | 重力浮游球 | 科學研究所 |
| mon_m41.png | 化學燒瓶怪 | 科學研究所 |
| mon_m42.png | 百分比巨龍 | 知識王國 |
| mon_m43.png | 歷史鎧甲兵 | 知識王國 |
| mon_m44.png | 地理羅盤怪 | 知識王國 |
| mon_m45.png | 公民天秤獸 | 知識王國 |
| mon_m46.png | 面積獅鷲 | 知識王國 |
| mon_m47.png | 速率飛馬 | 知識王國 |
| mon_m48.png | 應用題魔導師 | 智慧神殿 |
| mon_m49.png | 天文星象龍 | 智慧神殿 |
| mon_m50.png | 邏輯斯芬克斯 | 智慧神殿 |
| mon_m51.png | 百科全書魔像 | 智慧神殿 |
| mon_m52.png | 銀河智慧結晶 | 智慧神殿 |
