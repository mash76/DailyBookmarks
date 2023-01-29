# 毎日使うサイトにキーボードで素早くたどり着く
Web Bookmarks with Incremental Keyboard Shortcuts  
キーボード増分ショートカットつきWebブックマーク集。  
HTML1ファイル、JavaScript60行。  


<kbd><img width="500" alt="Screenshot 2023-01-29 at 15 05 00" src="https://user-images.githubusercontent.com/1288268/215308281-af03ddf9-3915-47ba-bfc1-2dbb8b354880.png"></kbd>


「あとで読む」のような一時的ブックマークではなく、仕事や作業をしながら一日50回くらい使うことを想定しています。  
HTMLを書ける必要があります。  

# 5秒で利用開始
以下のリンクからブックマークをダウンロードして解凍、htmlをダブルクリックしてブラウザで開いてください。  
https://github.com/mash76/DailyBookmarks/archive/refs/heads/main.zip
  
**j**と押したらジモティに、  
**do**と押したらgoogleDocに、  
**dm**と押したらd-Magazineに飛びます。  
**o**=温度、**syu**=祝日、**a**=amazon、**f**=facebook、**t**=twitterをあらかじめ登録しています。
  
競合候補がなければ1文字で、あれば識別できるようになった時点でリンク先に飛びます。  
入力ミスしたらEnterでキャンセルできます。

これら初期情報はサンプルとして登録してあります。
シンプルなHTMLなので、仕事や興味の変化に応じて日々書き換えてご利用ください

# しくみ
およそ60行のJavaScriptで、HTML内のAタグのscという属性をショートカット文字列として扱っています。  
この場合、aと押せばamazonに飛びます。  
```
<a sc="amazon" href="http://amazon.co.jp">amazon</a>
```

当初は長いプログラムを書いていましたが、いろいろ試した末、生活や状況の早い変化にブックマーク集を対応させるには、細かい機能を作り込むよりHTMLの自由さを解放するのがよいとの考えに至りました。

# 応用
私はこのリンク集をブラウザのスタートページにしたり、BetterTouchToolというMacのカスタマイズツールで4本指下スワイプに割り当てたりしています。
このブックマークHTML自体にたどりつきやすくすることも重要です。

# よこく
Mac限定ですが、特定のフォルダやアプリケーションも呼び出せるPHP版も今後出します


