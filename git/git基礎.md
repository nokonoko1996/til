## 2024-10-17
視聴動画  [Git/GitHub入門 ブランチ編](https://dotinstall.com/lessons/basic_gitgithub_branches)

- ステージに上げる
→ `git add ○○`  
- コミット
→ `git commit -m " "`
- **上記二つを合わせる**
→ `git commit -am " "`

- ブランチの確認
→ `git branch`
- ブランチの追加
→ `git branch ○○`
- ブランチの移動
→ `git switch ○○`
- logの確認
→ `git log --oneline`
- 全log（他ブランチ含）の確認
→ `git log --oneline --all`

## 2024-10-18
GitHubでファイルの下に何かを作りたいときはファイル名で`/`を押す

## 2024-10-19
- `git log --oneline --graph`
→ ログをグラフで表示。ブランチの分岐などがわかりやすい。
- `git switch -c ○○`
→ ブランチを作成しつつ移動  
- [ ] もう一度 `git reset` についての動画を確認しておく
