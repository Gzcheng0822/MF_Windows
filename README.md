## 1. 预装

**001.Edge**

- [x] 移除 内置`Edge/Edge Webview`(By MSEdge_EBView2_Removal_Tool)
- [x] 移除 系统内 Edge Webview2文件
- [x] 更新 Edge Webview2 到最新版本,并禁止更新

**002.Chrome**

- [x] 预装 Chrome 130.0.6723.117
- [x] 屏蔽 Chrome 更新提示/旧版提示

**003.Installers**

- [x] 预装 7-zip,预设置
- [x] 预装 Typora(破解版), 预设置,预装Pandoc
- [x] 预装 Everything,快捷键为Win+Ctrl+Space
- [x] 预装 GPU-Z
- [x] 预装 Python 3.12
- [x] 预装 Image Class 和 VLC Player 代替微软照片/播放器
- [x] 预装 Notepad++

**004.oldApps**

- [x] 预留 微信输入法旧版安装包 `1.12` (修改系统名称后安装)
- [x] 预装 火绒 5.X版本 关闭更新提醒 默认关闭 弹窗拦截 自动处理病毒

**005.Runtime**

- [x] 预装 Windows 常用运行库

**006.PortableApps**

- [x] 预装 一些便携版软件,路径`C:\Users\Userme`
- [x] 预装 Ditto (剪切板记录) NDM (多线程下载器)、QuickLook (空格预览)
- [x] 预装 常用工具,Traffic Monitor更新到了最新版,支持12代以上的CPU显示频率
- [x] 预装 Java, ADB, Scrcpy, ffmpeg 并且加入了环境变量, 默认 Java11-22 使用高性能图形卡

**007.From Microsoft Store**

- [x] 预装 QuickLook
- [x] 预装 Wintoys

**008.Fonts**

- [x] 默认安装 Robot
- [x] 默认安装 Source Code pro
- [x] 默认安装 MiSans
- [x] 默认安装 HarmonySan

**009.Wallpaper**

- [x] 内置 三张壁纸

**010.Mouse Skin**

- [x] 内置 鼠标皮肤(Windows 11 Concept Cursors), 鼠标大小默认设置为`3`

## 2.Set By Apps

**001.By DefenderRemover**

- [x] 默认关闭 UAC弹窗(By DefenderRemover)
- [x] 彻底删除 Windows 安全中心(By DefenderRemover)

**002.By Wintoys**

- [x] 启用 卓越性能模式(需手动开启)(By Wintoys)
- [x] 默认 关闭活动历史记录(By Wintoys)
- [x] 默认 关闭各种Windows广告(By Wintoys)
- [x] 默认 启用传递优化(仅本地网络)(By Wintoys)
- [x] 默认 启用网络任务卸载到网卡(By Wintoys)
- [x] 默认 Windows更新 修改为只接受安全更新(By Wintoys)
- [x] 默认 关闭`微软商店`App自动更新(貌似没用)(By Wintoys)
- [x] 默认 壁纸质量为100(By Wintoys)
- [x] 默认 文件管理器不显示主文件/图库(By Wintoys)
- [x] 默认 快速访问只显示桌面/下载/文档(系统设置)
- [x] 默认 隐私保护只打开锁屏使用摄像头(By Wintoys)
- [x] 默认 关闭所有广告(By Wintoys)
- [x] 默认 开启时钟显示秒钟/结束任务(By Wintoys)
- [x] 默认 Alt+Tab 不单独显示网页Tab
- [x] 默认 开启DMA(欧盟隐私保护,玄学,不一定有用)(By Wintoys)
- [x] 默认 开启 开发者模式(By Wintoys)

**003.By DISM++**

- [x] 同步 大部分修改到系统默认设置(By DISM++)
- [x] 默认 关闭任务栏无用功能(By DISM++)
- [x] 默认 壁纸质量显示为100%(By DISM++)
- [x] 默认 关闭SmartScreen应用筛选(By DISM++)
- [x] 默认 关闭程序的"安全警告"(By DISM++)
- [x] 默认 关闭开始菜单的建议/广告(By DISM++)
- [x] 默认 登录界面打开小键盘(By DISM++)
- [x] 系统级 关闭OneDrive(By DISM++)
- [x] 默认 显示所有扩展名(By DISM++)
- [x] 调整一些Explorer的默认行为(By DISM++)
- [x] 禁用 右键菜单无用选项(By DISM++)
- [x] 禁用 各种日志(By DISM++)

