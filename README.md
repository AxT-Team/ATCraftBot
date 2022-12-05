# ATCraftBot
ATBot的Addon（一个Minecraft各项信息查询机器人插件）<br/>

# 搭建教程（Mirai+Mirai Native）
## https://by.xiaoxian.org/index.php/archives/7/

## AT系列机器人插件如下
- ATBot - 用于查询机器人状态及各种消息处理的主控（已完成）<br>
https://github.com/AxT-Team/ATBot
- ATCraftBot - 集合了大部分Minecraft查询功能（已完成）<br>
https://github.com/AxT-Team/ATCraftBot
- ATDnBot - 集合了大部分域名及IP等查询功能（制作中）<br>
https://github.com/AxT-Team/ATDnBot
- ATLeBot - 集合了今日人品，猜数字等娱乐功能（制作中）<br>
https://github.com/AxT-Team/ATLeBot
- ATQmBot - 一个群管Bot（？（制作中）<br>
https://github.com/AxT-Team/ATQmBot

## ATCraftBot功能看指令列表（其实是懒得写）

## 管理员指令
- /atcraft admin - 查看ATCraft管理员命令菜单
- /atcraft setting - 查询插件功能开启状态（无需管理员身份）
- /atcraft ipadd [IP] - 指令/sv添加白名单IP
- /atcraft iplist - 指令/sv白名单IP列表
## Minecraft查询指令
- /mc - 主菜单命令
- /mc [ID] - 获取玩家UUID等信息
- /mcskin [ID] - 获取玩家皮肤文件
- /mcstatus - 获取Mojang及Minecraft验证等服务器状态
## Minecraft服务器查询指令
- /mcping - Minecraft服务器查询主菜单
- /sv [IP:端口] - 支持Java/BE查询（普通查询）[API使用https://api.imlazy.ink/mcapi/]
- /mcping [IP:端口] java - Java服务器详细查询（详细查询）[（国内部分地区可能无法获取）API使用:https://api.mcsrvstat.us/]
- /mcping [IP:端口] be - Bedrock服务器详细查询（详细查询）[（国内部分地区可能无法获取）API使用:https://api.mcsrvstat.us/]
