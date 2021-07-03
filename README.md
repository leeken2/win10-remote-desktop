# win10-remote-desktop

win10 多用户远程桌面破解

[主要教程](https://github.com/asmtron/rdpwrap/blob/master/binary-download.md)

1. 下载第一步中的 `RDPWrap-v1.6.2.zip`，点击 `install.bat`，会自动生成 `C:\Program Files\RDP Wrapper` (normally)
2. 复制压缩包内所有的文件到 `C:\Program Files\RDP Wrapper`
3. `autoupdate.bat` 因为墙的问题，不能正确更新
4. 通过 `autoupdate.bat` 的报错可获取 `rdpwrap.ini` 的[更新地址](https://raw.githubusercontent.com/asmtron/rdpwrap/master/res/rdpwrap.ini)
5. 覆盖 `rdpwrap.ini` 中的内容
6. 重启测试
 
运行 RDPConf.exe，全绿说明成功

## 注意事项
- [win10多用户远程登录](https://www.cnblogs.com/wmxl/p/10037326.html)
