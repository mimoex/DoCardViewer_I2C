道北バスの電子マネーカード”Doカード”の残高をFelicaリーダーとラズベリーパイ、I2Cキャラクタディスプレイを用いて確認できるプログラムとなります。  
  
SuicaやKitakaなどの交通系ICカードと同じ規格のFelicaですが、データの格納アドレスが異なっていたりして既存のICカード読み取りソフトウェアでは確認できません。  
そこでダンプファイルを取得・解析し、なんとか動作するものになりました。  
I2Cのライブラリは適当なものをお使いください。