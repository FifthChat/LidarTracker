# LidarTracker v3.0

A lidar tool made with Touchdesigner C++ CHOP, which can support HOKUYO, SLAMTEC, EAI, PHOTOPTRY and SIMINICS.

- Connect multiple lidars.
- Multiple lidars merge.
- Add trigger range
- TUIO & UDP

This version is only available in Touchdesigner 2022+.

This version is only available for window platforms.

contact us：**support@fifthchat.com**

# 版本说明 | Release Notes
v3.0.6
- 解决了星秒雷达数据X轴方向相反的问题
- Solved the problem that the X-axis direction of the SIMINICS lidar data is opposite

v3.0.7
- 解决了不同FPS下，元件的数据错误问题
- Solved the data error problem of plugins under different FPS

v3.1.0
- 参数面板新增了语言选择参数
- 参数面板新增了查询本机识别码按钮
- 参数面板查询信息按钮现在新增了当前账号所有已激活设备信息
- 组件面板新增了参数导出与导入功能，方便不同设备间同步参数
- 现在可通过帮助窗口中的下载按钮，下载最新版本插件
- Added a language selection parameter in the parameter panel.
- Added a button to query the UUID in the parameter panel.
- The query button in the parameter panel now adds all activated device information for the current account.
- The plugin panel has added parameter export and import functions to facilitate the synchronization of parameters between different devices.
- The latest version of the plugin can now be downloaded via the download button in the help window.

v3.2.2
- 解决某些情况下拉菜单无法打开的问题
- 解决触发区域滚动条不清晰问题
- 触发区域可以通过Ctrl+左键设置位置
- Solve the problem that the drop-down menu cannot be opened in some cases.
- Solve the problem that the scroll bar in the trigger area is not clear.
- The trigger areas can now be set by Ctrl + left click.

v3.2.3
- 添加PHOT雷达的支持
- 选择Hokuyo与星秒雷达时，串口设置为不可选状态
- 解决添加区域滑动条无法显示问题
- Add PHOT Radar support.
- When selecting Hokuyo and StarSecond Lidar, the serial port is set to unselectable state.
- Solve the problem that the slider in the add area cannot be displayed.

v3.2.4
- 驱动数据架构重写，增强了稳定性
- 新增对光觉PHOT雷达支持
- 新增对EAI TEA系列支持，移除对EAT TX系列与T15的支持
- UI界面稳定性优化
- Driver data architecture rewritten to enhance stability.
- Added support for PHOT Lidar.
- Added support for EAI TEA series, removed support for EAT TX series and T15.
- Stability optimization of UI interface.

v3.2.5
- 修复获取HOKUYO雷达数据的BUG
- Fixed a bug in getting HOKUYO Lidar data.

# Tutorial
https://www.youtube.com/playlist?list=PLQjcZ7FICSKODL-hvjV5XxAgrxHJwHpOJ
