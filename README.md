# d-fre-site

D-Fre の LP（ランディングページ）と各種法的文書（プライバシーポリシー・利用規約）を配信する静的サイト。

## ホスティング

- **Cloudflare Pages**（無料枠）
- 公開 URL: `https://d-fre-site.pages.dev/`（デプロイ後に確定）

## 構成（予定）

| ファイル | 用途 |
|---------|------|
| `index.html` | LP トップ（アプリ紹介・DL ボタン・PWA 起動ボタン） |
| `privacy.html` | プライバシーポリシー |
| `terms.html` | 利用規約 |
| `assets/` | ロゴ・スクリーンショット・CSS |

## デプロイ手順

詳細は `.company/governance/standards/privacy-policy-howto.md` を参照。

要点:
1. GitHub に push
2. Cloudflare Pages でリポジトリ連携
3. ビルドコマンド空欄、出力ディレクトリ `/`
4. 自動でデプロイ → URL 取得

## 関連リポジトリ

- アプリ本体: `cc_dir/company/.company/development/code/d-fre/`（別リポジトリで管理予定）
