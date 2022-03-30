# Ranger安装与配置



[参考1](https://eonun.com/posts/c9854b1/)

[参考2](https://www.cnblogs.com/devilmaycry812839668/p/15950982.html)







## 安装



`sudo apt install ranger`








## 安装图标

```bash
git clone https://github.com/alexanderjeurissen/ranger_devicons ~/.config/ranger/plugins/ranger_devicons

echo export RANGER_LOAD_DEFAULT_RC=FALSE >> ~/.zshrc
source ~/.zshrc

echo "default_linemode devicons" >> $HOME/.config/ranger/rc.conf


# ranger-autojump
git clone https://github.com/fdw/ranger-autojump.git ~/.config/ranger/plugins/ranger-autojump

cp ~/.config/ranger/plugins/ranger-autojump/autojump.py ~/.config/ranger/plugins

```





##  w3m图像预览

```bash
sudo apt install w3m-img


```





##  辅助

```bash
sudo apt install libx11-dev libxext-dev   ueberzug  highlight  atool 

sudo apt-get install caca-utils highlight atool w3m  mediainfo  catdoc docx2txt xlsx2csv w3m-img compton  poppler-utils  elinks pdftotext ffmpegthumbnailer
```

## 配置

```bash
ranger --copy-config=all
```

+ creating: /Users/test/.config/ranger/rifle.conf                   # 指定不同类型的文件的默认打开程序
+ creating: /Users/test/.config/ranger/commands.py          # 能通过 : 执行的命令
+ creating: /Users/test/.config/ranger/commands_full.py    # 能通过 : 执行的命令，但这个更全
+ creating: /Users/test/.config/ranger/rc.conf                      # 选项设置和快捷键
+ creating: /Users/test/.config/ranger/scope.sh                   # 当 use_preview_script = true，这个脚本会被调用



```bash
git clone git@github.com:junjiecjj/ranger.git 
```
