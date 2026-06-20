# Kaggle Learn Pandas 演習 — Colab完結版

Kaggle Learn の [Pandasコース](https://www.kaggle.com/learn/pandas) をもとに、ファイル入出力の2問を除く全6章・33問を一冊にまとめた日本語学習用Notebookです。

`.ipynb` をGoogle Colabで開くだけで始められます。外部データ、Kaggle認証、Google Drive、`git clone`、ファイルパス設定は不要です。

各問題は次の3セル構成です。

1. 問題セル（Kaggle原文＋日本語要約）
2. 解答入力セル
3. 模範解答＋日本語コード解説セル

画像に表が掲載されている問題も、列名・行名・数値をコピー可能なCSV形式で問題セル内に明記しています。画像を開かなくても、問題文だけで求める結果が分かります。

## Notebook

- `kaggle_pandas_complete_exercises_ja.ipynb`

## 実行環境

- Python 3
- NumPy（最新版）
- pandas（最新版）

Google ColabでNotebookを開き、冒頭の「Google Colab 初回セットアップ」セルから順番に実行してください。Notebook内の `%pip install -U` により、必要なライブラリを実行時点の最新版へ更新します。

練習用のDataFrameは各章の冒頭でコードから作成します。解答入力セルは初期状態ではコメント化されているため、Colabの「すべてのセルを実行」でも最後までエラーなく実行できます。末尾には主要な結果を検証するセルもあります。

## 出典・ライセンス

問題原文と基本解答は [Kaggle/learntools](https://github.com/Kaggle/learntools/tree/master/notebooks/pandas/raw) の `ex_0.ipynb`〜`ex_5.ipynb`（参照コミット `8a8d4450a699c864febc419fb27ec41443a5942b`）を元にしています。

原著作物は Apache License 2.0 で提供されています。本リポジトリのNotebookは、全章の統合、日本語要約・解説、学習用セル構成を追加した変更版です。詳細は `LICENSE` と `NOTICE` を参照してください。
