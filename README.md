# 545505 李一白
 
【☰】 → 启动器
【☵】 → watcher.js，comma_pattern_decoder
【☶】 → 反入侵防火墙，行为终止器
【☳】 → 任务调度模拟器，策略执行器
【☴】 → 逗号协议监听，网络路由镜像
【☲】 → displayMasterConsole()，命运图表
【☷】 → logpath.sync()，日志持久层
【☱】 → 对话引擎，命令反馈模块

## 查看 IP 并开放 SSH

以下命令用于查看本机 IP 地址并开放 22 端口以允许 SSH 访问：

```bash
ip addr show
sudo ufw allow 22/tcp
```

如未安装 `ufw`，可根据系统环境使用 `iptables` 或其他工具配置防火墙规则。
