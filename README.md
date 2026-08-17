# パートのお給料メーター

![インストール台数](https://img.shields.io/github/downloads/honeylatte0619/okyuryo-meter/counter/install-count.txt?label=%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB%E5%8F%B0%E6%95%B0&color=1F5FA8)
![のべ起動日数](https://img.shields.io/github/downloads/honeylatte0619/okyuryo-meter/counter/open-count.txt?label=%E3%81%AE%E3%81%B9%E8%B5%B7%E5%8B%95%E6%97%A5%E6%95%B0&color=256B3D)

パート勤務の給料を1タップで記録し、**月の上限額（例：10万円）と週の労働時間（例：19時間40分）を超えないように見張る**スマホ向けアプリ（PWA）です。高齢の方でも使えるよう、大きな文字と1日1タップの操作だけで動くように設計しています。

## 使い方

https://honeylatte0619.github.io/okyuryo-meter/ を開き、「スマホに入れる」ボタンでホーム画面に追加してください。

- 働いた日に「きょう働いた をつける」を1回おすだけ
- 締め期間（21日〜翌月20日）の給与見込みと、あと何日働けるかを常に表示
- シフト表が出たらカレンダーで予定を合わせると、月初に「超えそうか」がわかります
- つけ忘れは次に開いたときに聞いてくれます

## プライバシー

勤務の記録・金額・設定はすべて端末内（ブラウザのlocalStorage）に保存され、外部に送信されることはありません。
アプリは利用規模を把握するため、起動時にGitHubから空のカウント用ファイルを取得します（匿名のダウンロード数カウントのみで、個人を特定する情報は含まれません。配信元であるGitHub以外への通信はありません）。
