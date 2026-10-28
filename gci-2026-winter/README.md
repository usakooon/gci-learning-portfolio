# GCI 2026 Winter

| 項目 | 内容 |
| --- | --- |
| 講座名 | GCI グローバル消費インテリジェンス講座 2026 Winter |
| 受講状況 | 受講中（本人申告） |
| 授業回数 | 全13回 |
| 公式講座ページ | [GCI 2026 Winter](https://www.matsuo-institute.com/seminar/gci/gci-2026winter/) |

Python・データ処理・データ可視化・機械学習などを学び、各回の自主練習を記録します。
現在の学習内容は第2回のPython基礎、第3回のNumPyによる科学計算、第4回のpandasによるデータ加工です。

[学習進捗表](../README.md#learning-progress)をトップページで管理します。Notebookは未提供のため、まだ掲載していません。

## Notebook Structure

各Notebookには次の見出しを順に設けます。既存Notebookを追加する場合は、その内容・空欄・実行結果を保持したうえで整理します。

| 見出し | 記録する内容・作成者 |
| --- | --- |
| Learning Objectives（学習目標） | 取り組む項目と到達目標。AIが案を作成した場合はその旨を明記 |
| Practice Problems（練習問題） | 一般的な学習項目からAIが独自に作成した問題。配布課題を転載・言い換えしない |
| My Solutions（自分の解答） | 本人が書いたコード。未解答は空欄のまま残す |
| Outputs（実行結果） | 実際の実行結果と観察。未実行の結果を生成しない |
| Explanations（解説） | 本人が自分の言葉で書く考え方・処理の説明 |
| Key Takeaways（重要な学び） | 本人による振り返り、つまずき、次に確認すること |

コードセルの出力は元のセルに保持します。Outputs節から該当する問題番号・セルの説明を参照する形でも構いません。
問題番号を各節で揃えると、問題・解答・結果・解説を対応づけられます。
Notebook冒頭に作成日・更新日とAIの利用範囲（問題作成、ヒントなど）を記録します。AIによる参考コードがある場合は本人の解答とは別に、AI生成であることを明示します。

## Adding a Notebook

自主練習とNotebookの編集・実行はGoogle Colabで行い、GitHubへ保存します。

保存先は `usakooon/gci-learning-portfolio` の `main` ブランチです。Colabの「ファイル」メニューから「GitHubにコピーを保存」を選び、保存先のファイルパスを例えば `gci-2026-winter/notebooks/02_python_basics.ipynb` に指定します。保存前に公開する出力を確認し、保存後はGitHubでファイルの配置と表示を確認します。
既存Notebookを更新する場合は、GitHubの最新版をColabで開き、同じパスへ保存します。
Colabでの保存後、トップページの進捗表も更新します。この表は手動更新であり、Notebookの保存だけでは自動更新されません。

[Colab公式のGitHub連携ガイド](https://github.com/googlecolab/colabtools/blob/main/notebooks/colab-github-demo.ipynb)

1. `notebooks/` にNotebookを追加します。第2〜4回の予定ファイル名は次のとおりです。
   - `02_python_basics.ipynb`
   - `03_numpy.ipynb`
   - `04_pandas.ipynb`
2. 第5〜13回も `NN_topic.ipynb` の規則で追加します。未着手のNotebookをあらかじめ作る必要はありません。
3. 上記6節を用いて記録し、使用したPython・ライブラリのバージョンと、必要な実行手順をNotebook内に残します。
4. 公開前にセル、実行結果、メタデータ、添付ファイルを確認します。限定資料やデータ、認証情報、個人情報を含めません。
5. トップページの該当行を更新します。Notebook欄には、例えばファイル追加後に `[02_python_basics.ipynb](gci-2026-winter/notebooks/02_python_basics.ipynb)` と記載します（この相対パスはトップページ用です）。

解答・実行結果・解説・振り返りを本人が記録し、公開内容を確認するまでは `Completed` にしません。
AIによる問題作成だけでは本人の解答が完成したことにはなりません。

本ページは個人の学習記録であり、講座の公式資料ではありません。この記録方法の整理・文章作成にはAIを使用しています。

[トップページへ](../README.md)
