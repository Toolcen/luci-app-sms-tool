## Luci-app-sms-tool

![GitHub release (latest by date)](https://img.shields.io/github/v/release/4IceG/luci-app-sms-tool?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/4IceG/luci-app-sms-tool?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/4IceG/luci-app-sms-tool?style=flat-square)
![GitHub All Releases](https://img.shields.io/github/downloads/4IceG/luci-app-sms-tool/total)

#### Luci-app短信工具是一个用于通过短信应用程序/项目处理消息的GUI。可与mPCI-E和USB 3G/LTE调制解调器配合使用。不要使用HiLink/RNDIS调制解调器。


#### 预览和快速配置（调制解调器Quectel EM160R-GL）

![](https://github.com/4IceG/Personal_data/blob/master/zrzuty/1.9.4-20220325/1.9.4-20220325.gif?raw=true)

### 用户编译

<details>
   <summary>展开</summary>

``` bash
#添加到Openwrt源代码中：

cd feeds/luci/applications/
git clone https://github.com/Toolcen/luci-app-sms-tool.git
cd ../../..
./scripts feeds update -a
./scripts/feeds install -a
make menuconfig

```
   
</details>

### 截图

- 收件箱:

![](https://github.com/4IceG/Personal_data/blob/master/zrzuty/1.9.4-20220325/Odebrane%20wiadomo%C5%9Bci%20-%20LuCI.png?raw=true)

- 发短信:

![](https://github.com/4IceG/Personal_data/blob/master/zrzuty/1.9.4-20220325/Wysy%C5%82anie%20wiadomo%C5%9Bci%20-%20LuCI.png?raw=true)

- USSD:

![](https://github.com/4IceG/Personal_data/blob/master/zrzuty/1.9.4-20220325/Kody%20USSD%20-%20LuCI.png?raw=true)

- AT命令:

![](https://github.com/4IceG/Personal_data/blob/master/zrzuty/1.9.4-20220325/Polecenia%20AT%20-%20LuCI.png?raw=true)

- 配置:

![](https://github.com/4IceG/Personal_data/blob/master/zrzuty/1.9.4-20220325/Konfiguracja%20-%20LuCI1.png?raw=true)
![](https://github.com/4IceG/Personal_data/blob/master/zrzuty/1.9.4-20220325/Konfiguracja%20-%20LuCI2.png?raw=true)
![](https://github.com/4IceG/Personal_data/blob/master/zrzuty/1.9.4-20220325/Konfiguracja%20-%20LuCI3.png?raw=true)
![](https://github.com/4IceG/Personal_data/blob/master/zrzuty/1.9.4-20220325/Konfiguracja%20-%20LuCI4.png?raw=true)

### 感谢
- [obsy (Cezary Jackiewicz)](https://github.com/obsy)
- [Users of the eko.one.pl forum](https://eko.one.pl/forum/viewtopic.php?id=20096)
