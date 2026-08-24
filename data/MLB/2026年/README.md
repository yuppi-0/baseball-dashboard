# data/ フォルダについて

ここには run.py / run_mlb.py が出力する **非公開データ** が入ります。
- raw/            取得した生データ
- games/datamart/ 中間集計（xlsx）

これらは GitHub Pages では公開されません（docs/ の外にあるため）。
ただし git 管理はされる（バックアップとして履歴が残る）ので、公開したくない
情報（詳細な生ログなど）が入っていないか一度確認してから push してください。

一方、ダッシュボードが実際に読み込む games/json と season は
docs/data/ 配下に出力されます（そちらが GitHub Pages の公開対象です）。
