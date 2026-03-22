 # alienV4去门版 与 alienV4m专用版
------------------------------------------------
  在第一个alienV4.jar中，他是有后门的，这也就意味着如果你用他来玩2b2t.xin,你的基地将有被暴露的风险，
  但第二个就与众不同，他是去除后门的，你的基地不会因此而暴露。
 # 关于alimio
----------------------------------------------- 
  那是我闲的没事做将alienV4的文件中的fabric.mod.json改了一下
  随后再jars文件中放入了mio的开裂版文件，然后发神经发到了github额额额额
  但是这可以减少你装mio的时间，毕竟alienV4加mio可是非常好的外挂组合

  
 # 最后就是我修复的功能

 
# IClientPlayerInteractionManager 

访问客户端与服务器交互的管理器，用于模拟玩家操作（挖掘、放置、攻击等）

# ICloseHandledScreenC2SPacket 

访问「关闭界面」数据包，用于自动关闭容器或 UI
ICommonPongC2SPacket 

访问「响应包」数据包，用于网络延迟检测或心跳功能

# IContainerComponent 

访问容器组件，用于潜影盒查看器、箱子内容读取等功能

# IGameRenderer 

访问游戏渲染器，用于自定义视角、摄像机控制、着色器注入等

# IHandSwingC2SPacket

访问「挥动手臂」数据包，用于模拟攻击动作或自动攻击

# IItemRenderer 

访问物品渲染器，用于自定义手持物品显示、物品模型修改

# IModelPart 

访问模型部件，用于模型修改、实体模型上色

# IModelPartCuboid 

访问模型立方体，用于更精细的模型修改

# INativeImage 

访问原生图像缓冲区，用于截图、图像处理或纹理修改

# IPlayerActionC2SPacket 

访问「玩家动作」数据包，用于发送挖掘、停止挖掘等操作

# IPlayerInteractBlockC2SPacket 

访问「右键方块」数据包，用于自动使用方块（如自动放置、自动使用）

# IPlayerInteractItemC2SPacket 

访问「右键物品」数据包，用于自动使用物品（如自动吃食物、自动投掷）

# IPostEffectProcessor 

访问后处理效果处理器，用于自定义着色器效果

# IScreenHandler 

访问界面处理器，用于界面自动化操作（自动合成、自动交易）

# ISimpleRegistry 

访问简单注册表，用于动态注册物品、方块或实体

# IUpdateSelectedSlotC2SPacket 

访问「更新选中快捷栏」数据包，用于自动切换物品栏槽位

# 以上功能所对应的模块

# 功能模块 使用的 
Accessor

# 自动操作 
IPlayerActionC2SPacket、IPlayerInteractBlockC2SPacket、IPlayerInteractItemC2SPacket、IHandSwingC2SPacket、IUpdateSelectedSlotC2SPacket

# 潜影盒查看 
IContainerComponent、IScreenHandler

# 自定义视角/摄像机 IGameRenderer
# 着色器/视觉效果 IGameRenderer、IPostEffectProcessor
# 模型修改/上色 IModelPart、IModelPartCuboid、IItemRenderer
# 自动容器操作 ICloseHandledScreenC2SPacket、IScreenHandler
# 网络/延迟功能 ICommonPongC2SPacket
# 动态注册 ISimpleRegistry
# 纹理/图像处理 INativeImage













