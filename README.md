# 时间：2020年4月21日不再建议使用旧版Chrome（ps. 仅作为爱好者使用）

> 这两天用chrome 70.0.3538.110一直闪退，Google也一直强调安全性问题让升级到最新版，所以请看到到朋友们不要再使用旧版UI的Chrome。
>
> PS：如果你只是想体验下旧版ChromeUI，那欢迎下载。
>



 

## Chrome 70.0.3538.110 win&mac (最后一个可以改为老版UI的chrome)

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
