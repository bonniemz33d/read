.. _articles2420:

老手是这样教新手编程的
======================

2010年5月13日 `陈皓 <http://coolshell.cn/articles/author/haoel>`__

comp.lang.c全球最大的C语言新闻组，其Google的链接是：\ `http://groups.google.com/group/comp.lang.c/ <http://groups.google.com/group/comp.lang.c/>`__
可惜被GFW了。在comp.lang.c新闻组，有一个日本网友发了个\ `贴子 <http://groups.google.com/group/comp.lang.c/browse_thread/thread/9f3faa6af28577f2/e105e5d339edec01?hide_quotes=no>`__\ ，说他正在学习一个在线的C语言课程，要完成一个作业，用程序输出如下的结果，而他的老师在美国，因为时差问题，他无法和他联系，所以只有上这里来寻求帮助。

::

        *
       ***
      *****
     *******
    *********
    *********
     *******
      *****
       ***
        *

很明显，在comp.lang.c上发这种贴子是一定会被拍的很惨的，这样的事，以前在SUN的论坛上也发生过，\ `详情请看这里 <http://coolshell.cn/articles/1391.html>`__\ 。还有一个去软件\ `官网上要一个盗版序列号 <http://coolshell.cn/articles/1693.html>`__\ 的。果不然后，我看到了这样的一个\ `回贴 <http://groups.google.com/group/comp.lang.c/msg/e105e5d339edec01>`__\ 。提供这样的一段代码：

::

    #define      M 002354l
    #define     A   000644l
    #define    G     000132l
    #define     I   000322l
    #define      C 000374l
    #define                a ;
    #define               b for
    #define              c    ++
    #define             d       %
    #define            e       int
    #define           f           ,
    #define          g             -
    #define         h             011
    #define        i                 =
    #define       j                   {
    #define      k                     )
    #define     l                    '\n'
    #define    m                      main
    #define    n                         <
    #define     o                       }
    #define      p                     >
    #define       q                  &&
    #define        r                 (
    #define         s              ||
    #define          t             ?
    #define           u     putchar
    #define            v      void
    #define             w     '*'
    #define              x     :
    #define               y ' '
    #define                _ /
    #define           C_O_O_L return
                       e u r e k a
                             e
                            m r
                           v k j
                          j j j j
                         j j j j j
                        j j j j j j
                       j j j j j j j
                      j e z a b r z i
                     M _ A _ G _ I _ C
                    a z n G a u r z d h
                   + z _ h p M _ A q z d
                  h + z _ h n M _ G q z _
                 h n z d h + M _ I q z _ h
                p z d h g M _ C t w x y k f
               z d h g h + 1 s u r l k f z c
              k a u r l k a j j j j j j j j j
             j j C_O_O_L M _ A _ G _ I _ C a o
            o o o o o o o o o o o o o o o o o o
                          o o o o
                          o o o o
                          o o o o
                          o o o o

这段程序是可以编译通过的，没有任何问题，而且还是可以得到正确的结果的。关于这样的程序，你可以参考本站的这篇文章《\ `6个变态的C语言Hello
World程序 <http://coolshell.cn/articles/914.html>`__\ 》，而另一篇文章教你\ `如何搞乱你的C代码 <http://coolshell.cn/articles/933.html>`__\ 。呵呵。当然，你并不需要把在你的VC或是GCC下编译这段代码，现在什么都有在线了，编译器当然也在线了，这里是一篇关于\ `在线编译器的文章 <http://coolshell.cn/articles/1310.html>`__\ ，甚至一个\ `在线的IDE <http://coolshell.cn/articles/1883.html>`__\ （连这个网站的CTO都在本站\ `留言 <http://coolshell.cn/articles/1883.html#comment-2234>`__\ 了），上去编译一下你就可以看到\ `结果 <http://codepad.org/Rh6icaWU>`__\ 了。

最后，不恶搞了，在comp.lang.c的这个贴子中看到了很多不错的“如何教新手编程”的观点，下面罗列一些：

1）你把你自认为最好程序贴出来，我会帮你看的，但我是不会帮你写的。

2）要解决这个问题，你需要先观察输出，然后找到其规律，算法总是去描述一些有规律的事情。关于你的这个程序，很明显，你可以分成两个部分，一个正三角，一个倒三角，每一行的星号都是连续的奇数，1，3，5，7，9，而前面的空格又是顺序的自然数：4，3，2，1，你看这样的规律用程序来干不是正合适吗？

从这两个例子，我们可以看到，老手应该如何去教新手，那就是，a）让其独立思考，b）步步为营的引导，c）教一种方法而不是直接给答案。希望与大家共勉。

（全文完）

.. |image6| image:: /coolshell/static/20140922095905585000.jpg

.. note::
    原文地址: http://coolshell.cn/articles/2420.html 
    作者: 陈皓 

    编辑: 木书架 http://www.me115.com