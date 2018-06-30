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
Google 开源项目风格指南 (中文版)

https://github.com/tobegit3hub?tab=repositories

```
Elastic Search
	是一个建立在全文搜索引擎 Apache Lucene? 基础上的搜索引擎。
```
```
RabbitMQ
	RabbitMQ是一个开源的AMQP实现，服务器端用Erlang语言编写，支持多种客户端，如：Python、Ruby、.NET、Java、JMS、C、PHP、ActionScript、XMPP、STOMP等，支持AJAX。用于在分布式系统中存储转发消息，在易用性、扩展性、高可用性等方面表现不俗。
```
C# 写的呼呼的，Keras 跑的溜溜的，Docker也用的熟熟的，ElasticSearch, RabbitMQ, Storm, Spark
	

机器学习框架
	分布式
		
深度学习框架
	分布式
		mxnet

matlab
	MATLAB: 简单易用的 HPC 语言集成计算、可视化以及编程
```	
Anaconda命令
conda list #该命令，将列出Anaconda安装的所有应用包，我们可以看到Anaconda已经安装了numpy, nose, pip, python, scipy, mingw等等。
conda install <pkg name> #该命令用于安装应用包，如 conda install numpy.
pip install <pkg name> #该命令用于安装应用包，如 pip install theano.
conda update <pkg name> #升级应用包，如 conda update python
conda install mingw libpython
pip install theano #安装theano
```
numpy
	shape
		(100, 10)
		axis=0 [:][0]
		axia=1 [][]
	reshape
		函数功能：给予数组一个新的形状，而不改变它的数据
	多维数组
		如果将三维数组的每一个二维看做一个平面（plane，X[0, :, :], X[1, :, :], X[2, :, :]），三维数组即是这些二维平面层叠（stacked）出来的结果。则（axis=0）表示全部平面上的对应位置，（axis=1），每一个平面的每一列，（axis=2），每一个平面的每一行。
		假设shape = (100, 10, 20)
		轴上的操作相当于消去相应的shape值
			axis = 0 shape = (10, 20)
			axis = 1 shape = (100, 20)
			axis = 2 shape = (100, 10)
		三维数组的轴操作得到二维数组
		二维数组的轴操作得到一维数组
		多维数组
			第0轴代表 第0轴的索引的for循环
			第1轴代表 第1轴的索引的for循环
			第2轴代表 第2轴的索引的for循环
			i,j,k,l,m,n
				axis=3 相当于 先变化为 i,j,k,m,n,l 后对最后的列表运算
		二维数组 
			第0轴的sum max 相当于 每列的sum max 或者 先转置后每行的sum max
			第1轴的sum max 相当于 每行的sum max
			行列式矩阵概念
	加减乘除
		减法
			二维数组和一维数组相减 条件 行数相同
	exp
	flatten
	astype(np.int)
	random
		randint
			np.random.randint(0,10) 随机一个数
		uniform

caffe
	用于脑回神经网络算法的架构
```
    theano
    用于定义、优化以及评估数学公式的 Python 库
    张量 标量 向量 矩阵 
    theano安装
        安装Anaconda
        安装mingw
        安装theano
    theano学习
        0阶张量叫标量(scarlar)；1阶张量叫向量(vector)；2阶张量叫矩阵(matrix)
        lscalar int64
        theano.tensor
            mean 均值
            log(x) 对数
            arrange(n) 

        theano的shared是为了GPU
        theano.function
            declare symbolic variable
            build symbolic expression
            compile function
            print
        T.nnet.softmax 输入是个向量
        T.neq
```
		
		
spark
mahout
	Mahout
	Mahout是一个广为人知的开源项目，它是Apache Software旗下的一个开源项目，提供了众多的机器学习经典算法的实现，旨在帮助开发人员更加方便快捷地创建智能应用程序。Mahout内包含了聚类、分类、推荐等很多经典算法，并且提供了很方便的云服务的接口。

MLlib
	MLlib是Apache自己的Spark和Hadoop机器学习库，它被设计用于大规模高速度地执行MLlib所包含的大部分常见机器学习算法。MLlib是基于Java开发的项目，同时可以方便地与Python等语言对接。用户可以自己设计针对MLlib编写代码，这是很具有个性化的设计。
