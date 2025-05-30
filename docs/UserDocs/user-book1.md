---
sidebar_position: 2
---

# 不要修改这里的内容，这里的内容是原先用户手册的导出内容，请查看另外的文档，谢谢

# VRCub玩家操作手册

*是的，没想到吧，除了VRCub管理员操作手册 居然还有VRCub玩家操作手册。*

本文档接旨帮助玩家快速上手并游玩

 ### 注意⚠️

 文档仍然在修改，可能会发上各种各样的改变，

 如果发现错字或者问题，请及时与dream_pep联系！

#### 重要声明

### VRCub给新玩家的Q&A

 **Q：网易版可以玩吗？**

 **A：不可以，请购买国际版后再试😁**

---

 **Q：手机可以玩吗？**

 **A：可以，但需要您有一定的技术含量，我们管理员不帮助，请自行探索**

---

  **Q：为啥解压要钱？你这不是变相收费吗？**

  **A：这是您自己找的收费的解压软件，有免费软件你不找，偏偏选了收费的还来说我们？（这不关我们事，遇到这种一律踢出群并拉黑）**

---

Q：模组是什么，服务器IP是什么？

A：请下载整合包，根据用户手册操作，谢谢！

---

Q：现在需要通行证吗？

A：现在已经下架了通行证服务，暂时不需要验证，后续我们会开放更好的验证方法

---

Q：官网无法打开

A：这个可能是你的浏览器问题，请升级

---

Q：如何下载？QQ下载太慢了

A：请到官网下载页面，登陆你的微软帐号下载

---

Q：VR遇到问题？

A：请@其他管理

---

Q：想要加入管理组？

A：暂时不需要新的管理人员，现在管理组已经饱和，但也非常感谢您有想帮助VRCub的想法

---

### VRCub管理员给玩家们的提示

1. 在问问题时，**::请配上详细的问题描述/截图/还有保持良好的品德与教养::**。
2. ::尽量不要**@小沈（服主）**::，遇到问题请询问其他管理员，**dream_pep仅负责网络相关问题与活动策划**，其他问题一概不处理。
3. 服务器崩溃时，请耐心等候，**::我们管理员们会加急处理并争取快速回复，请勿在群里散播不属实言论，以公告为准::**。
4. 整合包内的按键分配问题我们正在进行优化，后续会更新整合包版本，**::请不要再因为此问题在群里找管理员反馈::**。

---

最后，VRCub也感谢各位玩家体谅管理员们，我们会经快开发更好的玩法给予玩家更优良的体验

————VRCub管理组全体成员

#### 无法登陆你的帐号？

### **Minecraft正版登录问题解决指南（按操作难度排序）**

以下方法按从简单到复杂排序，适配不同用户需求。当前Minecraft已归属Microsoft，操作中涉及的服务均需关联微软账号体系。

---

### **方法1：使用网络加速器（最简单，新手/老玩家通用）**

#### **新手版（完整说明）**

加速器就像给网络“开绿灯”的小助手，帮你绕开拥挤的网络路线，快速连接到微软的Minecraft服务器。

1. 下载 **UU加速器**、**雷神加速器** 或 **迅游加速器**（都有免费试用）。`这里不是暗广！！`
2. 打开加速器，搜索“Minecraft: Java Edition”或“国际服”，选择带“微软登录”的节点。
3. 点击“一键加速”，加速成功后重启游戏，直接用微软账号登录即可。
💡 提示：如果登录失败，试试在加速器里换个节点（比如“北美”或“欧洲”节点）。

#### **老玩家版（快速说明）**

通过代理服务器优化国际链路，降低TCP连接延迟和丢包率。推荐支持“Xbox Live”或“Microsoft Services”的节点，加速后重启游戏客户端即可完成握手验证。

---

### **方法2：使用Watt Toolkit（原Steam++，一键式工具）**

#### **新手版（完整说明）**

Watt Toolkit是个“网络全能管家”，能一键解决加速、Hosts修改等问题，专门针对微软服务优化。

