# naotocchi-playtest

なおとっちの 試遊用ページです（制作者の 確認用）。

- 元にした 版: Naoto214/naotocchi の ブランチ `claude/jolly-cray-xeq38x-game`（コミット e3974381d・BGM VERSION 2 統合）
- 保存データは 名前に `naotocchi-playtest:` を 付けて 本番と 分けて います（`playtest-reset.html` で 試遊版の データだけ 消せます）
- 検索エンジンに 載せない 指定（robots noindex）を 全ページに 入れて います
- `bgm-v2/`: 採用32曲 VERSION 2（PR #539）の 試聴ページ（1曲・連続・ループ）。音源は `audio/v2/` の V2 AAC（PR #539 と バイト一致）
- `bgm-v3/`: VERSION 2／VERSION 3 比較試聴ページ（V3 は `audio/v3/`）
- `bgm-v4/`: VERSION 3／VERSION 4 比較試聴ページ（ホーム4曲が 先頭。同じ 位置の まま 切りかえ）
- ゲームの BGM（`assets/bgm/*.m4a`）は VERSION 4（Naoto214/naotocchi の ブランチ `claude/jolly-cray-xeq38x-v4`）に 差し替え。V3 は `audio/v3/`、V2 は `audio/v2/` に 残す。曲ID・曲名・長さ・ループ・再生条件・音量・セーブデータは 変えて いない。`catalog.js` の file に `?v=` を 付けて 古い 音源の キャッシュを 避ける
