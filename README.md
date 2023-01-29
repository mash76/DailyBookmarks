# DailyBookmarks
Web Bookmarks with Incremental Keyboard Shortcuts  
キーボードショートカットつきWebブックマーク集。  
「あとで読む」のような一時的ブックマークではなく、毎日使うサイトにキーボードショートカットで素早くたどり着くための生活ツールです。  
<img width="350" border="2" alt="Screenshot 2023-01-29 at 15 05 00" src="https://user-images.githubusercontent.com/1288268/215308281-af03ddf9-3915-47ba-bfc1-2dbb8b354880.png">



# 5秒で利用開始
以下のリンクからブックマークをダウンロードして、解凍、htmlをダブルクリックしてブラウザで開いてください。  
https://github.com/mash76/DailyBookmarks/archive/refs/heads/main.zip
  
「j」と押したらジモティに、  
「do」と押したらgoogleDocに、  
「dm」と押したらd-Magazineに飛びます。  
  
競合候補がなければ1文字で、あれば識別できるようになった時点でリンク先に飛びます。  

入力ミスしたらEnterでやり直しです。

ただのHTMLなので、毎日の仕事や興味の変化に応じて自由に書き換え、組み替えてご利用ください

# しくみ
JavaScriptを使って、HTML内のAタグのscという属性をショートカット文字列として扱っています。  
この場合、aと押せばamazonに飛びます。  
```
<a target="_blank" sc="amazon" href="http://amazon.co.jp">amazon</a>
```