1. 访问cn.bing.com搜索“Watt Toolkit官网”，下载安装（完全免费）。
2. 打开软件，在“加速”页面找到“Microsoft服务”和“Xbox服务”，勾选后点击“一键加速”。
3. 加速成功后，直接打开Minecraft启动器登录，无需额外设置！

#### **老玩家版（快速说明）**

开源工具集成DNS缓存清理、Hosts智能写入和微软服务代理功能。在“加速”模块启用“Microsoft Services”后，可自动处理登录服务器的网络解析问题，进阶用户可通过“工具箱”手动管理Hosts规则。

---

### **方法3：修改DNS服务器（基础网络配置）**

#### **新手版（完整说明）**

DNS就像网络的“地址簿”，默认的“地址簿”可能找不到Minecraft服务器，换个更准的就能解决问题。

1. **Windows**：右键右下角网络图标 → 网络和Internet设置 → 更改适配器选项 → 右键当前网络 → 属性 → 双击“IPv4”。 **Mac**：系统偏好设置 → 网络 → 高级 → DNS。
2. 把DNS地址改成 `8.8.8.8`（谷歌）或 `223.5.5.5`（阿里云），点击保存。
3. 按 `Win+R` 输入 `cmd`（Windows）或打开终端（Mac），输入命令刷新DNS缓存（见步骤3详细说明）。

#### **老玩家版（快速说明）**

通过替换本地DNS解析服务器（如Google Public DNS或阿里云DNS），解决因ISP域名解析异常导致的登录失败。修改后需执行 `ipconfig /flushdns`（Windows）或 `sudo killall -HUP mDNSResponder`（Mac）清除本地DNS缓存。

---

### **方法4：切换网络环境（物理层调整）**

#### **新手版（完整说明）**

如果家里的WiFi连不上，试试用手机开热点！有些宽带运营商会悄悄“拦”住国际游戏连接，换个网络说不定就通了。
💡 操作：打开手机热点，电脑连接热点后重启游戏登录。

#### **老玩家版（快速说明）**

排查是否为运营商级网络封锁：临时切换至4G/5G热点或其他网络环境（如公共WiFi），若能登录则说明原网络存在链路限制，需联系运营商或使用加速器绕过。

---

### **方法5：关闭防火墙/更新客户端（系统级基础操作）**

#### **新手版（完整说明）**

有时候安全软件会“误杀”游戏连接，或者旧版本游戏“跟不上”微软的登录规则，需要简单调整。

1. **关防火墙**：暂时关闭Windows Defender或第三方杀毒软件（记得登录后重新打开！）。
2. **更新游戏**：打开Minecraft启动器，检查是否有“更新”按钮，点击更新到最新版。

#### **老玩家版（快速说明）**

- **防火墙**：在Windows安全中心或第三方安全软件中，将游戏进程（如Java版的`javaw.exe`）添加到信任列表，避免被拦截。
- **客户端更新**：通过官方启动器或微软商店确保游戏版本为最新，防止因协议版本不兼容导致登录失败。

---

### **方法6：修改Hosts文件（进阶手动配置）**

#### **新手版（完整说明）**

Hosts文件是电脑的“私人导航地图”，手动添加Minecraft服务器的正确地址，就能避开拥堵路线。

