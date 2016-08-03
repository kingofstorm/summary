   /********************************************************/
         
    学习计划
      周一到周五
        9.00-6.00上班时间
        
      每天晚7.30到10.30  三个小时
      周六早晨 9.00-11.00
          晚上 7-11点
          
      周末早晨 9.00-11.00
   
      实习5月23到8月23
      
      
      知识点总结：
      
      要看的书   
               UNIX环境高级编程
               深入理解计算机系统
               Linux 程序设计
               设计模式
                  单例模式
                  桥接模式
                  工厂模式
                  观察者模式
                  
      Linux开发环境
            GDB调试技巧
            VIM的使用
            TCPDUMP软件
            管道
            重定向
            
            常用命令
            grep
            ls
            find
            ps
            top
            
              
      数据结构  数组  
                链表
               二叉树
               各种叔
               图
     算法
               几何相关算法
               常见经典算法
                  开根号
                   大数相乘
                   大数想加
               整数相关
                  查找
                  排序
                   去重
                   二维矩阵
                
            字符串相关
                回文串
                字符串匹配
                查找字串
            动态规划
                01背包
                LCS
                LIS
                完全背包
            贪婪算法
            分治算法
            递归算法
            回溯算法
            双指针
       排序算法
            快排
            归并
            堆排序
            基数排序
            选择排序
            冒泡排序
            插入排序
             
              
   
   
   
      编程语言C/C++
       数据库 MySQL
      操作系统  进程线程  虚拟内存 进程调度  磁盘调度 文件
      计算机网络  常用网络命令  抓包软件   
                                          应用层   http https  smtp  ftp  
                                          传输层   TCP/UDP
                                          网络层   IP
                                        
    脚本语言
         Python
   
   
    服务器后台开发
         LAMP环境搭建
         Apache
         Nginx
   Socket网络编程
      
   
   
   
   
   
   
   
   
   
    /*面试总结*/
    网易游戏
    百度地图内推
    腾讯面试
    360面试
    中国银联面试
    微软面试
    华泰证券面试
    华为面试
    
    /*未过的笔试*/
    网易互联网
    完美世界
    京东
    阿里巴巴
    百度
    
    
    
   
    /*远景能源*/
      类的构造 析构 内存new delete malloc free
      构造函数 析构函数 怎么调用
      智能指针 循环引用
      虚函数内存布局
     
    内存泄露的检测
    
    
    
    
    Linux常用命令总结
    
    [kingofstorm@iZ28j5jp3riZ muduo]$ cat /etc/redhat-release

    
       # # -*- coding:utf8 -*-
         import calendar
         import multiprocessing
         import threading
         import time
         import datetime

      def work(interval):
          print ("start time is{0}".format(time.ctime()));
         time.sleep(interval)
         print ("end time is {0}".format(time.ctime()));

      if __name__=="__main__":
          t=multiprocessing.Process(target=work,args=(3,))
          t.daemon=True
          t.start()
          t.join()
          print "end"

   #include<iostream>
   #include<vector>
   #include<string>
   #include<unordered_map>
   #include<sstream>
   #include<algorithm>
   using namespace std;
   int main()
   {
	   int N,tmp;
	   cin >> N;
	   vector<int> num(N);
	   for (int i = 0; i < N; i++)
	   {
		   cin >> num[i];
	   }
	   system("pause");
	   return 0;
   }

