# SNS運用代行くん（先行予約特典）

- 出どころ: N1特典。2026-11-17にinoが共有したLstepリンク先のGoogle Driveフォルダ「SNS運用代行くん（先行予約特典）」（所有者 funnel.n1）から取得
- 中身: Claude Code用のAI社員パック。企画→台本→サムネ→運用管理→月次報告→営業提案、を担当する想定のスキル5本と役割定義
- 構成: 使い方md / sns-unyou-daikou-kun一式（CLAUDE.md＝役割定義、README.md＝セットアップ手順、memory/account-profile.md＝アカウント記入シート、.claude/skills/ にスキル5本）

## スキル5本
- sns-kikaku-30: 投稿企画30本の生成
- sns-script-gen: 台本（フック・構成・CTA）の生成
- sns-thumbword-gen: サムネイル・表紙テキスト案の生成
- client-report-gen: 月次クライアント報告書の生成
- account-diagnosis-proposal: アカウント診断結果（6分野・30項目チェック）を営業提案書に変換

## CREW HOUSE 402「SNS提案書くん」との関係
- CREW HOUSE（ひだまりハウス）402のSNS提案書くん本体は、ページ内の「スキルを受け取る」ボタンが無反応で取得できないことを2026-11-21に実測で確認済み
- 役割が同等の実スキルが上記 account-diagnosis-proposal で、本パック経由で取得・収録済み

## GitHubに入れていないもの
- zip原本（SNS運用代行くん.zip）はバイナリのため未収録。原本と展開済み一式は、むぎ側の `~/workspace/sns_unyo_daiko_kun/` に保持
- 管理シート（Googleスプレッドシート）とセットアップガイド（Notionリンク）も外部リンクのため未収録。リンクは使い方md内に記載あり
- 提供元の売上等の数字は提供者主張として扱い、検証済み事実とは分ける
