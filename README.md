# study-floodgate

- floodgateの過去の対戦ログ(csa)を自前のツールでsfen文字列の集合にしたもの。<br />
- 圧縮してますが解凍すると1年分は70MBくらいあるテキストファイルなのでご注意。<br />
- (2025年分は途中経過で順次（月一くらい？）で更新予定)<br />

# floodgateってなに？
- コンピュータ将棋（将棋ソフトウェア）同士が通信対戦して、レーティングを付けあっているところです。<br />
- http://wdoor.c.u-tokyo.ac.jp/shogi/floodgate.html<br />
- トップページが長らくメンテナンスされてないですが、対戦ログなどは該当ディレクトリでアップデートされているようです。<br />

# サンプル
- 1行1対戦
- セパレータはコロン(：) 元のcsaのsumamryの結果と両者のレーティング(ついていれば)、次にsfen形式で指し手stringです。<br/>

#'summary:toryo:007_512x2-64-16_12T lose:test_i7-8550U win:4461:4259:position startpos moves 2g2f 8c8d 2f2e 4a3b 7g7f 8d8e 8h7g 3c3d 7i6h 2b3c 7g3c+ 3b3c 6h7g 7a6b 6i7h 7c7d 3i3h 6b7c 3g3f 7c6d 2i3g 4c4d 4g4f 9c9d 3h4g 7d7e 7f7e 6d7e 5g5f P*7f 7g8h 7e6d 4i4h 8e8f 8g8f 8b8f 8h8g 8f8b P*8f 8b7b P*7e 6a6b 4f4e 4d4e 3g4e 3c3b B*6f 3a2b 2e2d 2c2d 2h2d P*2c 2d2e P*4d 6f4d 2a3c 4e3c 2b3c 4d8h P*4d P*4e 4d4e 2e2g 5c5d 8g7f 6b5c 5i6i 5c4c 1g1f 5a4b 2g2i 3c4d 8h7g P*8g 7f8g 6d7e 7g6h P*8h P*2d 2c2d 6h2d 4b4a P*4b 4a5b 7h8h P*2c 2d1e 1c1d 1e3g 5d5e 5f5e 5b4b P*7f 7e7f 8g7f 7b7f S*5d 4c5d 5e5d N*5e 3g5e 4d5e 8h7g 7f7b N*6e P*5b P*4d S*2d P*2e 2d1c P*7f 5e4d 6i7h P*8h 7h8h P*7e 7f7e 6c6d N*5f 4d5e 5d5c+ 5b5c G*6c 7b8b 6e5c+ 4b3c 1f1e 4e4f 5c5d 4f4g+ 5d5e S*6h S*4d 3c2b 1e1d 1c1d 1i1d 4g4h 8h8g B*5g S*6f P*8e 8f8e G*9e　<br/>
