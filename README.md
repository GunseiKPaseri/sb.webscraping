# sb.webscraping
- ニコニコ大百科記事掲示板自動保存。(単語記事(`/a/`), 動画記事(`/v/`), ユーザ記事(`/u/`)に対応)
- `python3 nicopedy_saver.py [記事トップURL]`の形で使用。
- 成功すると`./logs/[記事名].log`, `./log/[動画ID].video.log`, `./[ユーザID].user.log`ファイルに掲示板ログをテキスト形式で保存する。
- 例：`python3 nicopedy_saver.py https://dic.nicovideo.jp/a/linux`
