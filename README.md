# Ubuntu EVE CN

1. 遵循教程安装Ubuntu [yusefnapora/pixelbook-linux](https://github.com/yusefnapora/pixelbook-linux)

2. clone 脚本到本地后，如果你需要开启触控板的 `Tap Drag` 功能，需要在文件`ansible/roles/eve-touchpad/files/conf/50-touchpad-cmt-eve.conf`中添加 `Option "Tap Drag Enable" "1"`

3. 

4. lib目录内文件仅仅修改了google助理键盘为 Leftmeta  
  usr目录内是自定义的Pixelbook的键盘，如有需要可以修改symbols/eve文件  
5. 暂未有自动化脚本，**请勿直接拷贝替换文件，以免出现错误**  

  ![new keyboard layout for eve](https://raw.githubusercontent.com/Lyuzonggui/eve-cn/master/keyboard.png)

