# PandaMicro (🐼micro)

![表](/images/front.png)![裏](/images/back.png)



## 説明

PandaMicro は ProMicro サイズのIOエキスパンダモジュールです。  
基板にTRRSジャックが取り付けられているのが特徴で、TRRSを利用してI2C通信を行います。  
ピンの配列は可能な限りProMicroと互換するよう設計していますが一部利用できないピンがあるため注意して下さい。  


## TRRSジャック

<table>
  <tr>
    <td>T</td>
    <td>SCL</td>
  </tr>
  <tr>
    <td>R</td>
    <td>SDA</td>
  </tr>
  <tr>
    <td>R</td>
    <td>VCC</td>
  </tr>
  <tr>
    <td>S</td>
    <td>GND</td>
  </tr>
</table>


## ProMicroピン互換表

<table>
  <tr>
    <th>No</th>
    <th>ProMicro</th>
    <th>PandaMicro</tdth
    <td rowspan="12">　</td>
    <th>PandaMicro</th>
    <th>ProMicro</th>
    <th>No</th>
  </tr>
  <tr>
    <td>1</td>
    <td>D3</td>
    <td>NC</td>
    <td>VCC</td>
    <td>RAW</td>
    <td>24</td>
  </tr>
  <tr>
    <td>2</td>
    <td>D2</td>
    <td>NC</td>
    <td>GND</td>
    <td>GND</td>
    <td>23</td>
  </tr>
  <tr>
    <td>3</td>
    <td>GND</td>
    <td>GND</td>
    <td>NC</td>
    <td>RESET</td>
    <td>22</td>
  </tr>
  <tr>
    <td>4</td>
    <td>GND</td>
    <td>GND</td>
    <td>VCC</td>
    <td>VCC</td>
    <td>21</td>
  </tr>
  <tr>
    <td>5</td>
    <td>D1</td>
    <td>GA0</td>
    <td>GB7</td>
    <td>F4</td>
    <td>20</td>
  </tr>
  <tr>
    <td>6</td>
    <td>D0</td>
    <td>GA1</td>
    <td>GB6</td>
    <td>F5</td>
    <td>19</td>
  </tr>
  <tr>
    <td>7</td>
    <td>D4</td>
    <td>GA2</td>
    <td>GB5</td>
    <td>F6</td>
    <td>18</td>
  </tr>
  <tr>
    <td>8</td>
    <td>C6</td>
    <td>GA3</td>
    <td>GB4</td>
    <td>F7</td>
    <td>17</td>
  </tr>
  <tr>
    <td>9</td>
    <td>D7</td>
    <td>GA4</td>
    <td>GB3</td>
    <td>B1</td>
    <td>16</td>
  </tr>
  <tr>
    <td>10</td>
    <td>E6</td>
    <td>GA5</td>
    <td>GB2</td>
    <td>F3</td>
    <td>15</td>
  </tr>
  <tr>
    <td>11</td>
    <td>B4</td>
    <td>GA6</td>
    <td>GB1</td>
    <td>B2</td>
    <td>14</td>
  </tr>
  <tr>
    <td>12</td>
    <td>B5</td>
    <td>GA7</td>
    <td>GB0</td>
    <td>B6</td>
    <td>13</td>
  </tr>
</table>


## アドレスジャンパーピンの設定

![アドレス設定](/images/jumper_setting.png)


## 詳細情報

電圧：　1.8V　～　5.5V
信号：　I2C　（～1.7MHz）



