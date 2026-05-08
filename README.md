<div align="center">
  <img src="docs/icon-256.png" alt="FairyOperator" width="160" height="160" />
  <h1>FairyOperator</h1>
  <p>macOS の入力・ウインドウ・Dock の操作を、妖精たちが手伝ってくれます。</p>
  <p>
    <a href="https://github.com/piggest/FairyOperator-releases/releases/latest"><img src="https://img.shields.io/github/v/release/piggest/FairyOperator-releases?label=latest&color=8a76d6" alt="latest release" /></a>
    <a href="https://piggest.github.io/FairyOperator-releases/"><img src="https://img.shields.io/badge/website-Pages-8a76d6" alt="website" /></a>
    <img src="https://img.shields.io/badge/macOS-13%2B-blue" alt="macOS 13+" />
  </p>
</div>

---

## 概要

FairyOperator は、macOS を手伝う妖精たちを集めた小さな道具箱です。それぞれの機能を「妖精」と呼び、必要なものを設定画面から個別に有効にして使えます。

- **キー入れ替えの妖精** — 外付けキーボードごとに、自由にキーを再マッピングできます。
- **アプリ切り替えの妖精** — Cmd+Tab を置き換える切り替えパネルを呼び出せます。Unity プロジェクトのアイコンも自動で検出します。
- **クリップボードの妖精** — コピー履歴を保持し、検索や呼び出しがすばやく行えます。
- **ウインドウ操作の妖精** — ホットキー一つでウインドウを分割・最大化・別画面へ移動できます。
- **IME 操作の妖精** — 日本語入力のオン／オフを、好きなキーやアプリ単位で切り替えられます。
- **メニューバーの妖精** — アプリメニューを一時的に隠して、ステータスアイコンの表示領域を広げられます。
- **Dock 拡張の妖精** — Dock のアイコンにウインドウ数や応答状態などの情報を追加で表示します。
- **スリープ抑止の妖精** — 必要なときだけ macOS のスリープを抑止し、不要になれば自動的に元に戻します。

詳しい機能や設定項目は [機能ガイド](https://piggest.github.io/FairyOperator-releases/guide.html) を参照してください。

## ダウンロード

最新版は [Releases](https://github.com/piggest/FairyOperator-releases/releases/latest) ページから `.dmg` または `.app.zip` を取得できます。

```
# .app.zip をダウンロード後
unzip FairyOperator.app.zip -d /Applications/
xattr -dr com.apple.quarantine /Applications/FairyOperator.app
open /Applications/FairyOperator.app
```

> Developer ID で署名し、Apple の Notarization も通しています。そのため、Gatekeeper の警告は表示されません。

## スクリーンショット

<div align="center">
  <img src="docs/screenshots/settings.png" alt="設定画面" width="680" />
</div>

## 必要環境

- macOS 13 (Ventura) 以降
- アクセシビリティ権限（キー入れ替え・ウインドウ操作・Dock 拡張などで使用します）
- 入力モニタリング権限（キー入れ替えで使用します）
- 画面収録権限（ウインドウのサムネイル取得時にのみ使用します）

## ライセンス

このリポジトリは、バイナリ配布とランディングページの公開を目的としています。ソースコードは別のリポジトリで管理しています。

## 関連リンク

- [ランディングページ](https://piggest.github.io/FairyOperator-releases/)
- [機能ガイド](https://piggest.github.io/FairyOperator-releases/guide.html)
- [Releases](https://github.com/piggest/FairyOperator-releases/releases)
- [Issues](https://github.com/piggest/FairyOperator-releases/issues)
