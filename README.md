#我的vim配置

- 特别为python编程定制
- 需要exuberant ctags, 且只支持`exuberant ctags`，别的ctags不好使，比如mac自带的ctags就不行.（_vim/external_program 里有个ctags-5.8，有必要的话，可以编译这个）
- 需要安装pep8
- 添加了 golang 的配置，需要自己安装golang 和 gotags 并设置 gotags 需要的环境变量等, 如果不需要/不喜欢，可以在_vimrc 里把关于 golang那段注掉.

##注意
- 设置了 noswapfile，没有swap文件，在_vimrc 最后边.

##使用

- 把`_vimrc`软链接到 `~/.vimrc`
- 把`_vim`软链接到 `~/.vim`
- `ctrl + hjkl 切换窗口`
- `,n` 打开nerdtree，`i 或者 s` 分别横竖打开文件
- `,tb` 打开tagbar
- `,8` 做 pep8 检查
- 另外装了OminCompletion， pyflakes ，Django 模版语法支等一坨东西，还有一堆常用的 snippets，可以自己玩玩.
- 其他想起来再说.
