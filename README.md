# Music Recognizer

## 概要

#### 背景・課題

- 歌の練習や、誰かと一緒に歌ったものを振り返るために、カラオケで録音するニーズは計り知れない。
- しかし、録音ファイルには楽曲タイトルなどのメタ情報は付与されておらず、設定するためには手動で付与する必要がある。

#### 目的・アイデア

- 録音ファイルに対して楽曲タイトルなどのメタ情報を付与するツールを開発する。
- 公開されているWebAPIを利用することで、楽曲認識を実現する。

#### 処理概要

- ツール起動
- 処理対象フォルダパスを入力する
- 対象フォルダ配下の録音ファイルに対し、楽曲認識APIを実行してメタ情報を取得する。
- アーティスト毎にフォルダ分類したうえで、ファイル名に楽曲タイトルを付与する。
