# Firefox（デベロッパーエディション）の更新を停止した方法  
* 2020-01-22  
* Firefoxのインストールフォルダを開く
```
C:\Program Files\Firefox Developer Edition
```
* distribution フォルダを開く（もしなければフォルダを作成する）  
* policies.json ファイルを開いて、以下を書き込む（もしなければファイルを作成する）  
```
{
  "policies": {
    "DisableAppUpdate": true
  }
}
```
* Firefoxを再起動する  
* ヘルプの「Firefoxについて」を開き、「システム管理者により、更新が無効化されています」となっているのを確認する
