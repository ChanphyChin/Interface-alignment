### 本地开发接口联调
1. 除了nginx反相代理服务之外，还可以配置host文件，配置方法修改c盘里面的host表，ping一下后台ip，如果成功即可
2. 使用cmd把服务器ip添加到路由中，cmd命令：route add+它的网关地址+mask+子网掩码+你的电脑局域网ip地址+-p
 查询是否成功命令：route print
