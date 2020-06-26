PhantomGPSII 固件升级指导
====
固件是指运行在GPS里面的软件，升级固件类似于给手机刷机.<br>
版本查看方法:插上设备，显示绿色USB图标以后，打开左上角菜单，第一行显示类似:1.0.1（FW: 1.1)的字样，其中1.0.1位App的版本号，括号里的1.1为固件的版本号<br>
当前最新的固件版本为1.3,如果App菜单按钮出现了小红点，说明有新的固件版本可以升级。
#### 准备工作
1.	安装了Windows操作系统的电脑<br>
2.	在电脑上下载以下文件包：<br>
[设备驱动](http://download.gpsmock.com/firmware/DriverAssitant_v4.6.zip)<br>
[升级工具](http://download.gpsmock.com/firmware/FactoryTool_v1.63.zip)<br>
[固件文件包1](https://down.anqiuzp.cn/data/download.gpsmock.com/firmware/PhantomGPSII_fw_ver1.3.part1.rar)<br>
[固件文件包2](http://download.gpsmock.com/firmware/PhantomGPSII_fw_ver1.3.part2.rar)<br>
3.	准备一个取卡器<img src="http://phantomgps.com/assets/needle.jpg" width="5%" >或者大头针之类的工具<br>
 
#### 升级步骤
1.	解压下载的文件(下载四个文件，解压后是三个）。其中PhantomGPSII_fw_verxxx.img为升级文件。<br>
2.	进入驱动文件夹，运行DriverInstall.exe,安装设备驱动<br>
3.	运行FactoryTool.exe<br>
	-点左上角固件按钮，选择刚刚下载的PhantomGPSII_fw_verxxx.img文件<br>
	-点启动按钮，等待GPS插入<br>
4.	<font  color="red">操作GPS，进入升级模式</font><br>
	-让GPS处于关机状态<br>
	-将取卡器从设备顶部小孔插入，轻轻按下、弹起，多尝试几次，找到里面升级按键的手感。<br>
	-将取卡器下的升级按键按住，再按住电源开机键，持续两秒。注意，这时GPS设备看不到任何反应<br>
	（按住升级键再开机，设备就进入了升级模式）<br>
	-松开两个按键（无先后顺序），此时蓝色电源指示灯应该处于熄灭状态。如果灯亮了，将设备关机，重复上面步骤。<br>
	-将USB充电线插入GPS充电口，另一端连接电脑<br>
5.	升级
	-点开升级工具USB列表中所有的+号键，如果没有的话可以忽略。<br>
	-如果一切正常，将显示升级进度。<br>
	-升级完后，后侧绿灯下会显示升级成功。<br>
 
#### 常见问题
1.	请放心操作，任何意外（如电脑断电，载入的固件有错）都不会使设备变砖。<br>
2.	如果出现下载固件失败的提示：<br>
	-请将GPS的USB线拔掉，按住电源键15秒。<br>
	-用取卡器按住升级键开机，并重复之前的升级步骤。<br>
3.	如果担心文件出错，可以对比[md5sum](http://download.gpsmock.com/firmware/PhantomGPSII_fw_ver1.3_md5.txt)<br>
4.	本文稍微详细的版本[PDF](http://download.gpsmock.com/firmware/PhantomGPSII_fw_upgrade_guide.pdf),有图。<br>
5.	如果实在搞不定，请联系客服提供视频指导，或者寄回设备升级。<br>
