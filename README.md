# 建築の系譜 / Architecture Atlas

12人の建築家を、歴史的肖像、出典付きの日本語解説、Three.jsによる操作可能な概念模型で紹介する静的Webアプリ。

## 起動

Node.jsで `node server.cjs` を実行し、表示されるローカルURLを開く。追加のnpmインストールは不要。`dist` が配信用ファイル一式。

## 内容

ブルネレスキ、パラーディオ、シナン、ガウディ、ライト、グロピウス、ル・コルビュジエ、ミース、カーン、丹下健三、安藤忠雄、ザハ・ハディド。

各項目に思想・功績、代表作の読み解き、関連作品、一次資料を中心とした参照リンク、肖像の出典を収録。モデルは独自制作の教育用概念模型であり、実測や設計のためには使用できない。省略範囲は各ページに明記。

## 操作

- 建築家を選択。URLのハッシュで直接開ける。
- ドラッグ・矢印キーで回転、ホイール／ピンチ／＋－でズーム。
- 立体／正面／真上、自動回転、ワイヤーフレーム、リセット。
- 見どころボタンで模型の視点と作品解説を連動。
- 解説タブは矢印・Home・Endキーに対応。

## 権利・出典

肖像の出典・作者・ライセンスは [ATTRIBUTIONS.md](ATTRIBUTIONS.md)、`dist/portraits.json`、各ページの「資料」に記載。JPEGは提供元のサムネイルを保存し、画面上でグレースケール・トリミング表示を行う。CC BY-SAの写真を改変したものとして扱う場合、その写真の改変版は同じライセンスに従う。

このプロジェクトで独自に作成したコードと文章は [MIT License](LICENSE)。Three.js r180（MIT）のファイルとライセンスは `dist/vendor`。Noto Sans JP / Noto Serif JPはローカルに同梱し、SIL Open Font License 1.1のもとで配布。詳細は [ATTRIBUTIONS.md](ATTRIBUTIONS.md)。研究内容の確認日は2026年9月21日。

## 継続的な確認

GitHub ActionsはJavaScriptの構文、データと画像の対応、既知の認証情報らしき文字列を検査する。GitHubのSecret Scanning、Push Protection、Dependabot security updatesも有効化済み。

## 配信

Sitesプロジェクト識別子と静的配信先は `.openai/hosting.json`。認証情報は保存していない。