libsvm
liblinear
Scikit-learn

cuda-convnet: 脑回神经网络的高性能 C++/CUDA 软件实施
Theano: 
Torch7: 用于机器学习算法的科学计算架构 
cuBLAS: GPU 加速版本的完整标准 BLAS 库

cxxnet: 神经网络工具包

```
mxnet
	module
	initializer
	metric
	optimizer
		Optimizer
		SGD
		DCASGD
		NAG
		SGLD
		ccSGD
		Adam
		AdaGrad
		RMSProp
		AdaDelta
		Test
		create
		Updater
	model
		BatchEndParam
		save_checkpoint
		load_checkpoint
		FeedForward
	symbol
		Symbol
			bind
		Variable
		Group
		
		mxnet.symbol.Convolution
		mxnet.symbol.SVMOutput
		mxnet.symbol.SequenceMask
		mxnet.symbol.SequenceReverse
		mxnet.symbol.SliceChannel
		mxnet.symbol.Softmax
		mxnet.symbol.SoftmaxActivation
		mxnet.symbol.SoftmaxOutput
		mxnet.symbol.SpatialTransformer
		mxnet.symbol.SwapAxis
		mxnet.symbol.UpSampling
	executor
		Executor
			forward
			backward
			set_monitor_callback
			arg_dict
			grad_dict
			aux_dict
			output_dict
			copy_params_from
			reshape
	test_utils
		default_context
	io
		DataDesc
		DataBatch
		DataIter
		ResizeIter
		PrefetchingIter
		NDArrayIter
		MXDataIter
		CSVIter
		ImageRecordIter
		ImageRecordUInt8Iter
		MNISTIter
	ndarray
		waitall
		NDArray
		onehot_encode
		empty
		add
		subtract
		multiply
		concatenate
		arange
		load
		Convolution
		uniform
	random
		seed
	context
		Context
		cpu
		gpu
		current_context
	kvstore
		KVStore
		create
	
	[<NDArray 100x10 @cpu(0)>, <NDArray 100 @cpu(0)>]
	
	<type 'numpy.ndarray'> 2 <class 'mxnet.ndarray.NDArray'>
		mx.nd.array(x)
	<class 'mxnet.ndarray.NDArray'> 2 <type 'numpy.ndarray'>
		x.asnumpy()
		
	x[<type 'numpy.ndarray'>, <type 'numpy.ndarray'>] -= 1.0
		相当于zip
	Computer Vision
	Natural Language
		softmax
		CNN
		RNN
		LSTM
		VAE
		GAN
```
	
```
nlpir
    pynlpir.open(data_dir=nlpir.PACKAGE_DIR, encoding=ENCODING, encoding_errors=ENCODING_ERRORS, license_code=None)
    pynlpir.close()
    pynlpir.segment(s, pos_tagging=True, pos_names='parent', pos_english=True)
    pynlpir.get_key_words(s, max_words=50, weighted=False)
    pynlpir.nlpir
        pynlpir.nlpir.get_func(name, argtypes=None, restype=c_int, lib=libNLPIR)
        pynlpir.nlpir.Init(data_dir, encoding=GBK_CODE, license_code=None)
        pynlpir.nlpir.Exit()
        pynlpir.nlpir.ParagraphProcess(s, pos_tagging=True)
        pynlpir.nlpir.ParagraphProcessA(s, size_pointer, user_dict=True)
        pynlpir.nlpir.ImportUserDict(filename)
        pynlpir.nlpir.AddUserWord(word)
        pynlpir.nlpir.FileProcess(source_filename, result_filename, pos_tagging=True)
        pynlpir.nlpir.GetKeyWords(s, max_words=50, weighted=False)
        pynlpir.nlpir.GetFileKeyWords(filename, max_words=50, weighted=False)
        pynlpir.nlpir.GetNewWords(s, max_words=50, weighted=False)
        pynlpir.nlpir.GetFileNewWords(filename, max_words=50, weighted=False)
        pynlpir.nlpir.FingerPrint(s)
        pynlpir.nlpir.SetPOSmap(pos_map)
    pynlpir.pos_map
```
	







