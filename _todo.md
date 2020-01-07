  
  tmux卡死问题，client和server都只有一个线程，用tmux kill-window -t 1 终止该window。
  
#### sysprog
   
    https://chortle.ccsu.edu/AssemblyTutorial/
   
    http://kerneltrap.org/node/517
    
    对目录调用 stat 系统调用时的返回值是什么意思？
    sync，syncfs，fsync，fdatasync 等系统调用的区别和注意点？
    lock_gettime() 接口中，CLOCK_REALTIME and CLOCK_MONOTONIC 区别以及适用场景？
    
    正常TCP会话会保持多久？
    TCP/IP重传超时RTO是什么意思？
    优先级倒置是什么意思？    
    
    fork创建的子进程不会继承父进程挂起的信号，而exec创建的进程会继承父进程挂起的信号，为什么？
    进程中的信号相关配置存储在哪里？
    
    chroot 的适用场景是什么？
    select微秒级精读是什么意思？
    poll毫秒精度是什么意思？
    pselect/ppoll纳秒级精但毫秒级已经不可靠
    
    深入linux PAM体系结构    
    EINTER系统调用被中断    
    ctrl+\终止前台进程组中进程并产生core
    
    linux 系统编程p55
    原生编程规范 是什么意思？    
    
#### man

* 看一下 ld 的man手册
* sshpass 做什么用的？
* 添加sudo权限通过wheel方式和编辑sudoers的方式哪个更好？
* shutdown命令的halt是什么意思？
* the /run/nologin file is created to ensure that further logins shall not be allowed. (ref shutdown)
* https://www.ibm.com/developerworks/cn/linux/l-bash-test.html
* windows10 下有ubuntu子系统，可以试用下，尽管据说有不少命令可能还不能用。

* cat /sys/block/sda/queue/read_ahead_kb
* echo c > /proc/sysrq-trigger

* /proc/locks 什么作用
* ps Lp 1234
* ps mp 1234
* ps uxp 1234
* ps lp 1234

* xfs 文件系统写数据有journal么？

* lowest priority APIC routing
* 如果查看占用CPU高的程序？
* 进程以及线程对不同信号的处理方式？

* 内存泄露工具Valgrind了解

* linux 内核中的三个 tcp keepalive参数是什么含义？
* /proc/net/dev
* /proc/net/snmp    
* ifdown和ifconfig区别？

* iopath结合图理解

  #### acm  
  
    信心上限树是什么(UCT) 是什么东西？
    std::hash (std::bitset)
    https://stackoverflow.com/questions/12600330/pop-back-return-value
    http://www.gotw.ca/gotw/008.htm
    https://stackoverflow.com/questions/596162/can-you-remove-elements-from-a-stdlist-while-iterating-through-it
    https://stackoverflow.com/questions/799314/difference-between-erase-and-remove
    move也会抛出异常，所以不是所有的类型都是movable
    1234b2有其他算法需要了解下