安装pycharm tmux htop等工具，使用pycharm设置：
1. vim ~/.bashrc
2. shift+g 到最后一行 把pycharm.sh的文件路径添加进去alias pycharm="sh /usr/local/pycharm/pycharm-community-2019.2.3/bin/pycharm.sh"
3. source ~/.bashrc终端输入pycharm，远程debug
命令|用途
----|----
conda creat -n XX your_env_name python=2.7|创建环境
conda remove -n your_env_name --all|删除环境
source activate your_env_name|激活
source deactivate your_env_name|退出
conda env list|显示所有虚拟环境
