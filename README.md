# PandaMicro (ð¼micro)

<img src="/images/front.png" height="400">ã<img src="/images/back.png" height="400">
<br><br><br>


## èª¬æ

PandaMicro ã¯ MCP23017 ãä½¿ç¨ãã ProMicro ãµã¤ãºã®IOã¨ã­ã¹ãã³ãã¢ã¸ã¥ã¼ã«ã§ãã  
åºæ¿ã«TRRSã¸ã£ãã¯ãåãä»ãããã¦ããã®ãç¹å¾´ã§ãTRRSãå©ç¨ãã¦I2Céä¿¡ãè¡ãã¾ãã  
ãã³ã®éåã¯å¯è½ãªéãProMicroã¨äºæããããè¨­è¨ãã¦ãã¾ããä¸é¨å©ç¨ã§ããªããã³ãããããæ³¨æãã¦ä¸ããã  
<br><br>


## TRRSã¸ã£ãã¯

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


## ProMicroãã³äºæè¡¨

<table>
  <tr>
    <th>No</th>
    <th>ProMicro</th>
    <th>PandaMicro</th>
    <td rowspan="13">ã</td>
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


## ã¢ãã¬ã¹ã¸ã£ã³ãã¼ãã³ã®è¨­å®

<img src="/images/jumper_setting.png" width="700">
<br><br>


## ä½¿ç¨ãã¼ã

<table>
  <tr>
    <th>é¨åå</th>
    <td>è¡¨è¨</td>
    <td>å®¹é / åçª</td>
  </tr>
  <tr>
    <th>TRRSã¸ã£ãã¯</th>
    <td>ã</td>
    <td>PJ320D</td>
  </tr>
  <tr>
    <th>IOã¨ã­ã¹ãã³ã</th>
    <td>U1</td>
    <td>MCP23017-E/SS</td>
  </tr>
  <tr>
    <th>ã³ã³ãã³ãµ</th>
    <td>C1</td>
    <td>0.1Î¼Fï¼ãµã¤ãºï¼2012ï¼</td>
  </tr>
  <tr>
    <th>I2Cãã«ã¢ããæµæ</th>
    <td>R1ãR2</td>
    <td>2.2kÎ©ï¼ãµã¤ãºï¼2012ï¼</td>
  </tr>
</table>
<br><br>


## è©³ç´°æå ±

é»å§ï¼ã1.8Vãï½ã5.5V  
ä¿¡å·ï¼ãI2Cãï¼ï½1.7MHzï¼
ãµã¤ãºï¼ãwidth 17.78mmãÃãheight 33.02
<br><br>


## åç

<img src="/images/pcb_1500.jpg" width="800"><br><br>
<img src="/images/notrrs_1500.jpg" width="800"><br><br>
<img src="/images/comp_1500.jpg" width="800"><br><br>


