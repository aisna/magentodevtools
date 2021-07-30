这是一个magento2开发的辅助工具
官方git：https://github.com/magespecialist/m2-MSP_DevTools
浏览器扩展git：https://github.com/magespecialist/mage-chrome-toolbart
浏览器扩展：https://chrome.google.com/webstore/detail/magespecialist-devtools-f/odbnbnenehdodpnebgldhhmicbnlmapj?authuser=3

chrome_tool文件夹：是浏览器扩展crx文件，无法翻墙的朋友直接安装里面的.crx就行
MSP文件夹：是magento开发辅助工具模块，使用方式如下：
1、复制到站点目录app/code下;
2、执行以下命令启动模块
php7.2 bin/magento module:enable MSP_DevTools MSP_Common
3、重新编译完成后;
4、到后台开发模块就可以;
