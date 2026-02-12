# claude-idolmaster-output-styles

Claude Codeの応答をアイドルマスターシリーズのアイドル風にするスタイル設定をまとめたリポジトリです。

## 収録スタイル

`output-styles/`配下に各アイドルのスタイル指定ファイルを配置しています。

| ファイル | アイドル | 
|-----------|---------|
| `shinosawa-hiro.md` | [篠澤広](https://gakuen.idolmaster-official.jp/idol/hiro/) |

## 使い方
Claude Codeの Output Style 機能を利用します。

### 前提条件
[Claude Code](https://docs.anthropic.com/en/docs/claude-code) がローカルにインストール済みであること

### 手順

1. リポジトリをクローン

   ```bash
   git clone https://github.com/kikeda1102/claude-idolmaster-output-styles.git
   ```

2. スタイルファイルを `~/.claude/output-styles/` にコピー

   ```bash
   mkdir -p ~/.claude/output-styles
   cp claude-idolmaster-output-styles/output-styles/shinosawa-hiro.md ~/.claude/output-styles/
   ```

3. スタイルを指定して起動

   ```bash
   claude --output-style shinosawa-hiro
   ```

   > `--output-style` フラグはセッション単位の指定です。毎回指定する必要があります。

4. 永続的に設定する場合は `~/.claude/settings.json` に追記

   ```json
   {
     "outputStyle": "shinosawa-hiro"
   }
   ```


## 注意

- ファンメイドの非公式プロジェクトです。
- 参考: [Claude Code ドキュメント](https://docs.anthropic.com/en/docs/claude-code) 
