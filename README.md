# PandaMicro (🐼micro)

<img src="/images/front.png" height="400">　<img src="/images/back.png" height="400">
<br><br><br>


## 説明

PandaMicro は MCP23017 を使用した ProMicro サイズのIOエキスパンダモジュールです。  
基板にTRRSジャックが取り付けられているのが特徴で、TRRSを利用してI2C通信を行います。  
ピンの配列は可能な限りProMicroと互換するよう設計していますが一部利用できないピンがあるため注意して下さい。  
<br><br>


## TRRSジャック

<table>
  <tr>
    <td>1</td>
    <td>T</td>
    <td>SCL</td>
    <td rowspan="4"><img src="/images/pj320a.png" width="400"></td>
  </tr>
  <tr>
    <td>2</td>
    <td>R</td>
    <td>SDA</td>
  </tr>
  <tr>
    <td>3</td>
    <td>R</td>
    <td>VCC</td>
  </tr>
  <tr>
    <td>4</td>
    <td>S</td>
    <td>GND</td>
  </tr>
</table>
<br><br>


## ProMicroピン互換表

<table>
  <tr>
    <th>No</th>
    <th>ProMicro</th>
    <th>PandaMicro</th>
    <td rowspan="13">　</td>
    <th>No</th>
    <th>ProMicro</th>
    <th>PandaMicro</th>
  </tr>
  <tr>
    <td>1</td>
    <td>D3</td>
    <td>NC</td>
    <td>24</td>
    <td>RAW</td>
    <td>VCC</td>
  </tr>
  <tr>
    <td>2</td>
    <td>D2</td>
    <td>NC</td>
    <td>23</td>
    <td>GND</td>
    <td>GND</td>
  </tr>
  <tr>
    <td>3</td>
    <td>GND</td>
    <td>GND</td>
    <td>22</td>
    <td>RESET</td>
    <td>NC</td>
  </tr>
  <tr>
    <td>4</td>
    <td>GND</td>
    <td>GND</td>
    <td>21</td>
    <td>VCC</td>
    <td>VCC</td>
  </tr>
  <tr>
    <td>5</td>
    <td>D1</td>
    <td>GA0</td>
    <td>20</td>
    <td>F4</td>
    <td>GB7</td>
  </tr>
  <tr>
    <td>6</td>
    <td>D0</td>
    <td>GA1</td>
    <td>19</td>
    <td>F5</td>
    <td>GB6</td>
  </tr>
  <tr>
    <td>7</td>
    <td>D4</td>
    <td>GA2</td>
    <td>18</td>
    <td>F6</td>
    <td>GB5</td>
  </tr>
  <tr>
    <td>8</td>
    <td>C6</td>
    <td>GA3</td>
    <td>17</td>
    <td>F7</td>
    <td>GB4</td>
  </tr>
  <tr>
    <td>9</td>
    <td>D7</td>
    <td>GA4</td>
    <td>16</td>
    <td>B1</td>
    <td>GB3</td>
  </tr>
  <tr>
    <td>10</td>
    <td>E6</td>
    <td>GA5</td>
    <td>15</td>
    <td>F3</td>
    <td>GB2</td>
  </tr>
  <tr>
    <td>11</td>
    <td>B4</td>
    <td>GA6</td>
    <td>14</td>
    <td>B2</td>
    <td>GB1</td>
  </tr>
  <tr>
    <td>12</td>
    <td>B5</td>
    <td>GA7</td>
    <td>13</td>
    <td>B6</td>
    <td>GB0</td>
  </tr>
</table>
<br><br>


## アドレスジャンパーピンの設定

<img src="/images/jumper_setting.png" width="700">
<br><br>


## 使用パーツ

<table>
  <tr>
    <th>部品名</th>
    <td>表記</td>
    <td>容量 / 型番</td>
  </tr>
  <tr>
    <th>TRRSジャック</th>
    <td>　</td>
    <td>PJ320D</td>
  </tr>
  <tr>
    <th>IOエキスパンダ</th>
    <td>U1</td>
    <td>MCP23017-E/SS</td>
  </tr>
  <tr>
    <th>コンデンサ</th>
    <td>C1</td>
    <td>0.1μF（サイズ：2012）</td>
  </tr>
  <tr>
    <th>I2Cプルアップ抵抗</th>
    <td>R1、R2</td>
    <td>2.2kΩ（サイズ：2012）</td>
  </tr>
</table>
<br><br>


## 詳細情報

電圧：　1.8V　～　5.5V  
信号：　I2C　（～1.7MHz）
<br><br>


## 写真

<img src="/images/pcb_1500.jpg" width="800"><br><br>
<img src="/images/notrrs_1500.jpg" width="800"><br><br>
<img src="/images/comp_1500.jpg" width="800"><br><br>


