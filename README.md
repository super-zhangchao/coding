```c++
c++
  map["1"]
  如果keys中不存在"1"，那么map会自动赋值。这个非常隐蔽。
```
```java
java
  阿里巴巴 Java 开发手册，2016-12月阿里发布的JAVA技术开发手册，首次向业界公开 Java 开发手册，总共五大章节，干货满满，大多数规约还有说明以及正、反代码实例，对于新手而言能从中学到很多知识。还有就是非常适合全公司推广，利于项目维护以及规范开发。
```
```python
python
  # 集合需要加set，而list和dict只需要[]、{}。
  f = []
  f = set()
  f = {}
```
```git
git
  pull 下来的时候要首先fetch diff merge
  https://github.com/tobegit3hub?tab=repositories
```
```shell
shell
  （4）find 查找可执行文件
  find . -perm /u+x

  History命令主要用于显示历史指令记录内容

  sort问题
  对罗马字符不支持，导致排序错误

  统计行出现次数
  sort out | uniq -d -c > out3
  sout out out1 out1 | uniq -u > out2 差集

  linux shell
       “(())” 双括号运算符使用

  linux系统
    10.255.34.80 已经添加了 “rm命令转为mv命令”
    36.17空间被占满
    删除链接文件时 文件名或目录后面不要加/ 例如 基于关键字
    删除软链接文件时 要特别小心
```
```vim
vim
  Vim 的 End/Home 键无效的解决方法
      1    E  VK_END                "/033[4~"
      2    E  VK_HOME               "/033[1~"
      3    E  VK_INSERT             "/033[2~"
      4    E  VK_DELETE             "/033[3~"

  delete   删除左边字符
  x        删除当前光标下的字符 没有删除右边字符
  dw       删除光标之后的单词剩余部分。
  d$       删除光标之后的该行剩余部分。
  dd       删除当前行。
  c        功能和d相同，区别在于完成删除操作后进入INSERT MODE
  cc       也是删除当前行，然后进入INSERT MODE
```
```linux
linux ubantu
    vim
        配置
    Bazel
        安装 Bazel
        首先依照 教程（http://bazel.io/docs/install.html） 安装 Bazel 的依赖. 然后使用下列命令下载和编译 Bazel 的源码:
        $ git clone https://github.com/bazelbuild/bazel.git
        $ cd bazel
        $ git checkout tags/0.1.0$ ./compile.sh
        
	java
		
	python
		ANACONDA
		setuptools 23.0.0 pip
			wget https://bootstrap.pypa.io/ez_setup.py -O - | sudo python
			easy_install pip
		sudo apt-get install git
		sudo apt-get install python-pip python-dev python-numpy python-scipy python-matplotlib python-virtualenv
		sudo apt-get install libprotobuf-dev libleveldb-dev libsnappy-dev libopencv-dev libhdf5-serial-dev protobuf-compiler
        sudo apt-get install --no-install-recommends libboost-all-dev
       	sudo apt-get install libatlas-base-dev libgflags-dev libgoogle-glog-dev liblmdb-dev
		sudo apt-get install swig
		
		gensim
			easy_install -U gensim
		
	输入法
        fctix
		添加两个输入法 谷歌拼音和英文
	终端 快捷键
		多标签页
		复制粘贴
			鼠标左键选中即复制
			鼠标中键即粘帖
			ctrl+v也是粘帖
		gsettings set com.canonical.Unity.Launcher launcher-position Bottom
	
    sudo apt-get install laptop-mode-tools 
        挂起 无法唤醒的问题
	
	caffe安装 需要C++的各种类库 安装成功
	    #!/bin/bash
        sudo apt-get install git
        sudo apt-get install libprotobuf-dev libleveldb-dev libsnappy-dev libopencv-dev libhdf5-serial-dev protobuf-compiler
        sudo apt-get install --no-install-recommends libboost-all-dev
        sudo apt-get install libatlas-base-dev
        sudo apt-get install python-dev
        sudo apt-get install libgflags-dev libgoogle-glog-dev liblmdb-dev

        git clone https://github.com/bvlc/caffe.git
        cd caffe/
        mv Makefile.config.example Makefile.config
	
        安装boost、glob、blas
        sudo apt-get install libprotobuf-dev libleveldb-dev libsnappy-dev libopencv-dev libboost-all-dev libhdf5-serial-dev libgflags-dev libgoogle-glog-dev liblmdb-dev protobuf-compiler protobuf-c-compiler python-pandas
        git clone https://github.com/paulsapps/gmock-1.7.0
        protobuf 重要
        BLAS-3.6.0 CBLAS
    
    tensorflow
		sudo apt-get install python-pip python-dev python-virtualenv
		virtualenv --system-site-packages ~/tensorflow
		cd ~/tensorflow
		source bin/activate
		pip install --upgrade https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.5.0-cp27-none-linux_x86_64.whl
	    
    theano
        BLAS → LAPACK → ATLAS → numpy → scipy → Theano
        ATLAS
	        OpenBLAS, Intel MKL vs ATLAS
	    pip install nose_parameterized
	    sudo pip install Theano
	        将theano安装到/usr/local/lib/python2.7系统自带python的路径
	        需要使用pip install Theano
	        sudo pip 是系统管理员的pip
	        pip 是当前用户的
    mxnet
	    https://github.com/dmlc/mxnet
	    没有安装
```

