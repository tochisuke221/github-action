## 概要
GithubActionの設定を確認するためのリポジトリです

<img width="234" alt="スクリーンショット 2023-09-30 12 03 35" src="https://github.com/tochisuke221/github-action/assets/81346474/9c469e45-5dcd-498d-9212-d2e2d0e84cd5">

## 内容
以下のような実装を行いました
- **プルリク作成時にassigneesを自動決定します**
  - プルリク作成者になります
  - https://github.com/technote-space/assign-author

- **ブランチ名によってラベルを付与します**
  - https://github.com/ffittschen/pr-branch-labeler

- **developブランチにマージされた際に、main向けのリリースプルリクを作成できます**
  - https://github.com/x-motemen/git-pr-release
  - ※以下のプルリク作成権限を付与しておく必要があります。（リポジトリのSettings > Actions > General > Workflow permissionsより下記画像のように権限を付与してください）

<img width="454" alt="スクリーンショット 2023-09-30 11 51 45" src="https://github.com/tochisuke221/github-action/assets/81346474/e5115e7a-a024-4afc-80eb-3b75111844b6">
