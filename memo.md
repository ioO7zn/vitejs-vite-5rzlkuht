# 用語

## DOMとは

- Document Object Modelの略
- HTMLなど解釈し木構造で表現したもの

## 仮想DOMとは

- いきなりDOMを操作せず、JS上で仮想DOMを操作し差分をだしてからDOMに反映

## モジュールバンドラーとは

- 複数のjs(css/image)ファイルを1つにまとめるためのもの(本番環境において)
    - webpack
    - Vite

## トランスパイラとは

- 新しいJavaScriptの記法を古い記法に変換してくれる
    - BABEL
    - SWC(Next.jsは内部的にSWCを使用)

## SPAとは

- Single Page Applicationの略
- モダンJavaScriptはSPAが基本
- HTMLは1つのみでJavaScriptで画面を書き換える
- SPAのメリット
    - ページ遷移毎のちらつきがなくなる
    - 表示速度のアップによるユーザー体験向上
    - コンポーネント分割が容易になることでの開発効率アップ

