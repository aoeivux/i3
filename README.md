1、左下角右上角的状态栏是conky，可以在rofi $mod+d 打开之后，输入pamac-manager把conky进行卸载重启一下即可消失。

2、新安装的系统蜂鸣器的叫声，在～/.xprofile 或者 ~/.profile 加入xset  -b即可关闭。


+ kde主题
Nordic-bluish

# i3 
透明引擎
+ picom

fcitx5输入法
修改~/.xprofile

```shell
  export QT_IM_MODULE=fcitx
  export GTK_IM_MODULE=fcitx
  export XMODIFIERS="@im=fcitx"
  fcitx5 &
```

+ rofi



