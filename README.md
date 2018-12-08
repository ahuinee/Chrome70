## Chrome 70.0.3538.110

### 切换为老版UI

浏览器输入：`chrome://flags/#top-chrome-md`

将`Default`改为`Normal`即可

### Mac 禁止Chrome更新

```bash
$ cd ~/Library/Google
$ ls
GoogleSoftwareUpdate
```
使Google丢失对文件夹操作的权限（达到禁止更新Chrome的效果）
```bash
$ sudo chown root:wheel GoogleSoftwareUpdate
```

### 下载地址（官方）：

win:

https://dl.google.com/release2/chrome/QNAYH6TuhXA_70.0.3538.110/70.0.3538.110_chrome_installer.exe

mac:

https://dl.google.com/release2/chrome/AODD0i9IJlvh_70.0.3538.110/GoogleChrome-70.0.3538.110.dmg
