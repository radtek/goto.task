## 项目简介
* 任务调度系统-任务调度服务 taskmanager
	* 支持实时任务,定时任务,断点任务。
	* 任务列表来源为配置文件,可简单修改做成群集任务调度。
	* 任务执行前,中,后支持各种日志扩展异常监听。
	* 调度架构以插件形式加载任务模块，具有良好的功能扩展性，稳定性，简单性，便于功能扩展。
* 任务调度系统-子业务模块 taskbusiness
	* 具体任务操作类对基类,接口无任何限制,实现灵活配置。

## 技术选型
* 核心框架：Spring Framework
* 日志管理：SLF4J、Log4j2

## 系统流程图
![系统流程图](/doc/flowchart.jpg)

## 使用说明
	
## 问题反馈
