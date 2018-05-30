# FAQ
### 是否对所有app有效
是<br>
其原理相当于给手机换了一个可自定义位置的GPS芯片。

### 能不能淘宝交易
暂时不能，会封淘宝账号<br>
### 微店有保障吗
微店的投资人包括腾讯以及雷军，2014年腾讯投资4.3亿美金入股，更详细的消息可以搜索 北京口袋时尚科技有限公司 的相关资料
### 如何获取APP
PhantomGPS需要安装配套的App，用于设置目的地址，该App无法在苹果应用商店上架，只能通过测试模式发布，目前使用TestFlight安装<br>
[如何使用TestFlight](https://jingyan.baidu.com/article/63f23628276e1d0209ab3d10.html)

### PhantomGPS对设备有哪些影响
耗电，Phantomg GPS的工作电流在3～5mA左右，由手机电池提供电源。除了设备本身耗电，APP在工作时需要计算路劲以及位置信息，需要耗费CPU资源，导致手机消耗更多的电量.
在iPhone5C（电池容量1510mAh）上的测试结果为持续工作**4**小时左右

其他影响暂未发现

### 是否会被其他应用检测到异常

别越狱，未越狱的系统每个App都运行在自己的沙盒里，无法获取系统安装了哪些应用
PhantomGSP未设置URL scheme，无法通过应用跳转打开
通过App store下载的所有App，如果需要读取外设，都必须由厂家将外设寄至苹果检测中心，匹配bundle ID和Accessor ID才能读取外设信息，没有通过认证的设备信息无法上架，因此App store下载的软件是无法检测该设备的。

### 是否可以升级iOS
理论上不用担心，该外设使用的是苹果通用的外设通讯协议（iAP2)，所有的苹果外设都使用这个接口，如果基础协议变了，所有的外设厂商以及他们的设备都会受到影响。
但是必须注意的是，这个外设并不是苹果官方认可的外设，他属于非法设备，如果哪天苹果禁用外部GPS的功能了，这个设备也就没有用了，升级iOS之前可以先到qq群咨询最新支持的版本。
### 质保
微店的质保和淘宝相同，7天无理由退款<br>
店主承诺质量问题3个月包换
### 是否有距离限制
iOS 11.0.x有15公里的距离限制，其他版本没有，也就是10.3.3（包含）以前的没有，11.1.0（包含）以后的也没有
### 能否定位到国外
可以，距离限制同上<br>
目前的坐标拾取是采用高德地图，国外的数据无法搜索，只能在地图上手动找到，再设置位置
### 可以多设备共用吗
可以，但必须是同一个apple id，这个是和Test Flight绑定的。
### 软件能使用多久
会一直维护
### 需要在后台运行吗
需要，否则无法定位<br>
### 会一直在后台运行吗
插上外设的时候app会在后台运行，拔掉后app在后台不运行（省电）
### 能改手机的ip吗
不能
### testflight可以删除吗？
建议保留，每三个月要更新一次app<br>
删掉后重新下载也可以，不需要重新接受邀请邮件。

### 更多问题请QQ咨询
QQ群：612428052