```windows
windows
```

```mac
mac
python
    Anaconda
        conda list
        conda install <pkg name> #该命令用于安装应用包，如 conda install numpy.
        pip install <pkg name> #该命令用于安装应用包，如 pip install theano.
        conda update <pkg name> #升级应用包，如 conda update python
    easy-install
    pip
        wget https://bootstrap.pypa.io/get-pip.py
        sudo python get-pip.py
    Pillow
    setuptools
        curl https://bootstrap.pypa.io/ez_setup.py -o - | python
    tensorflow
        bazel
            brew install bazel
    swig
            brew install swig
        brew install bazel swig
        $ sudo easy_install -U six
        $ sudo easy_install -U numpy
        $ sudo easy_install wheel

        $ sudo easy_install ipython
        
        can't determine number of CPU cores
    caffe
    theano
    
mac
    wine + notepad++
    mac 安装brew wine

第一层 操作系统
第二层 编程语言 编译器
第三层 应用软件

系统
	chrome
	搜狗拼音输入法	
	Sublime Text
	eclipse
	pycharm

终端配置
    使用ll、la、l等ls的别名命令
        alias ll='ls -lF'
        alias la='ls -A'
        alias l='ls -CF'
	homebrew
        ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
        搜索软件：brew search 软件名，如brew search wget
        安装软件：brew install 软件名，如brew install wget
        卸载软件：brew remove 软件名，如brew remove wget
    wget brew install wget
    oh-my-zsh 切换 chsh -s /bin/zsh
    git brew install git
    bazel brew install bazel
    swig brew install swig
    gcc brew install gcc47
    xcode
	
编程
    c/c++
        cmake
    java
        /usr/bin/java
    python
        anaconda2
		setuptools
        easy_install
        pip
        numpy scipy
	
平台
	tensorflow
		pip install tensorflow
	maxnet
		
	caffe

应用软件
	浏览器 chrome
    腾讯企业邮箱 https://exmail.qq.com/cgi-bin/loginpage?t=dm_loginpage&s=logout&param=zhang_chao@gowild.cn
    微信网页版
    百度云网页版 http://pan.baidu.com/disk/home?errno=0&errmsg=Auth%20Login%20Sucess&stoken=eafb6891f34b7442f1667606a1365a1b14ff9f15253f91986ee441a82fccbacc10c6c003d069351d4bac8c35453c9618357fe8c5d15dae7e1fb7aef5a57587d951682a6c8806&bduss=035ce1d54c5cd4cb4561c350cdb1e11f285cd857bb8d7508358ec75b644781eef77df8166677cc150605d17cc3b19f762f97d4501552ba965e1cd850479810c58e30635d38adccf2f9583070733fed8246900a0410520325515e346f38904be1ca4b71a8c707bc1def5742b45a016d503fa40883397d046b45914a76668db9b3f8c9f1d87c5bd6cc5473678e5db4f459277300d96f1221693500d2aad9b4d034924b1cea44720b551f522bd7160652a38e6b4a851438016889b5e7060daf7f6f2114d96f7e3c&ssnerror=0#list/path=%2F&vmode=list
	爱奇艺
	百度云盘
	winrar
```

```markdown
markdown
```






