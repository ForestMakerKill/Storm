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

==================================================================================================================

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

更多细节：

游戏玩法介绍：

· 在一个地图里敌我阵营的玩家们将进行3v3或者2v2的死亡竞赛，每个玩家有两条命，全部击破对方的机甲即可获胜。
· 核心玩法与亮点：
· 1.作为一款PVP第三人称射击游戏，核心玩法主要使用枪械和其他武器，通过射击击败对方玩家来获得游戏胜利。因为玩家操控的角色是可飞行的巨大机甲，并且z轴的纵深和自动瞄准系统的加入，使得射击手感，移动操作等方面都可以给玩家带来独特的体验。
· 2.两个数据塔：占领数据塔的玩家可以获得增益，比如:攻击力,血量,大招能量等。
· 3.跳台与高地：地图中心有一处高层基地 ，玩家需要在占领数据塔和取得制高点之间取得平衡。跳台则是无需消耗能量飞行 瞬间弹射到高处的装置。
· 4.可破坏地形与基地建筑 ：野外的岩石，基地的大楼可作为掩体 ，但无论是大楼，平房甚至是路灯管道都可以被破坏，且一些巨石拥有掉落伤害，鼓励玩家思考如何利用战场环境的同时进行快节奏战斗
· 5.可破坏机体：所有机体都可以飞行，拥有自动瞄准系统，每个机体都可以被部位破坏（手，脚，头）且有不同的效果，例如：手部：武器掉落，头部：视野一段时间模糊等，大部分机甲核心部位难以破坏，但是四肢比较脆弱，需要玩家加以利用。
· 6.技能与武器：每台机体都拥有三个独特的武器和一个终极技能，并且在破坏他人机体部位后可以拾取他人机体的武器使用，可以让玩家感受到使用他人武器的爽快感。
· 7.补充弹药和修复肢体：地图上藏有多个弹药补充点和2个修理站，弹药补充只能补充当前武器弹夹，修理站可以修复损坏的手臂或者补充血量。

