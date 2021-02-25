# Github Actionsの軽いお試し
Github Actionsを試しに使ってみたときのリポジトリ。

flake8でlintして、pytestでテストしてくれるGithub Actionsのワークフローテンプレートのやつをそのまま使用。

pytestは特に何もしなければ `test_*.py`を実行する。アサーションがなければテストは合格になる。
```
./github-actions-test/
├── README.md
├── main.py
└── test_1.py

0 directories, 3 files
```