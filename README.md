# Storm
A TPS shooter of Mecha Combat DEMO

Google driver link: 
1. Playing Show: https://drive.google.com/file/d/1-IeSVQ_h1BXIUBS31J7vFm9skShiGpbC/view?usp=sharing
2. Traning: https://drive.google.com/file/d/1-Oy7qTh8r-SmtUjBR6hKmWofsw85aenO/view?usp=sharing
3. Download LInk:  https://drive.google.com/file/d/1-X8thfXkA9xNVTOo5VTUyijYOeI47dN_/view?usp=sharing 


Download link in Google Driver:

Engine Version: UE5.3
Platform: Windows

Need install WindowsServer\Engine\Extras\Redist\en-us\UEPrereqSetup_x64.exe

Play in Sole Training:

StormServer:
1. Open StormServer folder
2. Open Cmd and input StormServer.exe -log
3. Loading Map and experience and "ShooterGame.GamePhase.WaitForPlayer"

We don't limit number of people, but we need two people join the game, then the game will begin. [TODO Changed]

StormClient:
1. Open StormClient folder
2. Double-click StormClient.exe
3. Windows Mode:StormClient.exe -WINDOWED -ResX=960 -ResY=640 in cmd to choose hero  
4. Key 'Ecs' can quit game

Enjory playing!



Next Planing:
1. Creating Room or game-matching
2. Server + Database
3. UI
4. New Mecha and Map
5. Store System
6. Other: github only support 2GB size for each file, need do chunk for game, and then optimize our game.
===============================================================================================================

中文说明：

视频展示：Show above
训练教程：Show above
下载链接：Show above

安装UE5引擎配套：WindowsServer\Engine\Extras\Redist\en-us\UEPrereqSetup_x64.exe

1. 打开服务器文件夹StormServer在命令行启动服务器：StormServer.exe -log
2. 命令行显示说明之后 "ShooterGame.GamePhase.WaitForPlayer"
3. 打开客户端文件夹双击StormClient启动客户端
4. 再打开一个客户端

Note:  窗口模式打开的方式 StormClient.exe -WINDOWED -ResX=960 -ResY=640 

提示：打开两个客户端才可以进入选人界面。
祝你游玩愉快

交流群：

QQ群：

我们的计划
1. 匹配系统或者房间匹配
2. 后台服务器搭建
3. UI完善
4. 新地图和新机甲
5. 商店系统
6. 其他