**004.By Windows11轻松设置**

- [x] 默认 开启系统还原
- [x] 默认 关闭搜索热点/小组件/自动更新硬件驱动/改善客户体验计划/程序兼容性助手/诊断服务(By Windows11轻松设置)
- [x] 卸载 相机/终端/微软商店以外的所有 UWP App(By Windows11轻松设置)
- [x] 禁止 `Windows搜索索引` 服务,禁止云内容搜索/Web搜索(不影响系统内置设置搜索)(By Windows11轻松设置)
- [x] 隐藏 快捷方式角标/文字(By Windows11轻松设置)
- [x] 默认 隐藏管理员运行图标(By Windows11轻松设置)
- [x] 还原 Windows10 右键菜单(By Windows11轻松设置)
- [x] 默认 关闭系统休眠(By Windows11轻松设置)
- [x] 默认 开启远程桌面(By Windows11轻松设置)

## 3.组策略

- [x] 1.屏蔽Windows大版本更新
- [x] 2.屏蔽Windows驱动更新
- [x] 3.屏蔽Windows自动更新

## 4.注册表

- [x] 修改 Windows 更新最大可暂停更新时间为 1000 周

  ```
  计算机\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WindowsUpdate\UX\Settings\FlightSettingsMaxPauseDays
  ```

## 5. 内置驱动

- [x] 内置了安卓ADB驱动
- [x] 内置了KVM虚拟机所需硬盘/网卡驱动
- [x] 内置大部分 Intel WIFI6/6E/7 X722 1G/2.5G 网卡驱动

## 6. 电源管理优化

- [x] 默认 禁用休眠
- [x] 调整 节电模式为从不
- [x] 调整 关闭屏幕时间为 1 分钟(电池) 从不(插入电源))
- [x] 调整 硬盘关闭时间为 1 分钟(电池) 从不(插入电源))
- [x] 调整 PCIE 省电为 最大省电(电池) 关闭(插入电源)
- [x] 修改 电源计划中显示更多实用选项,隐藏一些不常用选项(By Windows 高级电源辅助管理工具)

## 7.设置Windows虚拟内存

- [x] 默认 SWAP 文件为16MB-16GB

## 8.远程连接&网络优化

- [x] 默认 打开远程连接
- [x] 默认 打开网络发现
- [x] 默认 开启无密码连接(By 本地安全策略)

## 9.Modify Windows Fonts

- [x] 替换 Windows 系统字体为 MiSans

## 10.系统设置

- [x] C盘命名为Win
- [x] 默认 创建好 vGPU 文件夹
- [x] 默认 设备名为 WindowsPC
- [x] 默认 打开请勿打扰
- [x] 默认 日历默认显示农历
- [x] 默认 开始菜单显示设置图标
- [x] 默认 多任务处理 设置最小贴靠, 网页不显示在Tab中
- [x] 默认 关闭位置信息

## 11.系统组件

- [x] 还原 Windows10 记事本
- [x] 还原 Windows10 任务管理器(Windows11 23H2 Only)

## Final. 系统更新与清理

- 清理 注册表残留

- 删除 无用UWP 应用

- 删除 UWP应用 残留文件

- 删除了制作过程中产生的 Windows日志

- 删除 制作过程中产生的网络适配器 

- 目录:

  ```
  计算机\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\NetworkList
  ```

### 删除设备管理器多余设备

```
$hiddenDevices = Get-PnpDevice -PresentOnly:$false 
foreach ($device in $hiddenDevices) {
    Write-Output "Hidden device: $($device.FriendlyName)"
	&"pnputil" /remove-device $device.InstanceId
}
```

### 打开休眠

```
powercfg /hibernate on
```

### 关闭休眠

```
powercfg /hibernate off
```

### 提示

1. 开机记得打开Driver store explorer删除多余网卡驱动
2. 记得激活系统(开始菜单里有激活工具)
