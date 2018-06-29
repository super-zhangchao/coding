python
    defaultdict

python list 和 numpy array 的互转

python去掉字符串空格的方法
    strip lstrip rstrip
    replace
    split
    正则表达式
    
python安装包
    NumPy 安装语句 sudo apt-get install python-numpy
    SciPy安装语句 sudo apt-get install python-scipy
    sudo apt-get install python-setuptools
    sudo easy_install rsa
    gensim了，安装语句 sudo easy_install -U gensim

python 当不确定字符串是str还是float还是int时，直接使用str()。

python 函数参数带星号*
    带一个星号（*）参数的函数传人的参数存储为一个元组（tuple）；
    而带两个星号（*）参数的函数传人的参数则存储为一个字典（dict）

时间统计
    start = datetime.datetime.now()
    for i in range(1):
        beg = datetime.datetime.now()
        #print beg
        
        end = datetime.datetime.now()
        #print end
        #print end - beg
        time_list.append(end-beg)
    #print max(time_list), min(time_list)
    #print 'avg ', (datetime.datetime.now() - start) / len(time_list)

写文件 
    如果是unicode，则需要添加sys.setdefaultencoding('utf8')，否则写入失败

f=lambda x:x==1
    f(1)    True
    f(2)    True


C++ 与 python 的客户端 服务端的相互调用
c++.c c++.s
python.c python.s
四者之间的相互调用

python 比较list两个是否相等

python 的 if else 单行 表达
    a = 2 if b == 4 else 1
string与list互转
    lst = list(str)
python sorted cmp 对称策略
    cmp(x, y) * cmp(y, x) == -1
详解Python中的下划线
    n = 42 
    for _ in range(n): 
        do_something()
    有存在的必要性，但后面不会用到的情况下
itertools chain
Counter most_common
collections.namedtuple
如何用Python写一个贪吃蛇AI
    http://www.imooc.com/article/8315
项目
    Open Chinese Convert 開放中文轉換
        pip install opencc-python
        
    读书
        用Python读红楼梦
        用Python看金庸武侠
        
    游戏
        贪食蛇
            如何用Python写一个贪吃蛇AI
        五子棋
            BetaMeow：利用机器学习做五子棋AI
                https://github.com/MashiMaroLjc/ML-and-DM-in-action
    
    爬虫
        python 抓取微信公众号文章



