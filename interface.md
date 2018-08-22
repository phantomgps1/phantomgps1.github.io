# Phantom GPS

发送经纬度给外设，修改手机位置

## 接口 ##
| 类    | 接口  | 描述   | 版本  |
| -----|:-----:|:-----:|:-----:|
| PhantomGPS    | - (int)setGPSData:(float)latitude longitude:(float)longitude speed:(float)speed insindeChina:(BOOL)inChina;| 给外设发送经纬度信息。<br>speed:行驶速度，单位是km/h <br>insideChina：用于判断是采用有WGS84还是GCJ02坐标系； <br>返回值：0表示正常，-1表示发送失败，需要重新发送。| 0.2| 
| PhantomGPS    | - (int)setGPSData:(float)latitude longitude:(float)longitude altitude:(float)altitude insindeChina:(BOOL)inChina;| 给外设发送经纬度信息。<br>altitude:海拔高度，单位是米 <br>insideChina：用于判断是采用有WGS84还是GCJ02坐标系； <br>返回值：0表示正常，-1表示发送失败，需要重新发送。| 0.2| 
|略|||

## 说明 ##
- 速度和海拔高度需要分两步完成，**并且**设置海拔时带入的经纬度仅仅作为参考，设置速度的方法经纬度才会生效，实际使用应根据需要调整两者的比例，可以1：1，也可以2~3：1
- 修改位置需要不间断发送位置信息给设备，否则外部GPS会停止给手机发送信号，从而导致手机位置恢复真实位置。发送频率控制在1~5HZ范围内

- info.plist里将protocolString设置为com.itools.mobile
