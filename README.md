# 简介
使用git颜文字美化commit

# 安装&使用
- 打开终端(命令行模式),将颜文字模板内容设置到commit.template里
```
git config --global commit.template /path/to/commit.template
```

- 安装`emojify`解决命令行下,无法查看颜文字问题
```
ubuntu
$ sudo sh -c "curl https://raw.githubusercontent.com/mrowa44/emojify/master/emojify -o /usr/local/bin/emojify && chmod +x /usr/local/bin/emojify"

OS X
brew install emojify
```

# 参考
- [gitmoji.carloscuesta.me](https://gitmoji.carloscuesta.me/)
- [emojify](https://github.com/mrowa44/emojify)