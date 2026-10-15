# Weird Sanctuary

[日本語](#日本語) | [English](#english)

---

## 日本語

DELTARUNE Chapter 4 の非公式改変Mod です。

> [!WARNING]
> **DELTARUNE Chapter 4 のネタバレを含みます。** 本編を遊び終えてからのプレイをおすすめします。

### 必要なもの

- DELTARUNE（Steam 版）。Chapter 4 まで遊べる状態のもの
- [UndertaleModTool](https://github.com/UnderminersTeam/UndertaleModTool/releases)（0.9.2.0 で動作確認）
- このリポジトリの2つのファイル
  - `WeirdSanctuary_v1.0.csx`（Mod 本体）
  - `dark_sanctuary_weird.ogg`（Mod 用の BGM）

### 導入方法

1. **ゲームのフォルダを開く**
   Steam のライブラリで DELTARUNE を右クリック →「管理」→「ローカルファイルを閲覧」を選びます。

2. **バックアップを取る**
   `chapter4_windows` フォルダの中の `data.win` を、別の場所にコピーしておきます。

3. **data.win を開く**
   UndertaleModTool を起動し、「File」→「Open」で `chapter4_windows` の `data.win` を開きます。

4. **Mod を適用する**
   「Scripts」→「Run other script...」で `WeirdSanctuary_v1.0.csx` を選びます。
   「Weird Sanctuary v1.0 を適用しました」と表示されたら成功です。

5. **保存する**
   「File」→「Save」で `data.win` に上書き保存します。
   エラーが出た場合は保存せずに閉じてください。

6. **BGM を入れる**
   `dark_sanctuary_weird.ogg` を `chapter4_windows` の中の `mus` フォルダに入れます。
   入れなかった場合は、その場面で本家の曲が流れます。

### 注意

- **必ず「未改造の」data.win に適用してください。** 一度適用した data.win にもう一度適用すると、正しく動きません。
- 新しくチャプター4を始めると Mod の内容が始まります。今あるセーブデータとは別のスロットで遊ぶことをおすすめします。
- 日本語・英語のどちらの言語設定でも遊べます。
- ゲーム本体のアップデートで、Mod が適用できなくなる場合があります。

### 元に戻す方法

次のどちらかで元に戻せます。

- 手順2で取ったバックアップの `data.win` を戻す。
- Steam で DELTARUNE を右クリック →「プロパティ」→「インストール済みファイル」→「ゲームファイルの整合性を確認」を行う。

`mus` フォルダに入れた `dark_sanctuary_weird.ogg` は、消しても消さなくてもゲームに影響はありません。

### その他

- これはファンが作った非公式の Mod で、Toby Fox 氏および DELTARUNE の公式とは関係ありません。
- ゲームのデータ（data.win）はこのリポジトリに含まれていません。遊ぶにはゲーム本体が必要です。
- 不具合の報告は Issues にお願いします。

---

## English

An unofficial fan mod for DELTARUNE Chapter 4.

> [!WARNING]
> **Contains spoilers for DELTARUNE Chapter 4.** It's recommended to finish the original chapter before playing.

### Requirements

- DELTARUNE (Steam version) with Chapter 4 playable
- [UndertaleModTool](https://github.com/UnderminersTeam/UndertaleModTool/releases) (tested with 0.9.2.0)
- The two files in this repository
  - `WeirdSanctuary_v1.0.csx` (the mod itself)
  - `dark_sanctuary_weird.ogg` (music used by the mod)

### Installation

1. **Open the game folder**
   In your Steam library, right-click DELTARUNE → "Manage" → "Browse local files".

2. **Make a backup**
   Copy `data.win` from the `chapter4_windows` folder to somewhere safe.

3. **Open data.win**
   Launch UndertaleModTool and open `chapter4_windows/data.win` with "File" → "Open".

4. **Apply the mod**
   Go to "Scripts" → "Run other script..." and select `WeirdSanctuary_v1.0.csx`.
   When the message "Weird Sanctuary v1.0 を適用しました" (Weird Sanctuary v1.0 applied) appears, it worked.

5. **Save**
   Use "File" → "Save" to overwrite `data.win`.
   If an error appears instead, close without saving.

6. **Add the music**
   Put `dark_sanctuary_weird.ogg` into the `mus` folder inside `chapter4_windows`.
   If you skip this, the original track will play in that scene instead.

### Notes

- **Always apply the mod to an unmodified data.win.** Applying it twice to the same data.win will not work correctly.
- The mod's content starts when you begin Chapter 4 from the start. Using a different save slot from your existing saves is recommended.
- Both the English and Japanese language settings are supported.
- Updates to the game may make the mod impossible to apply.

### Uninstalling

Do either of the following:

- Restore the `data.win` you backed up in step 2.
- In Steam, right-click DELTARUNE → "Properties" → "Installed Files" → "Verify integrity of game files".

Leaving `dark_sanctuary_weird.ogg` in the `mus` folder does not affect the game, so you can delete it or keep it.

### Other

- This is an unofficial fan-made mod and is not affiliated with Toby Fox or DELTARUNE.
- No game data (data.win) is included in this repository. You need to own the game to play.
- Please report bugs in Issues.
