# セキュリティとプライバシー

AI I Love Youは、攻撃対象領域とデータ収集をできるだけ小さくするために設計された、静的なGitHub Pagesサイトです。

## セキュリティ設計

- JavaScriptや実行可能なクライアント側アプリケーションコードを使用しません
- フォーム、認証、アカウント、データベース、API、サーバー側処理を使用しません
- 第三者素材、埋め込み、フレーム、解析タグ、広告、外部フォントを使用しません
- HTML内に制限の強いContent Security Policyを記載しています
- リポジトリの秘密情報や実行時の認証情報を必要としません
- 依存パッケージとパッケージ管理ツールを意図的に使用しません

## プライバシー設計

サイトコードは、訪問者情報を意図的に収集、保存、プロファイリング、第三者送信しません。Cookie、トラッキングピクセル、フィンガープリンティングコード、アクセス解析スクリプトはありません。

GitHub Pagesは配信基盤です。ネットワーク情報やサービス運用上の情報は、このサイトのソースコードとは独立して、GitHub自身の方針に基づき処理される場合があります。そのため、このプロジェクトはホスティング基盤全体について絶対的なゼロ収集を主張せず、サイト自身をデータ最小化設計と説明します。

## 問題の報告

公開して差し支えない問題は、このリポジトリのGitHub Issueで報告してください。個人情報、認証情報、秘密情報、悪用可能な詳細はIssueに記載しないでください。機密性の高い報告には、リポジトリで利用可能な場合、GitHubのPrivate Vulnerability ReportingまたはSecurity Advisoryを使用してください。

## 保守時の指針

サイトは静的な構成を維持してください。セキュリティとプライバシーへの影響を確認せずに、スクリプト、フォーム、外部リソース、追跡機能、秘密情報、生成依存関係、利用者投稿機能を追加しないでください。

---

# Security and privacy

AI I Love You is a static GitHub Pages site designed to minimize attack surface and data collection.

## Security design

- No JavaScript or executable client-side application code
- No forms, authentication, accounts, database, API, or server-side processing
- No third-party assets, embeds, frames, analytics, advertisements, or external fonts
- A restrictive Content Security Policy is declared in the HTML
- No repository secrets or runtime credentials are required
- Dependencies and package managers are intentionally absent

## Privacy design

The site code does not intentionally collect, store, profile, or transmit visitor information. It contains no cookies, tracking pixels, fingerprinting code, or analytics scripts.

GitHub Pages is the hosting provider. Network and operational information may be processed by GitHub independently of this site's source code and under GitHub's own policies. For that reason, this project describes its own design as data-minimizing rather than making an absolute claim about the entire hosting infrastructure.

## Reporting a problem

Please report non-sensitive problems through a GitHub Issue in this repository. Do not include personal information, credentials, secrets, or exploit-sensitive details in a public issue. For sensitive reports, use GitHub Private Vulnerability Reporting or a Security Advisory when that feature is available for the repository.

## Maintenance guidance

Keep the site static. Avoid adding scripts, forms, external resources, trackers, secrets, generated dependencies, or user-submitted content unless their security and privacy effects have been reviewed first.