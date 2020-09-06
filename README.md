# AC電流センサ基板
Minimally invasive current sensor board

## 概要 
  * ホール素子を用いた低侵襲AC電流センサ基板です  
  * CT電流センサと異なり、一般的な電源ケーブルに近接させて使用します    
  * 電源ケーブルの電流に応じて比例してアナログ電圧が出力されます  
  * 可変抵抗RV1で感度調整が可能です  
  * センサ電源は2.5V～5V電源を供給してください  
  
   <img src="https://github.com/meerstern/AC_Current_Sensor_Module/blob/master/IMG/AC_IMG1.JPG" width="360">
   
   <img src="https://github.com/meerstern/AC_Current_Sensor_Module/blob/master/IMG/AC_IMG2.JPG" width="360">
  

## 使用方法
　* 小電流(数10W～数100W程度)の場合は部品側にシルクの点線に合わせて電源ケーブルを固定してください  
 
 <img src="https://github.com/meerstern/AC_Current_Sensor_Module/blob/master/IMG/AC_IMG3.JPG" width="360">
　
  * 大電流(数100W～1000W程度)の場合は部品裏側のシルク点線に合わせて電源ケーブルを固定してください  
  
 <img src="https://github.com/meerstern/AC_Current_Sensor_Module/blob/master/IMG/AC_IMG4.JPG" width="360">
 
 <img src="https://github.com/meerstern/AC_Current_Sensor_Module/blob/master/IMG/AC_IMG5.JPG" width="360">
 
 <img src="https://github.com/meerstern/AC_Current_Sensor_Module/blob/master/IMG/AC_IMG6.JPG" width="360">
 
 <img src="https://github.com/meerstern/AC_Current_Sensor_Module/blob/master/IMG/AC_IMG7.JPG" width="360">
    
## 注意 
 * 布巻き電源ケーブルや傷、破損のある電源ケーブルに対して使用しないでください  
 * 電源ケーブルの破損防止のため、電源ケーブルとセンサ基板を強く固定しないでください  
 * 当電流センサ基板は商用交流(50Hz、60Hz)専用で直流電流やその他交流電流の測定には使用できません  
 * 実験、評価用途を目的としています  
 * 15A以上の電流測定には使用しないでください  
 * 商用電源のノイズがアナログ出力に入る場合は必要に応じて、フィルタ処理をしてください  
 * 磁界変化をピークホールドさせるため、急激な電流変化や微小な電流変化の検出はできません  
 * 同じ電流であっても電源ケーブルの種類や取り付け位置によっても磁界の大きさが変化し、出力も合わせて変化します  
 * 電流とアナログ出力電圧の関係は事前にクランプ式電流センサ等で確認してください  
 * 負荷や使用する電源ケーブルによっては電流に対してアナログ出力が１次比例しない場合があります  
 * 電源ケーブルと電流センサ基板の取り付け位置を固定させて使用してください  
 * 当電流センサ基板上の部品を手で触れた状態では出力が不安定化する場合があります  

  
 MIT Lisense
