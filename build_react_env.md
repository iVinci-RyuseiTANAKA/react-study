# 環境構築のメモ
## node.js を最新にする
### nvm が入っていることを確認
```zsh
% nvm -v
0.39.1
```
### node 最新のLTSをインストール
```zsh
% nvm install --lts
```
### 最新のLTSに切り替える
```zsh
% nvm use --lts
```

***
## react の雛形を作る
### 作業用ディレクトリへ移動
```zsh
% cd react-study
```
### ディレクトリが空であることを確認し雛形を作る
```zsh
% npx create-react-app .
```

### 起動確認
```zsh
% npm start
```

### Material UI インストール
```zsh
% npm install @mui/material @emotion/react @emotion/styled
```

### React-Router インストール
```zsh
% npm install react-router-dom@6
```
