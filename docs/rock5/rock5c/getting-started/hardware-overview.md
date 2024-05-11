---
sidebar_position: 5
---

# 硬件接口总览

## 实物照片

<img src="/img/rock5c/rock-5c-overview-new.webp" alt="rock 5c new overview" width="700" />

## 接口说明

<table>
  <tr>
    <th>编号</th>
    <th>接口名</th>
    <th>编号</th>
    <th>接口名</th>
    <th>编号</th>
    <th>接口名</th>
    <th>编号</th>
    <th>接口名</th>
    <th>编号</th>
    <th>接口名</th>
  </tr>
  <tr>
    <th>1</th>
    <th>User Led</th>
    <th>6</th>
    <th>MIPI DSI</th>
    <th>11</th>
    <th>FAN</th>
    <th>16</th>
    <th>PWKEY GND 5V DC IN</th>
    <th>21</th>
    <th>POE Header</th>
  </tr>
  <tr>
    <th>2</th>
    <th>Power Button</th>
    <th>7</th>
    <th>40-PIN GPIO</th>
    <th>12</th>
    <th>Headphone Jack</th>
    <th>17</th>
    <th>USB Type C</th>
    <th>22</th>
    <th>eMMC Socket</th>
  </tr>
  <tr>
    <th>3</th>
    <th>Power Led</th>
    <th>8</th>
    <th>Gigabit Ethernet</th>
    <th>13</th>
    <th>Recovery Key</th>
    <th>18</th>
    <th>Rockchip RK3588S2</th>
    <th>23</th>
    <th>RTC</th>
  </tr>
  <tr>
    <th>4</th>
    <th>Antenna Connector</th>
    <th>9</th>
    <th>USB 3.0</th>
    <th>14</th>
    <th>Maskrom Key</th>
    <th>19</th>
    <th>WIFI 6 && BT 5.4</th>
    <th>24</th>
    <th>MIPI CSI</th>
  </tr>
  <tr>
    <th>5</th>
    <th>FPC Connector</th>
    <th>10</th>
    <th>USB 2.0</th>
    <th>15</th>
    <th>HDMI</th>
    <th>20</th>
    <th>LPDDR4x RAM</th>
    <th>25</th>
    <th>MicroSD Slot</th>
  </tr>
</table>

## 特性

<table>
    <tr>
        <td align="center">型号</td>
        <td align="center">ROCK 5C</td>
        <td align="center">ROCK 5C Lite</td>
    </tr>
    <tr>
        <td align="center">处理器</td>
        <td align="center">Rockchip RK3588S2</td>
        <td align="center">Rockchip RK3582</td>
    </tr>
    <tr>
        <td align="center">CPU</td>
        <td align="center">Quad-core Cortex-A76 主频最高达 2.4 GHz<br/>Quad-core Cortex-A55 主频最高达 1.8GHz</td>
        <td align="center">Dual-core Cortex-A76 主频最高达 2.4 GHz<br/>Quad-core Cortex-A55 主频最高达 1.8GHz</td>
    </tr>
    <tr>
        <td align="center">GPU</td>
        <td align="center"> Arm Mali‑G610MC4 </td>
        <td align="center"> N/A </td>
    </tr>
    <tr>
        <td align="center">内存</td>
        <td align="center">2/4/8/16/32GB 64位 LPDDR4x</td>
        <td align="center">1/2/4/8/16GB 64位 LPDDR4x</td>
    </tr>
    <tr>
        <td align="center">存储</td>
        <td align="center" colspan="2"> 1x eMMC 座子 <br/> 1x microSD 卡座 <br/> 无 SPI Flash </td>
    </tr>
    <tr>
        <td align="center">视频输出</td>
        <td align="center" colspan="2">1x HDMI 2.1 支持最高8K画面输出<br/>1x MIPI DSI 最高2K画面输出</td>
    </tr>
    <tr>
        <td align="center">多媒体</td>
        <td align="center">H.265 / VP9 8K@60fps 解码<br/>H.264 8K@30fps 解码<br/>AV1 4K@60fps 解码<br/>H.264 / H.265 8K@30fps 编码</td>
        <td align="center">H.264 / H.265 4K@60fps 编码</td>
    </tr>
    <tr>
        <td align="center">以太网</td>
        <td align="center" colspan="2">支持PoE 功能的千兆以太网口<br/>PoE 需要额外的 HAT</td>
    </tr>
    <tr>
        <td align="center">无线网</td>
        <td align="center" colspan="2">1x WiFi6 / BT5.4 带外部天线接口</td>
    </tr>
    <tr>
        <td align="center">USB</td>
        <td align="center" colspan="2">2x USB2.0 端口<br/>1x USB3.0 Host 端口, 1x USB3.0 OTG 端口</td>
    </tr>
    <tr>
        <td align="center">摄像头</td>
        <td align="center" colspan="2"> 1x 4通道 MIPI CSI 接口</td>
    </tr>
    <tr>
        <td align="center">其他</td>
        <td align="center" colspan="2">40 针脚扩展座</td>
    </tr>
        <tr>
        <td align="center">供电</td>
        <td align="center" colspan="2">支持 5V</td>
    </tr>
        <tr>
        <td align="center">尺寸</td>
        <td align="center" colspan="2">86 x 56 mm</td>
    </tr>
</table>

## 系统框图

<img src="/img/rock5c/rock-5c-system-block-diagram.webp" alt="rock 5c system diagram" width="700" />

## 芯片框图

<Tabs queryString="target">
  <TabItem value="rk3588s2" label="RK3588S2">
  <img src="/img/rock5c/rk3588s2_blockdiagram.webp" alt="rock 5c overview" width="700" />
  </TabItem>
  <TabItem value="rk3582" label="RK3582">
  <img src="/img/rock5c/rk3582_blockdiagram.webp" alt="rock 5c lite overview" width="700" />
  </TabItem>
</Tabs>