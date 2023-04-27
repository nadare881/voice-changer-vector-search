# voice-changer-vector-search (Ver 0.0.1)
本リポジトリはボイスチェンジャーの変換結果を比較し、類似した音声のデータセットや学習済みモデルを検索するためのリポジトリです。

現在はPoC版で、コンセプト検証の結果のみ公開しています。

## 概要
本リポジトリでは音声変換モデル、及び音声変換の学習に用いてよい音声データの収集を行います。
話者情報をembeddingに変換し、メタ情報と共に管理することで音声のベクトル検索をサポートします。

embedding・メタデータをMITライセンスにおいて公開していただけるという条件を承諾していただいたものについてのみ公開・管理予定です。

### ver 0.0.1
ver0.0.1では類似音声検索のPoCとして[JVSコーパス](https://sites.google.com/site/shinnosuketakamichi/research-topics/jvs_corpus)の話者分類、及びそのembeddingの分析結果を公開します。

[こちらのnotebookを確認してください。](poc/working/VoiceVectorSearch_PoC_notebook.ipynb)
