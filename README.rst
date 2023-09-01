flask2_websocket_text_share
-------------------------------------------

ここ
https://kivantium.hateblo.jp/entry/2021/10/18/110509
の WebSocket のサンプルを動かしてみる。


インストールと起動
::

   git clone git@github.com:nakagami/flask2_websocket_text_share.git
   cd flask2_websocket_text_share
   python3 -mvenv venv
   . venv/bin/activate
   pip install -r requirements.txt
   python server.py

下記の URL にブラウザの複数画面からアクセス
::

   http://localost:8000
