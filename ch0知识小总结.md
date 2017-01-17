#python学习笔记0111-0114

##Ch0

- 变量 

       就是指给name赋予input的变量，等号左边是变量名称，等号右边是变量实体

- 字符串
   转义字符\n表示换行，\'转义表本意。
- 占位符
  - %d 表示整数
  - %f 表示浮点数
  - %s 表示字符串，一般多用此来代替。
  - %x 十六进制整数



- 任务一：找到python2和python3的差别
  - print 函数不同
     从形式上看，3要带括号。
        print('a', 'b')
        print 'a', 'b'
    input:
    ('a', 'b')
    a b
    - python 2
          print "Hello World"

    - python 3

      ```
      print("Hello World")
      ```

- 整除
  
  - Python 2
        print '3 / 2 =', 3 / 2
        print '3 // 2 =',3 // 2
        print '3 / 2.0 =', 3 / 2.0
        print '3 // 2.0 =', 3 // 2.0
          run
         3 / 2 = 1
         3 // 2 = 1
         3 // 2.0 =1.5
         3 // 2.0 = 1.0 
  
  - Python 2
        print('3 / 2 =', 3 / 2)
        print('3 // 2 =', 3 // 2)
        print('3 / 2.0 =',3 // 2.0)
        print('3 // 2.0 =', 3 // 2.0)
         run
         3 / 2 = 1.5
         3 // 2 = 1
         3 // 2.0 =1.5
         3 // 2.0 = 1.0 
- 自己的在编码过程的小坑
  - my first name 这样表述错误
    应为 my_first_name
  
    
        
- 任务二：学会CIL语言
  - - [ ] 什么是CIL？（至今还未学会）

      

    

- 任务三：安装gitbook ，生成个人学习输出
  1. 在网站和自己github关联
  2. 下载Node
  3. 在终端输入一下指令建立gitbook
      npm install gitbook-cli -g
      #通过npm安装gitbook

      $ gitbook -V
      #查看gitbook是否安装成功。(可以显示版本号)
  - [ ] 如何将markdown 文件传送到gitbook上还需要学习
