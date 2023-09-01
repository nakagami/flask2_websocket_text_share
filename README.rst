flask2_websocket_text_share
-------------------------------------------

ここで解説されている
https://kivantium.hateblo.jp/entry/2021/10/18/110509
テキスト入力欄を共有する WebSocket のサンプル

macOS の python3.9.6 で動作確認した。

インストールと起動
::

   git clone git@github.com:nakagami/flask2_websocket_text_share.git
   cd flask2_websocket_text_share
   python3 -mvenv venv
   . venv/bin/activate
   pip install -r requirements.txt
   python server.py

下記の URL に複数のブラウザからアクセスしてテキスト編集
::

   http://127.0.0.1:5000
