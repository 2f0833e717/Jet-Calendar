# 本家(fork元)
https://github.com/retrorocket/Right-Click-to-Calendar

# todo
・右クリックコンテキストメニューから一発でGoogle Calendar登録（現在時刻で登録しGoogle Calendarへ遷移）

# work-flow-design
Webブラウザ上で文字選択
↓
右クリック
↓
コンテキストメニュー（本拡張機能アプリ）タイトル
↓
設定日時選択（デフォルト１時間）※オプションで変更可能？
・現在時刻（１５分刻み？）
・明日の現在時刻（１５分刻み？）
・カスタマイズ（日付（カレンダーUI?）、時刻（時計UI？））
↓
内容選択（Google Calendar登録）
・選択文字をタイトルにして登録（Bodyは空）
・選択文字の先頭から２０文字をタイトルにして選択文字を詳細情報として登録


