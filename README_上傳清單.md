# 待上傳_0917:線上資產主機缺漏 / 過期檔(ENG-P0-06 逐檔 HTTP+SHA256 實測,2026-09-17)

主機:https://a0963810728-dot.github.io/wanshen-assets/(repo a0963810728-dot/wanshen-assets,最後一次 commit 2026-09-11 00:41 UTC)
做法:GitHub 網頁 → Add file → Upload files → 把本資料夾 23 個 .glb 全部拖進去(同名覆蓋)→ Commit。完成後告知工程重跑 `node tools/verify-online-assets.js`。

| 檔 | 線上現況 | 本機位元組 | 本機 SHA256 |
|---|---|---|---|
| mob_baiyuan.glb | ONLINE_STALE | 387928 | 583f8b1f5bfda58ad7c9d7bda3fd78195f99b6f173a371210d017868c96f73a6 |
| mob_dengxiahua.glb | ONLINE_STALE | 1181384 | 112fd03d5cf9ee891ab800e0075627189cdf0082ebfaa9ff21ab0575b1de0c25 |
| mob_huxiang.glb | ONLINE_STALE | 1409112 | 2cd66b279ea08550c10c5ec28b533e431d081a5a954badb0510ee4e075381b87 |
| mob_ns_guangze.glb | ONLINE_STALE | 539548 | c433c953eade622cb15bcd7ddb105b65ddf971a7fbdabfa00d4efdd051f590f3 |
| mob_ns_mazu.glb | ONLINE_STALE | 1438472 | 257fcb8b741dbb9595c17927a66ec7c2ac2be135ebe4c4fa82b9fe42f82add80 |
| mob_ns_nezha.glb | ONLINE_STALE | 1423520 | 8960c7002eee5426db91a343af89427ad74201b6336dac9f0e94b7a0bfa39e8f |
| mob_ns_zhenwu.glb | ONLINE_STALE | 1348028 | d8a4aaa92d6393050037c5e2b15a0a5984f7b6944405ffee6940c9452eca9565 |
| mob_qiyuan.glb | ONLINE_STALE | 1393812 | 21adea6e9dadfa70f89942626dbfc941eefa54f0199de29553c2030b74937cfb |
| mob_shenmen.glb | ONLINE_STALE | 266740 | 2c5baf05344a9315c78716ab92dcfa24b70a0768c50d36b5b745a41b147b2b98 |
| mob_shoudeng.glb | ONLINE_STALE | 1293612 | cc92ca0a0215d971500e8b90d9454b9be130ae493d404cbc8468e57b968ac2d5 |
| mob_tianjie.glb | ONLINE_STALE | 1381672 | 381cbca125e83385d7ffbdf88c6f5cc24a2338c7bbfaa4cc50d436cad9bc44b0 |
| mob_wanyuan.glb | ONLINE_STALE | 1525540 | e4944e45218ac4042d7a5c8143a02100d93178add1c3bf7049137b0f0553cc1f |
| mob_wuming.glb | ONLINE_STALE | 208652 | c37a99ada993dc05ca39e8927a57f0249288aa6bdba1edb7a63d105d19bcdcd8 |
| mob_xianghuo.glb | ONLINE_STALE | 299800 | b51388cfe8ab5924b0426be56dfbd003942c7d1abc6a87f79676a238c20da95a |
| mob_zhenjie.glb | ONLINE_STALE | 1388144 | 8b2d03f2ea9449d363a125135fe485fc1100350d964e8b2ae4317c162d4bfe5f |
| mob_zhenshan.glb | ONLINE_STALE | 1415204 | 2cfefa51edb992dd95c9163868f5aa303f58c8d95fc7e827aa7980af951c50a9 |
| mob_zhentian.glb | ONLINE_STALE | 218460 | 66830817515e8c800f05437df8507494941c900d76851fc4e1cacec0ab281a64 |
| mob_zhenxie.glb | ONLINE_STALE | 1411728 | 49214449734828e2a6acdbd11837a46058027049131b6ac58471409862d971ca |
| pc_dizang_f.glb | HTTP_404 | 1048988 | 4b4b65ad6480b40db571aa7347861ed45716a29db186abe02c672f05beb65c15 |
| pc_guandi_f.glb | HTTP_404 | 1112888 | adec8afbb66a0574d7766876c3d7ddbe3a07f668f198ef872d6b17df9d7199ec |
| pc_guangze_f.glb | HTTP_404 | 1064456 | 7090bc62fceefd822f8cd670e72b8b3455f97864bbc0c0e7fb0f77df39320ec5 |
| pc_mazu_f.glb | HTTP_404 | 1164552 | 38f24bac2caff5fb94930621a66586aa6082aca4da53c88b7d9b7104f2cdf659 |
| pc_zhenwu_f.glb | HTTP_404 | 1051500 | 6bc4b766e5d716db774578ca6724e257bace8f331cdf80f7417690e81372f38a |