1. **找到文件**：
   - Windows：在 `C:\Windows\System32\drivers\etc\` 里，右键用记事本（管理员模式）打开 `hosts`。
   - Mac：在终端输入 `sudo nano /etc/hosts` 并输入密码。
1. 在文件末尾添加：

```other
13.107.213.49 login.minecraft.net  
20.207.73.82 authserver.mojang.com
```

   （IP可能会变！用 `PingInfoView` 工具查最新IP，或百度“minecraft登录服务器IP”）

1. 保存前取消文件“只读”属性（Windows），保存后重启电脑生效。

#### **老玩家版（快速说明）**

通过编辑系统Hosts文件强制解析登录服务器域名（`login.minecraft.net` 和 `authserver.mojang.com`）到稳定IP，绕过ISP的DNS污染。需定期通过 `ping login.minecraft.net` 校验IP有效性，避免因微软服务器IP变更导致登录失效。

---

### **方法7：联系微软官方支持（终极求助）**

#### **新手版（完整说明）**

如果所有方法都没用，别慌！找微软客服帮忙，把登录时的错误截图和你的操作步骤告诉他们。
🔗 地址：[微软支持中心](https://support.microsoft.com/) → 搜索“Minecraft登录问题” → 提交工单。

#### **老玩家版（快速说明）**

若排除所有网络和客户端问题仍无法登录，需通过微软支持平台提交技术工单。附件需包含：

- 启动器完整错误日志（Java版路径：`%AppData%\.minecraft\logs`）
- 网络环境信息（如IP归属地、使用的加速器/代理类型）
- 详细操作步骤及失败截图，便于官方定位账号或服务器端问题。

---

### **难度总结与推荐顺序**

| 难度等级 | 适合人群      | 优先推荐方法                          |
| ---- | --------- | ------------------------------- |
| 简单   | 新手/懒人     | 加速器 → Watt Toolkit → 切换网络/更新客户端 |
| 中等   | 有基础电脑操作经验 | 修改DNS → 关闭防火墙                   |
| 较难   | 进阶玩家/技术流  | 修改Hosts文件                       |
| 终极   | 所有方法失效时   | 联系微软官方支持                        |

按此顺序逐步排查，90%以上的登录问题可在“简单-中等”难度步骤中解决。遇到权限问题（如修改Hosts）时，记得以管理员身份操作哦！ 🎮✨

---

————VRCub管理组dream_pep

---

# 第一节：新手教程

#### 第一章：下载VRCub整合包

官网下载[https://vrcub.net/download/](https://vrcub.net/download/)

---

QQ下载：

在开始时你需要拥有一个QQ帐号。

然后打开VRCub交流群

 ### 被省略的步骤

+  我不在群里咋么办？

    请立即访问网页 vrcub.net

    首页的公告上有显示QQ群号

点击群文件，并选择`客户端在这里`这个文件夹，里面选择一个最新的版本，你可以选择下载标准版还是青春版

 ### 青春是啥？

 青春版是为了给渣机准备的完善版本，你可以选择他，但是体验可能会有所欠缺

 ### 注意⚠️

 下载后请打开Mod文件夹，请删除 **下面这两个模组**，这个模组对客户端有影响，有崩溃风险，后者有显示bug。

![IMG_2504.png](https://res.craft.do/user/full/8c64421f-afa1-96e8-dd67-8efce27b11dd/doc/45BB165F-FF44-4993-85FB-B120508BB2E5/7EDD5880-4F3D-4166-94BC-20884105F81E_2/8Aft23xGVenG54VDeo4jKd4J4yMNv3gUK0yQGYSnU7gz/IMG_2504.png)

#### 第二章：**安装一个启动器**

这边您可以在下面选择一个启动器，来阅读操作方法，如果你已经有启动器了，请跳过本篇！

#### 使用LancherX

由于HMCL过于古老（而且dream_pep不喜欢），本教程将教您使用LancherX来进行操作

### 如何下载？

首先请打开浏览器

并访问 corona.studio/lx

点击立即下载，并选择合适的系统版本

下载后解压即可

 本步骤只要求了你下载并解压，具体激活步骤请到下一章

#### 使用PCL2

PCL2作为一个特别老牌的启动器，其稳定性与可靠性还有快速上手性都非常的出色，但因为其不支持跨端导致其用户大部份为Windwos用户（虽说只有极少数人用MacOS来玩和Linux来玩罢了）

#### 第三章：激活，登陆，并加入服务器

 **本篇文档适用于大部份启动器，HMCL请自行摸索**

---

# 激活您的启动器并安装整合包和启动游戏

先在**::C盘与桌面以外的地方::**创建一个文件夹，并将解压后的启动器本体拷贝过去

 这一步是为了防止C盘占用与方便后期操作

下面有两篇指导方式，但其实大差不差，请选择你的启动器再来按照流程来进行安装

---

### LancherX请看：

打开启动器，一般按照指引一步步操作即可

在登陆帐户时，请选择Microsoft帐户（正版），到达JAVA选择页面选择合适的java

 ### 请注意⚠️

 如果你没有安装java请不要跳过这一步，点击下载java，选择java17，点击安装

 等待进度条跑了一半，你就可以在上面选择你下载的java17了

激活LancherX后，请将你在第一章解压的文件内标有`VRCub ALL.zip`的文件拖动到LancherX的窗口上，并根据操作完成安装

---

### PCL2请看:

双击PCL2图标，打开启动器，同意条款，请将你在第一章解压的文件内标有`VRCub ALL.zip`的文件拖动到PCL2的窗口上，并根据操作完成安装

---

# 启动并加入服务器

OK，你现在已经快要成功了！

---

LancherX：接下来请打开LancherX的 游戏 页面，并将VRCub开头的版本旁的图钉图标点上，然后回到主介面，点击启动即可！

---

PCL2：请登录你的正版帐号，然后点击启动游戏即可！

---

到这里，新手教程就结束了，下面呢还准备了一些应对方案供问价查阅：

#### 莫名其妙掉出服务器？

一般发生这种事都会显示下面的内容：

![IMG_2503.png](https://res.craft.do/user/full/8c64421f-afa1-96e8-dd67-8efce27b11dd/doc/45BB165F-FF44-4993-85FB-B120508BB2E5/D8513A8F-1110-4DB2-9F81-B59AE9B0C0CB_2/mXWifihjAPRXpuJ1OF7XtuuKjxTh936UhXiFBq37brsz/IMG_2503.png)

你可以尝试打开Windows安全中心，关闭防火墙即可

---

# 第二节：使用神奇的命令

#### 领地的神奇力量

  摘要：

  本服选点工具为“箭”，分别用其左键右键方块选择第一个第二个点形成空间长方体，再结合以下命令即可画出领地

 以下来自  [http://www.mcbbs.net/thread-18529-1-1.html](http://www.mcbbs.net/thread-18529-1-1.html)

### 总命令

/res ? [页数] – 显示帮助，不写页数则显示第一页.

/resadmin – 在使用管理命令时使用

---

### 选择命令

/res select [x] [y] [z] – 选择领地的长方体区域，X Y 和Z 都是从你当前位置为中心的距离，你也可以用一个工具（默认是木斧）来选择地块。

/res select chunk – 选取一整个chunk。

/res select expand [格数] – 向你的前方延伸选区。

/res select size – 显示已选择区域的尺寸。

/res select shift [格数] – 向你的前方移动选区。

/res select vert – 把选区延伸到从天顶到地底。

---

### 创建命令

/res area [add/remove/replace] 领地名 [区域id] – 向叫做[领地名]的领地增加(add)、从其中去除(remove)或是替换 (replace) 区域。可与同一领地内的区域重合。

/res create [领地名] – 选择好区域后创建一个叫做[领地名]的领地

/res remove [领地名] – 移除一个叫[领地名]的领地

/res removeall – 移除所有领地

/res subzone 领地名 [子区域名] – 在领地内创建一块子区域，你必须是所有者才行。

---

### 信息命令

/res area list [领地名] – 列出某领地的所有区域

/res area listall [领地名] – 列出某领地的所有区域以及他们的坐标

/res current – 显示你所在的领地

/res info 领地名 – 得到某领地的信息

/res list – 显示你拥有的领地

/res listall – 显示所有领地

/res limits – 显示重要的权限

/res sublist – 显示你所在领地的所有子区域

/res version – 显示插件版本

---

### 权限命令

/res gset 领地名 [群组名] [权限] [true/false/remove] – 设置某领地对于某群组的权限

/res lset 领地名 [黑名单/忽略名单] [材质] – 从某领地的黑名单/忽略名单中增加/移除某材质

/res lset 领地名 info – 显示某领地的黑名单/忽略名单设置

/res pset 领地名 [玩家名] [权限] [true/false/remove] – 设置某领地对于某玩家的权限

/res set 领地名 [权限] [true/false/remove] – 设置某领地的权限

---

### 其他命令

/res default [领地名] – 重置某领地的权限设置

/res give [领地名] [玩家名] – 将某领地赠与某玩家，你必须是领主且被赠予玩家在线

/res lists – 预定领地许可清单的详细信息

/res message [领地名] [enter/leave] [信息] – 设置进入/退出某领地时候显示的信息

/res message [领地名] remove [enter/leave] – 移除进入/退出某领地时候的信息

/res mirror [源领地名] [目标领地名] – 复制源领地的权限设置至目标领地

/res rename – [旧名称] [新名称] 重命名领地.对于子空间旧名称必须全名，新名称可以只写子空间名

/res renamearea [领地名] [旧名称] [新名称] – 重命名某领地中某区域的名称

/res tp [领地名] – 传送至某领地

/res tpset – 设置当前领地的传送点为你站立的地方

/res unstuck – 将你从当前领地移出

---

### 交易命令

/res lease [renew/cost] [领地名] – 更新/显示 更新一个领地的费用（？意义不明）

/res market list – 显示在售的所有领地

/res market info [领地名] – 显示在售的某领地的信息

/res market sell [领地名] [价格] – 将某领地出售

/res market unsell [领地名] – 将某领地下架

/res market buy [领地名] 购买某领地

/res market rentable [领地名] [价格] [天数] [repeat:t/f](repeat:t/f) – 将某领地以[价格]/[天数]出租并设置可否自动续期

/res market rent [领地名] [repeat:t/f](repeat:t/f) – 设置某领地出租手否可自动续期

/res market release [领地名] – 解除某领地的出租

---

### 管理命令

/resadmin lease set [领地名] [#天数/infinite] – 设置领地的时间限制或不限时

/resadmin removeall [玩家名] – 移除某玩家的所有领地

/resadmin setowner [领地名] [玩家名] – 将某领地以交给某玩家

/resadmin server [领地名] – 将某领地设置为服务器领地

/resload – 载入领地插件. *注* 在res.yml的任何改变都不会被还原. 你可以再更改过res.yml后想立即将新设置生效的时候使用此命令

/rereload – 重载领地插件. *注* 将会还原res.yml为初始状态. 如果你在res.yml更改过设置请不要使用此命令

注：以上命令不写领地名则为当前所在的领地

---

### 权限表：

admin：领地的全权管理权限，仅能给与某玩家

container：是否能使用箱子，发射器等

bucket：设置是否能使用桶

ignite：点火的权限

piston：活塞是否能使用

build：建造权限（包括destroy和place）

destroy：毁坏权限

place：放置权限

move：进入权限

tp：传送权限

use：使用权限（工作台，炉子等）

subzone：是否能设置子空间

tnt：设置tnt是否有效

creeper：设置JJ怪是否有效（设置F的话JJ怪就废了）

damage：设置领地内是否能造成伤害（不能防止被挤死）

monsters：设置是否刷新怪物

animals：设置是否刷新动物

firespread：火是否能蔓延

flow：液体流动，包括waterflow和lavaflow

waterflow：水的流动

lavaflow：岩浆流动

healing：设置是否能恢复生命

pvp：设置是否能pvp

  **本节正在撰写**

---

# 第三节：学会与管理员沟通

  **本节正在撰写**

---

# 第四节：正确的举报姿势

#### 举报信息收集

在你看到这篇文档的时候，说明你遇到了作弊者或者违规者。

 在开始举报前，你需要按照下面的列表来收集证据（建议在没有遇到作弊违规前就记住以下信息收集列表，方便在遇到作弊者或违规者时能从容面对）

| **证据类型** | **格式样例/描述**   | **是否必须？** |
| -------- | ------------- | --------- |
| 作弊者游戏ID  | the_id        | 是         |
| 作弊者行为截图  | 他作弊的影响，如聊天框   | **是**     |
| 违规事件坐标   | 生存1区，0 12 -20 | 否         |
| 时间       | 25年4月12日13:00 | **是**     |

建议尽量收集上面全部类型的证据，这可以更好地帮助我们解决问题

[VRCub玩家违规行为与处罚细则说明](https://lingke.craft.me/VRCub-appeal)

  **本节正在撰写**

---

# 第五节：如何使用VRCub.net

  **本节正在撰写**

---

# 第六节：其他

#### MCFT使用教程`测试版`

## 🌟 前置准备须知

- 本教程适用于**完全零基础的新手玩家**，使用Minecraft Fabric 1.21.4+版本
- 需要准备：支持面部捕捉的VR设备（如PICO 4 Pro）、已安装SteamVR环境
- 推荐先观看视频教程：[PICO 4 Pro连接演示](https://www.bilibili.com/video/BV1TW4y197qp)

---

## 🛠️ 安装配置全流程

### 第一步：Mod环境搭建

1. 下载必备组件：
   - [Fabric Loader](https://fabricmc.net/use/)
   - [MCFT最新版](https://example.com)（从官方群文件获取）
   - [VRCFT v2023.1+](https://github.com/vrcft)
1. 安装步骤：

```other
/Minecraft根目录
├── /mods
│    ├── fabric-api-0.xx.x.jar
│    └── MCFT-1.0.0-fabric.jar
└── /config
     └── vrcft_settings.cfg
