## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
  ・エンドポイントは"https://zipcloud.ibsnet.co.jp/api/search"。
  ・機能としては入力した郵便番号を元に住所を表示する。
* リクエストとレスポンスのフォーマット
  ・zipcodeを使用して郵便番号のURLをリクエストし、都道府県などの住所をレスポンスする。
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
  名称：天気予測のAPI(open-Meteo)
  参照：https://open-meteo.com/
* エンドポイントと機能
  ・エンドポイントは`https://api.open-meteo.com/v1/forecast?latitude=${latitude}&longitude=${longitude}&daily=temperature_2m_max,temperature_2m_min&timezone=Asia%2FTokyo`。
  ・機能は緯度・経度を入力すればそこの気温が予測される。
* リクエストとレスポンスのフォーマット
  ・20行目で緯度経度のリクエストをし、26行で最高気温、最低気温をHTMLに出力
### Q3-3. 感想
* 今回の課題で苦労したこと
  ・初めてのAPIで全体の構造に苦戦した。
* 演習を通して理解できたこと
  ・APIについて何ができるかを少しだけ理解できた。
* Web APIの利便性や課題など
  ・いろいろなAPI(画像や音声等)が存在し、入力をするだけで参照してくれる
