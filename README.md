# 最后一个旧版UI的Chrome 70.0.3538.11

> 这是最后一个可切换到旧版本UI的Chrome，包含win和mac版本；相比新版本的圆圆感的UI我更觉得旧版给人的感觉更符合Chrome理念：硬朗、干净、极速。
> 
> 时间：2020年4月21日不再建议使用旧版Chrome，这两天用chrome 70一直闪退，Google也一直强调安全性问题提醒升级到最新版。
>
> 仅供怀念或尝鲜下载！


#### 效果图
![效果图](https://user-images.githubusercontent.com/13514929/144783236-ff79f59e-d1f2-4419-8198-257d37688008.png)



 

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

官方连接已失效，请在files文件夹中选择下载！

win（已失效）:

https://dl.google.com/release2/chrome/QNAYH6TuhXA_70.0.3538.110/70.0.3538.110_chrome_installer.exe

mac（已失效）:

https://dl.google.com/release2/chrome/AODD0i9IJlvh_70.0.3538.110/GoogleChrome-70.0.3538.110.dmg
