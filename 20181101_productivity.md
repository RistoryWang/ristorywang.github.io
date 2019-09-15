## 生产力服务建设

### 作者

ristorywang 

### 日期

2018-11-01




#### 相关组件
![skill](https://ristory.oss-cn-shanghai.aliyuncs.com/article/productivity/Productivity_Tools.png)




#### 持续集成

Git+Jenkins+Nexus+SLB+Truck+TruckSSH+ECS
![skill](https://ristory.oss-cn-shanghai.aliyuncs.com/article/productivity/deployment_sequence_diagram.png)




#### 基础监控告警

Grafana+Influxdb+Telegraf
![skill](https://ristory.oss-cn-shanghai.aliyuncs.com/article/productivity/Monitor_System.png)




#### 日志告警

Docker compose（Sentry+Memcached+redis+postgresql）

Sentry-dingding ：fork github repo
by-sentry：override sentry-log4j2.jar sentry.jar etc.
                    Extend Log4j2 : BYLogger

![skill](https://ristory.oss-cn-shanghai.aliyuncs.com/article/productivity/Sentry_Diagram.png)






#### 文档协同和任务跟踪

Confluence+Jira

Sentry integrate Jira
