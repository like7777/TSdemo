记录使用mac配置ts环境问题
默认使用npm安装完ts后，使用tsc -v查看版本会提示command not found：tsc 。原因是因为环境问题，缺少了.bash_profile以及其配置。
解决方案：在终端输入 vim ~/.bash_profile创建对应文件 输入i进入编辑模式，然后把ts安装路径复制过去，按esc退出编辑模式，在按:wq保存并退出。最后输入source ~/.base_profile让配置生效。