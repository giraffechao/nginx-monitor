# nginx-monitor
nginx监控


## docker本地容器日志采集 loki+promtail+grafana
步骤1: 本地安装和启动docker,然后docker-compose启动，启动前创建本地network[docker network create devops-compose]
```
docker-compose up -d
```
步骤2: grafana页面导入陪孩子好的看板: docker-log-dashboard.json