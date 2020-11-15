#Visual Studio CodeでMarkdownを書く際、リンクを挿入するショートカットを設定する
Qiitaのデフォルトエディタ画面だとどうにも違和感があり、設定が済んでいるいるVSCodeで書いた。
思いの外快適であったが、若干痒いところに手が届かなかったので、備忘として書いておく。

## 設定したショートカット
> [VSCode拡張機能 Markdown All in One / Issues:'"Create Link" command #841' より](https://github.com/yzhang-gh/vscode-markdown/issues/841)

```
  {
    "key": "alt+l",
    "command": "editor.action.insertSnippet",
    "when": "editorLangId == 'markdown'",
    "args": {
        "snippet": "[$TM_SELECTED_TEXT$1]($0)"
    }
  },
```
上記を元に、適宜なキーを選ぶなりカーソル位置を指定するなり改変し、VSCodeのkeybindings.json(Preference: Open Keyboard Shortcuts(JSON)より)の良さげなところに挿入

## Visual Studio CodeでMarkdownを書くにあたって導入した拡張機能
安直に、VSCodeの拡張機能で'markdown'と検索して上から2つ入れました。
これで事足りたので、ベストかどうかはわかりません。

[Markdown All in One](https://github.com/yzhang-gh/vscode-markdown)
上記掲示板の本来の議論対象。

[Markdown Preview Enhanced](https://github.com/yzhang-gh/vscode-markdown)
デフォルトのプレビューだと、改行にスペース2つ必要でQiitaの仕様に合わないために導入。