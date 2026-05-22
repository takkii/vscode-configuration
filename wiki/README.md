### vscode-configuration

> Windows11 環境構築

```markdown
# ./vscode/extensions/README.md
テキストエディタの正規表現を利用し前処理を行いデータ加工をする。

# ./vscode/settings.json
File → Preferences → settings → search settings  → "settings." write in bar  →  Edit in settings.json
/vscode/settings.jsonの内容をコピー&ペーストする。

# Windowsターミナル/Powershell上で実行する
cd ./powershell
.\vscode_ext.ps1

# Hyper-V/Ubuntu24.04/shellを実行する
cd ./sh
./vscode_ext.sh

# 許可がありません
cd ./sh
chmod +x ./vscode_ext.sh
```

#### Use [Scoop](https://scoop.sh/)

```markdown
# Scoop install
scoop install cmake
scoop install erlang
scoop install elixir
scoop install deno

# Add, vscode extensions.
pip3 install yapf
pip3 install isort
```

#### Lang / Font

- [Rust](https://rustup.rs/)、ドキュメントを読んでインストールしてください。

- GitHub/[Hackgen](https://github.com/yuru7/HackGen)、フォントを[2種類](https://github.com/yuru7/HackGen/releases)インストールしてください。

- [Elixir](https://elixir-lang.org/install.html#windows)、ドキュメントを読んで設定してください。

- [Deno](https://deno.com/)、インストールしてください。

※ まだスタックトレースが流れる場合、英文を読んで不足しているものをインストールしてください。
