# クロコ オフ会 準備チェックしましょう

Claude Code（クロコ）デスクトップアプリ版 導入オフ会の当日チェック用 Web アプリです。

## 概要

オフ会会場に到着した参加者が、インストール作業をスムーズに始めるための準備チェックリストです。
Q1〜Q7は最初から全て表示され、OS選択後にMac/Windowsで分岐しながら残りの設問が表示されます。
全問回答後にチャットへ貼り付ける下書きが生成され、コピーできます。

## チェック項目

### 最初から表示（Q1〜Q7）
1. 名札をつけていますか？
2. 本日のリベチャットで問診に答えましたか？
3. 作業前にパソコンを再起動しましたか？
4. クロコで使うGmailアカウントを決めていますか？
5. パソコンの電源ケーブルを繋いでいますか？
6. スマホを手元（横）に置いていますか？
7. パソコンの種類を教えてください（Mac / Windows）

### OS選択後に表示（Q8〜Q12）
8. macOSのソフトウェアアップデートは完了していますか？（Macのみ）
9. デフォルトのWebブラウザはChromeに設定されていますか？
10. スクリーンショット（スクショ）の撮り方を知っていますか？
11. ターミナル / PowerShellの開き方を知っていますか？（OS別テキスト）
12. Spotlight（スポットライト）は起動しますか？（Macのみ）

## デプロイ先

Cloudflare Workers  
URL: https://claudecode-offkai-ready.miidacnt.workers.dev

## 関連リンク

- [導入前問診チェック](https://claudecode-offkai-checkin.miidacnt.workers.dev/)
- [GitHubリポジトリ](https://github.com/iidaatcnt/claudecode-offkai-ready)
