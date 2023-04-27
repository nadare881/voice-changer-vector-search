# upload guide
本ドキュメントでは、データベース用にデータをアップロードするためのガイドを提供します。

## step1: 話者情報抽出モデルを用意する
本アプリケーションでは[pyannoteのembeddingモデル](https://huggingface.co/pyannote/embedding)を用いて話者に関する特徴量を用意します。
pyannoteの規約に同意し、HuggingFaceのTokenを用いてモデルを利用できるようにしてください。
また、実行時にはローカルのモデルのパスを利用することも可能です。ローカルへのモデルのDLの方法も[pyannoteのページ](https://huggingface.co/pyannote/embedding)に同意してください。

## step2: 変換元データを用意する
本アプリケーションでは[ITAコーパス](https://github.com/mmorise/ita-corpus)を用いた音声を用いてDB用のembeddingを作成します。
各音声データベースのライセンスを確認したうえで、データを用意してください。

