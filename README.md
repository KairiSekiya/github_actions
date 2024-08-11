# github_actions

## GitHub actionsのワークフローを設定する
- リポジトリを開き、「Actions」を選択
- Browse all categories
  - Deployment : サーバーの公開など「デプロイ」に関するワークフロー
  - Security
  - Continuous integration : ソースプログラムのビルドなどに関するワークフロー
  - Automation : 自動化に関するワークフロー
  - Pages
- 「Automation」-「Greetings」-「configure」
- ワークフローはyamlファイルで作成される
- 「commit changes ..」、「commit changes」
- 「.github/workflows」の配下にyamlファイルが作られる
- ブランチを作成して、プルリクエストを送る（今回はプルリクエストがactionsのきっかけなので）