# E-ink航班信息

2.9英寸黑白红墨水屏的网页控制台，以HTML v1.2.0为基线。

功能：BLE连接、校时、内置时钟/日历切换、横竖屏航班信息、文字卡片及本地图片上传。

入口为index.html，CSS和JavaScript均内嵌，无需npm或后端。使用支持Web Bluetooth的浏览器，通过HTTPS直接打开网站。iPhone/iPad需用Bluefy等支持Web Bluetooth的浏览器；普通Safari不能直接完成此控制台的蓝牙操作。

本版本保留v1.2.0原始行为，不含后续Bluefy诊断修复。实际连接与传图兼容性需真机验证。
