# Cursor 自作コマンド集

このディレクトリには、Cursorで使用するカスタムコマンドが含まれています。

## コマンドファイル

- `commit-atomic.md` - 原子的コミット実行コマンド。論理的に意味のある最小単位で、タスクに関連するファイルのみをコミットします。

## インストール

```bash
git clone https://github.com/myokoym/cursorcommands .cursor/commands/my
```

## 使い方

これらのコマンドファイルは、Cursorのコマンドパレットから実行できます。

例：
```
/commit-atomic [commit-message]
```

## ライセンス

CC0 1.0 Universal (パブリックドメイン)

詳細は [LICENSE](./LICENSE) ファイルを参照してください。

