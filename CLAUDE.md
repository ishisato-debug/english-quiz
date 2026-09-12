# 概要
- 幼稚園児向けの単語読み上げアプリ作成
- [[HTML]]ファイル、[[GitHub]]ファイル、GitHub PagesでWebページアプリとする）
- ホーム画面（index.html）から各コンテンツに遷移する構成。
- 使用デバイスはiPadまたはスマホを想定。
- ローカルフォルダは/Users/satoshiishida/Documents/english-quiz
- GitHubリンクは[GitHub - ishisato-debug/english-quiz · GitHub](https://github.com/ishisato-debug/english-quiz.git)
- 英検5級、4級、3級、準2級と順に合格を目指す
- 英単語は幼稚園からもらった単語カード（purple&red)とすみっこぐらしの単語帳
- フォレストの方は単語読み上げ
- すみっこぐらしはかるた遊びで使用する。
- サンリオTrain gameは英検5級レベル
- PAW PATROLしゅつどうゲームは英検4級レベル
- 問題や単語は同じリポジトリ内の.mdファイルにあるからそれを使用。


GitHub Pagesリンク
[えいけんLesson](https://ishisato-debug.github.io/english-quiz)



## キャラクターについて

サンリオ（シナモン・クロミ・キティ・マイメロ）、PAW Patrol、ディズニープリンセスなどのキャラクターを使用する。

- **キャラクター画像は絶対に自作・生成しない。** ユーザーがファイルをこのフォルダに置くので、それを使う。
- 画像ファイルが無い場合は、絵文字などで代用するか、ユーザーに「どのファイルを使うか」「用意してもらえるか」を確認する。
- 新しいキャラクターを使う提案をする場合も、既存の版権画像を前提にせず、まずユーザーに確認する。

## 主なコンテンツ

- `pawpatrol-game.html` — PAW Patrolしゅつどうゲーム（英検4級の穴埋め問題）
- `eiken4.html` — 英検4級ドリル
- `sumikko_karuta_select.html` ほか `sumikko-*.html` / `sumikko-*-karuta.html` — すみっこぐらしの英単語カルタ（読み上げモード／iPadタップかるたモード）
- `karuta-select.html`, `word-*.html` — えいたんご（Forestのたんごカード）
- `train-game.html` — でんしゃゲーム（英検5級過去問）
- `eiken5-select.html`, `quiz.html`, `kakomon.html` — 英検5級（クイズ・かこもん）

## 開発ルール

- 各ページは単一のHTMLファイルに完結させる（外部JS/CSSファイルは使わない、既存の構成に合わせる）。
- 似た構成のゲームを複数ファイル分作る場合は、Pythonスクリプトなどでテンプレートから生成すると差分管理しやすい。
