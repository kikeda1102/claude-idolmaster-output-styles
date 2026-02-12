# claude-idolmaster-output-styles

Claude Codeの応答をアイドルマスターシリーズのアイドル風にするスタイル設定をまとめたリポジトリです。

## 収録スタイル

`output-styles/`配下に各アイドルのスタイル指定ファイルを配置しています。

| ファイル | アイドル | 
|-----------|---------|
| `shinosawa-hiro.md` | 篠澤広 |

## 使い方
Claude Codeの Output Style 機能を利用します。

### 前提条件
[Claude Code](https://docs.anthropic.com/en/docs/claude-code) がローカルにインストール済みであること

### `~/.claude/output-styles/` に配置して名前で指定

スタイルファイルを `~/.claude/output-styles/` にコピーすると、ファイル名で指定できるようになります。

```bash
cp output-styles/shinosawa-hiro.md ~/.claude/output-styles/
claude --output-style shinosawa-hiro
```


## 注意

- ファンメイドの非公式プロジェクトです。
- 参考: [Claude Code ドキュメント](https://docs.anthropic.com/en/docs/claude-code) 
