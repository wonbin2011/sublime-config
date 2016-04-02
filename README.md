Sublime 3 config files

我使用的操作系统是 centos7 不同的操作系统，在 sublime 配置上会有微小的差别。

我使用 Package Control，所有我安装的包在 Package Control.sublime-settings 文件 中都列出了。

安装步骤

－ 在新系统上 sublime 3/2 安装好之后

cd /home/your_dir/.config/sublime-text-3/Packages/User

git clone 
mv sublime-config/* .
rm -rf sublime-config

到 https://packagecontrol.io/installation 安装 packagecontrol 。这样所有的包会自动安装上。（ ctrlA跟 导引号 来呼叫出 command console ）