```

### 第二步：设备连接

- 确保头显通过**有线/无线串流**连接PC
- 在SteamVR中确认设备识别状态：

    绿灯常亮 → 正常 | 红色感叹号 → 检查USB驱动

---

## 🎮 首次使用教程

### 游戏内操作流程

1. 启动游戏后输入命令：

```java
/MCFT
```

1. **核心标定四步法**：

| 步骤      | 操作要点            | 常见问题                     |
| ------- | --------------- | ------------------------ |
| 1. 眼白标定 | 用选区工具框选皮肤中纯白色区域 | 选区边缘出现杂色 → 放大皮肤2倍操作      |
| 2. 眼皮标定 | 选取与脸部主色一致的区域    | 颜色匹配困难 → 使用吸管工具采样        |
| 3. 瞳孔定位 | 确保包含虹膜完整圆形区域    | 眼球转动异常 → 检查是否包含高光层       |
| 4. 动态校准 | 缓慢转动眼球观察实时反馈    | 灵敏度不足 → 调整"移动倍率"至1.2-1.5 |

1. **高级参数调节**：
   - 眼球曲率：0.85（拟真） ↔ 1.15（卡通化）
   - 眨眼阈值：推荐保持默认35%
   - 头部跟随：关闭可减少眩晕感

---

## 🚨 故障排除指南

### 常见问题速查表

| 现象     | 解决方案                       | 进阶检测                  |
| ------ | -------------------------- | --------------------- |
| 无法识别设备 | 1. 重启VRCFT服务br2. 重装USB驱动 | 检查设备管理器→混合现实设备        |
| 眼球偏移   | 1. 重新标定瞳孔区域br2. 调整IPD参数  | 使用校准网格覆盖工具            |
| 帧率骤降   | 1. 关闭光影模组br2. 降低渲染分辨率    | 在NVIDIA控制面板单独设置JAVA进程 |

---

## 💡 专家级小贴士

1. **皮肤适配技巧**：
   - 为提升精度，可在皮肤眼部周围添加定位标记点（完成后擦除）
   - 使用透明通道制作动态睫毛（需PS编辑皮肤PNG）

---

## 🔄 版本更新说明

请前往vrcub.net/mcft

遇到任何问题欢迎联系技术支持：
📮 [mcft-support@vrcub.net](mailto:mcft-support@vrcub.net)

  **本节正在撰写**
