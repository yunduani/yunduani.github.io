+++
date = '2025-11-12T09:50:20+08:00'
draft = false
title = 'Window'
categories = ["Windows 系统"]
+++


### 针对window关机的时候提示软件未关闭进行的强制关闭策略
```
按 `Windows + R` 打开运行窗口，输入 `regedit`，点击确定。
路径栏输入 `HKEY_USERS\.DEFAULT\Control Panel\Desktop`，按回车键。
右键点击 `Desktop`，点击新建 → 字符串值。
将其命名为 `AutoEndTasks`，并双击打开。
数值数据改为 `1`，点击确定。
```




<a href="https://imgchr.com/i/pZCVxit" target="_blank"><img src="https://s21.ax1x.com/2025/11/12/pZCVxit.webp" alt="Windows 注册表操作示意图" border="0" width="150" height="150" /></a>