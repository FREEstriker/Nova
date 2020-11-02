# 程序结构

* 核心部分
    * 脚本解析（`ScriptParsing/`）
    * Lua运行时与绑定（`LuaRuntime.cs`）
    * 脚本变量系统（`Variables.cs`）
    * 存档系统（`CheckpointManager.cs`、`Restoration/`）
    * 游戏状态（`GameState.cs`）
    * 资源加载与缓存（`AssetLoader.cs`）
    * 动画系统（`Animation/`）
    * 特效系统（`VFX/`，对shader和material的绑定）
    * 设置系统（`ConfigManager.cs`）
    * 国际化系统（`I18n.cs`）
    * 输入系统（`Input/`，包括快捷键功能，以后可能会用Unity的input system代替）
* 前端部分
    * 演出组件
        * 图片（sprite）
        * 角色
            * 立绘部件裁剪与元数据
            * 立绘合成
            * 自动淡入淡出
            * 语音
        * 音乐
        * 音效
        * 摄像机
        * 时间轴（timeline）
        * 摄像机遮罩
        * 自动语音
    * UI
        * 对话框（以后会移到演出组件）
        * 菜单
        * 分支选项
        * 文本回顾界面
        * 存档/读档界面
        * 图片鉴赏界面
            * 图片元数据
        * 音乐鉴赏界面
            * 音乐元数据
        * 设置界面
        * 警告框
        * 通知框
        * 窗口缩放系统（`GameRenderManager.cs`）
        * 国际化组件