# mememo-legal

iOS/Web アプリ **mememo** のプライバシーポリシー・利用規約・サポート導線を公開する静的サイト。
GitHub Pages で配信します。

## 公開URL

| ページ | URL |
| --- | --- |
| トップ | https://aiokara.github.io/mememo-legal/ |
| プライバシーポリシー | https://aiokara.github.io/mememo-legal/privacy.html |
| 利用規約 | https://aiokara.github.io/mememo-legal/terms.html |

## アプリ側の設定

これらのURLは、アプリの環境変数に設定します。

```
EXPO_PUBLIC_PRIVACY_URL=https://aiokara.github.io/mememo-legal/privacy.html
EXPO_PUBLIC_TERMS_URL=https://aiokara.github.io/mememo-legal/terms.html
EXPO_PUBLIC_SUPPORT_URL=https://aiokara.github.io/mememo-legal/
```

## 原稿の同期

本文の原稿はアプリ本体のリポジトリにもあります。**片方だけを直さないこと。**

- `docs/PRIVACY_POLICY_DRAFT.md` ⇔ `privacy.html`
- `docs/TERMS_OF_USE_DRAFT.md` ⇔ `terms.html`

## 更新手順

1. 該当の `.html` を編集する
2. 各ページの「最終更新日」を更新する
3. commit して `main` へ push（数十秒で反映されます）

## 注意

このリポジトリは **public** です。秘密情報（APIキー、`.env`、証明書）を絶対に置かないでください。
