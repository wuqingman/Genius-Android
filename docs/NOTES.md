* 2014/9/2 修改GLog方法"addLogCallbackListener()"为："addCallbackListener()"。
* 2014/9/2 解决GLog回调时出现："java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()" Bug。
* 2014/9/2 修复因为日志消息传输问题导致的服务调用日志类出现的程序死掉问题。
* 2014/9/2 GLog与Command类添加"destroy()"方法用于释放资源。
* 2014/9/2 Publish Version-0.1.0.


* 2014/9/6 更改日志部分Bug。
* 2014/9/6 修改命令行执行部分，更改了服务实现与接口释放。
* 2014/9/6 命令行执行添加异步执行方法。
* 2014/9/6 命令执行类删除回调方式等待，采用有次数等待方式。
* 2014/9/6 添加新的UI项目。
* 2014/9/6 Material Button实现。
* 2014/9/8 Publish Version-0.1.1.


* 2014/9/18 程序注释等英文化。
* 2014/9/20 Log精简化，删除内存缓存及通知功能。
* 2014/9/21 ToolUtils添加文件拷贝，或许系统唯一标识等方法。
* 2014/9/22 Command精炼化，添加取消任务功能。
* 2014/9/23 Command服务添加自动停止功能，与销毁功能。
* 2014/9/24 添加NetTool模块，提供Ping/DNS等常见功能使用。
* 2014/9/24 添加HashUtils模块，提供对字符串与文件计算MD5。
* 2014/9/28 库添加初始化与销毁方法。
* 2014/9/30 Publish Version-0.4.0.


* 2014/10/2 简化Log设置文件存储的方法调用
* 2014/10/2 Log与Command抛出异常语句统一化
* 2014/10/2 修改NetTool中toString方法的Bug
* 2014/10/3 添加FixedList固定队列
* 2014/10/4 添加App相关UiTool与UiModel
* 2014/10/5 修复TraceRoute,Dns解析中解析失败时结果为null时触发异常
* 2014/10/5 更新README，更新SAMPLE
* 2014/10/5 Publish Version-0.6.5.


* 2014/10/5 调整属性样式
* 2014/10/5 公布Material Button
* 2014/10/5 添加截图等工作
* 2014/10/5 更新README，更新SAMPLE
* 2014/10/5 Publish Version-0.6.8.


* 2014/10/9 更改域名解析传入服务器地址参数为：InetAddress
* 2014/10/9 更改域名解析有服务器情况下超时时间为8秒
* 2014/10/10 更改域名解析实例化是传入服务器参数为：InetAddress
* 2014/10/10 删除命令行执行中产生的日志信息
* 2014/10/11 MaterialButton 调整速度参数
* 2014/10/11 MaterialButton 支持近似正方形情况
* 2014/10/11 MaterialButton 添加新属性AutoMove，自动移动到中间
* 2014/10/11 更新项目截图
* 2014/10/12 Publish Version-0.7.5.


* 2014/10/27 修复Material按钮竖直情况下动画BUG
* 2014/10/27 更改README，添加Jar包模式下配置信息
* 2014/10/27 Publish Version-0.7.6.


* 2014/11/21 Log方法添加直接拷贝日志到外部存储方法
* 2014/11/21 取消Log初始化开启日志存储时的位置指定参数
* 2014/11/21 修改README，更正Log传参错误示例
* 2014/11/21 Publish Version-0.7.9.


* 2014/11/24 微调 `Log` 中发送消息方法
* 2014/11/24 删除掉 `UiTool` 类
* 2014/11/24 新增 `ToolKit` 代替 `UiTool` ,完成同样工作的同时无需传入Activity，传入Runnable类即可
* 2014/11/25 编写 `Jni FastBlur` 实现模糊效果
* 2014/11/25 `Jni` 生成 so 文件完成
* 2014/11/25 编写 `BlurKit` 类，添加 `FastBlur` 方法用于模糊图片
* 2014/11/26 添加图片模糊案例
* 2014/11/26 删除 `Jni` 中加载的 `android/log` 头文件
* 2014/11/26 重新生成 `Jni` 文件so
* 2014/11/26 修改 `util/ToolUtils` 类名为 `Tools`
* 2014/11/26 删除 `util/Tools` 类中不常用方法：`getDeviceId()` `isAvailablePackage()`
* 2014/11/26 更改资源 `attrs_material` 为 `genius_attrs`
* 2014/11/26 更改资源 `colors` 为 `genius_colors`
* 2014/11/26 更名日志 `Log.txt` 为工作记录 `NOTES.md`
* 2014/11/26 添加文档文件夹并添加Eclipse完全导入说明书 `Log.txt` 为工作记录 `NOTES.md`
* 2014/11/26 更改 `LogWriter` 类中锁的释放，解决其在特定情况下出现死锁情况
* 2014/11/26 优化 `Log` 类回调部分，更改Handle为自定义线程类实现，优化效率
* 2014/11/26 修改测试用例部分命名，以及删除多余部分
* 2014/11/26 删除 `MaterialRectButton`，以及删除多余属性文件
* 2014/11/26 修改 `README` 准备发布相关
* 2014/11/26 完善相关文档，包括 **Eclipse** 导入方法
* 2014/11/26 Publish Version-0.9.0.
