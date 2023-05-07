# voice-changer-vector-search (Ver 0.1.1)
本リポジトリはボイスチェンジャーの変換結果を比較し、類似した音声のデータセットや学習済みモデルを検索するためのリポジトリです。

現在はα版で、今後データベースの列名等は追加・削除する可能性があります。。

## 概要
本リポジトリでは音声変換モデル、及び音声変換の学習に用いてよい音声データの収集を行います。
話者情報をembeddingに変換し、メタ情報と共に管理することで音声のベクトル検索をサポートします。

## changelog

### ver 0.1.1
[VOICEVOX](https://voicevox.hiroshiba.jp/)と[SHAREVOX](https://www.sharevox.app/)の読み上げ音声のデータを追加しました。
機械学習に用いる際は必ず各ソフトウェアおよび各キャラクターの規約を確認してください。

### ver 0.1.0
α版を公開しました。許諾不要・許諾確認済みのITAコーパスから得た収集と検索のデモを用意しました。

[notebook/search_similar_voice.ipynb](notebook/search_similar_voice.ipynb)を実行すると音声to音声の検索が可能です。

以下のように音声の類似度を確認可能です。
![image](https://user-images.githubusercontent.com/23290400/236252615-b75d7bdb-710c-416f-9f19-96693a427b59.png)

### ver 0.0.1
ver0.0.1では類似音声検索のPoCとして[JVSコーパス](https://sites.google.com/site/shinnosuketakamichi/research-topics/jvs_corpus)の話者分類、及びそのembeddingの分析結果を公開します。

[こちらのnotebookを確認してください。](poc/working/VoiceVectorSearch_PoC_notebook.ipynb)
