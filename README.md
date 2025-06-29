# Raspberry Pi Pico版 Xeviousもどき  
Katsumi様、KenKen様作成の[MachiKania type M](http://www.ze.em-net.ne.jp/~kenken/machikania/typem.html)用に作成した「Xeviousもどき」を  
Raspberry Pi Picoへ移植しました。  

　SPI接続版(VERTICALバージョン）  
![](Xevious1.jpg)  

　※HORIZONTALバージョンのNormal版の実行ファイルを修正しました。（2023/11/26）  

　液晶接続など使用ポートはMachiKania type Pと同様です。  
　「MACHIKAP.INI」に「LCD180TURN」と記載すると表示を180度反転します。  
　　又「ROTATEBUTTONS」を記載すると上下左右ボタンを入れ替ます。  

uf2フォルダー内のファイルを参照ください。  
　　各HORIZONTAL,VERTICALフォルダーにpico版、pico2版に分けて保存しています。  
 　　　※pico2対応版を追加しました。（2024/10/28）  
 　　　※UEBKeyBoadに対応しました。（2025/06/15）  
 　　　　キー操作はphyllosoma_Pに準拠、FIREキーはZキー、STARTキーはXキーを追加
