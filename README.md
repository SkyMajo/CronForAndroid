# CronForAndroid
这个项目开始于一个运行于智能设备上的定时语言播报项目。这个功能的实现首先需要有一个常驻系统后台的服务。

由于需求是要跟Linux的cron六位格式（秒、分、时、日、月、周）完全匹配，而cron4j项目只支持五位格式（分、时、日、月、周），不支持秒级别的定时。

经过修改后已经能完全支持六位格式的定时任务。如果需要支持七位格式（秒、分、时、日、月、周、年），也可以同样的方式扩展。

希望这个项目能对大家的项目有所帮助，如果有好的建议也请不吝赐教！

另外，经过测试，这个定时任务对CPU和内存的占用极少，基本可以忽略。
