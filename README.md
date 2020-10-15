# ハンズオン構成

## ハンズオンのターゲットレベル

### ターゲット

- 初めて高機能テキストエディタとして VS Code にふれる方 -> この体験でテキストエディタを積極的に使おうと思えるようになる
- 他の高機能テキストエディタを使用していて、VS Code を味見をしてみたい方 -> VS Code の作法がわかること
- なんとなく VS Code を使っている方 -> VS Code の一通りの使い方、カスタマイズ方法を体験できること

### ターゲットにしない

- プログラミング言語での活用方法を知りたい人

## 進め方

- VS Code の画面と、ワークスペースを理解しようを解説
- それぞれの操作を解説

## コンテンツ

- VS Code の画面と、ワークスペースを理解しよう
  - やってもらうこと: git をチェックアウト、もしくは github から ZIP をダウンロードして解凍し、フォルダーをドラッグして、ワークスペースを開く
  - 扱うこと: 画面構成、ワークスペース、エディター、パネル
  - ゴール: フォルダーを開くことができること
- VS Code のインストールしよう
  - やってもらうこと: VS Code をインストールして、表示言語を日本語に設定する
  - 扱うこと: インストール、日本語設定
  - ゴール: インストールが完了し、日本語設定ができていること
- Markdown を書いてみよう
  - やってもらうこと: エクスプローラータブでファイルを新規作成し、README.md を開いて編集し、ファイルを保存して、プレビューする
  - 扱うこと: エクスプローラータブ、ファイルの保存、プレビュー
  - ゴール: エクスプローラータブからファイルを開いて、編集ができること
- 検索して、ファイルを一気に置換しよう
  - やってもらうこと: ファイル内置換を使って、
  - 扱うこと: ファイル内検索、検索ビュー
  - ゴール: ファイル内検索と、検索ビューを使って、一括置換ができること
- 拡張機能をインストールして、コマンドパレットから呼び出そう
  - やってもらうこと: 拡張機能 [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) をインストールして、フォーマットを行う。[Markdown](https://marketplace.visualstudio.com/items?itemName=AlanWalk.markdown-toc)をインストールして、Table of Contents を追加する。[TOC Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf) をインストールして、PDF を出力する
  - 扱うこと: 拡張機能のインストール、コマンドパレット、コマンド検索、ファイル検索、シンボル検索
  - ゴール: 拡張機能がインストールできること、コマンドパレットの呼び出し方がわかること
- 拡張機能をインストールして、Markdown をチェックさせよう
  - やってもらうこと: 拡張機能 Markdown Lint と、Code Spell Checker をインストールして、リントエラーを修正する
  - 扱うこと: 問題パネル
  - ゴール: 目的のリントツールが実行できること、問題パネルが使えること
- Git でファイルをコミットしよう
  - やってもらうこと: Git のファイルコミットする、github アカウントを持っている場合、フォークして push する
  - 扱うこと: Git タブ、コミット、ブランチの作成、ブランチの変更
  - ゴール: ソースコントロールビューを使った変更差分の確認と、コミットができること。ステータスバーのブランチの変更ができるようになること。
- 自分好みにカスタマイズしよう
  - やってもらうこと: 保存した時に自動でフォーマットがかかるように設定する、好みのキーにフォーマットのコマンドを設定する
  - 扱うこと: キーバインド、ユーザ設定 UI、ワークスペース設定の概念
  - ゴール: UI でユーザ設定を変更できること
- スニペットで定型文を簡単に入力しよう
  - やってもらうこと: 週報スニペットを作成してもらい、スニペットでテンプレートを作成する
  - 扱うこと: スニペットの作成、スニペットの使用
  - ゴール: スニペットを使うことができること
- ターミナルを活用しよう

## 逆にこのコンテンツでは扱わないこと

- デバッグ
- タスク
- 拡張機能の開発
- ユーザ設定 JSON
