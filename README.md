# Kaggle Learn Pandas 全演習

Kaggle Learn の [Pandasコース](https://www.kaggle.com/learn/pandas) に収載された全6章・全35問を、一冊にまとめた日本語学習用Notebookです。

各問題は次の3セル構成です。

1. 問題セル（Kaggle原文＋日本語要約）
2. 解答入力セル
3. 模範解答＋日本語コード解説セル

## Notebook

- `kaggle_pandas_complete_exercises_ja.ipynb`

## 実行環境

- Python 3
- NumPy 1.26.4
- pandas 2.2.3

Google ColabでNotebookを開き、冒頭の「Google Colab 初回セットアップ」セルから順番に実行してください。必要なライブラリはNotebook内で固定バージョンをインストールします。

ワインレビューなどの外部データを使う章は、Kaggle NotebookへNotebookをImportし、右側の **Add Input** から元問題で指定されたデータセットを追加してください。

主なデータセット:

- [Wine Reviews](https://www.kaggle.com/datasets/zynicide/wine-reviews)
- [Things on Reddit](https://www.kaggle.com/datasets/residentmario/things-on-reddit)
- [Powerlifting Database](https://www.kaggle.com/datasets/open-powerlifting/powerlifting-database)

## 出典・ライセンス

問題原文と基本解答は [Kaggle/learntools](https://github.com/Kaggle/learntools/tree/master/notebooks/pandas/raw) の `ex_0.ipynb`〜`ex_5.ipynb`（参照コミット `8a8d4450a699c864febc419fb27ec41443a5942b`）を元にしています。

原著作物は Apache License 2.0 で提供されています。本リポジトリのNotebookは、全章の統合、日本語要約・解説、学習用セル構成を追加した変更版です。詳細は `LICENSE` と `NOTICE` を参照してください。
