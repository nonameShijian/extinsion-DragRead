扩展介绍: 无名杀windows电脑版专属扩展，把zip（离线包，扩展或素材压缩包）拖入到游戏内即可导入
<pre style="color:rgb(210,210,000); font-size:25px; line-height:20px; text-shadow: 0 0 2px black;">
v3.1更新内容:

———修复在诗笺版v1.7报错的问题

———更换更新链接

v3.0更新内容:

———支持通过info.json识别扩展信息

v2.1更新内容:

———支持异步game.import

v2.0更新内容:

———重新选用npm解压库

———移除对解压7z压缩包的支持

———添加对带密码的压缩包功能

———可以简单的识别文件夹嵌套的扩展


v1.81更新内容:

———修复一个导入的bug


v1.8更新内容:

———兼容识别【应用配置】中提供的新扩展框架


v1.78更新内容:

———修复导入时不显示进度的bug

———zip解压完成后，过500ms再结束Promise
（为了防止某些bug）


v1.77更新内容:

———支持导入.7z格式的离线包和素材包

———导入7z格式的扩展请参考万能导入法

然后选择素材包，解压缩到指定扩展目录

———导入默认选项从“扩展包”改为“取消”


v1.76更新内容:

———增加新功能，拖拽一个extension.js也可以导入扩展

———拖拽的监听放在了启动函数里，

即选模式的界面也可以用拖拽了



v1.75更新内容:

———兼容Electron V15及以上的新api


v1.74更新内容:

———修复导入的不是扩展时不弹窗提示的问题


v1.73更新内容:

———【一键导出完整包】的功能不再包括皮肤

（image/skin）文件夹

———因为有了【在线更新】扩展，所以本扩展移除

【替换github更新地址】的功能


v1.72更新内容:

———修复【替换github更新地址】的bug


v1.71更新内容:

———增加【一键导出完整包】的功能

———增加【替换github更新地址】的功能

请额外在菜单-选项-通用-更新地址 手动切换为

【GitHub】


v1.7更新内容:

———没有nodeJs环境导入时将自动删除此扩展

———移除【下载完整包】的功能


v1.65更新内容:

———下载完【完整包】后自动导入

———下载【完整包】时不能获取总字节数的情况将

显示已经下载了多少MB


v1.6更新内容:

———扩展支持【检查更新】

———扩展界面可以直接下载【最新版完整包】


v1.5更新内容:

———本扩展向下兼容低版本windows无名杀


v1.4更新内容:

———增加导入耗时提示，导入后可以查看导入消

耗了多长时间

———使用JSZip v3.5.0特性


v1.3更新内容:

———兼容一种错误的压缩扩展方式（可以通过此

扩展导入“直接压缩文件夹”的扩展）


v1.2更新内容:

———增加了进度条的z-index

———拖拽后没有检测到文件将不会弹窗

———可以拖拽pdf，html等文本文件打开了
</pre>