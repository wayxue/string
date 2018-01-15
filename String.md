# StringBuilder & StringBuffer
- String ：              
    String a = "abc";                                           
    String b = "1";                                               
    String c = a + b; //三个对象                       
    String d = "abc" + "1"; //一个对象
- StringBuffer : 线程安全的；
- StringBuilder : 线程不安全的；
> 三者执行速度：String < StringBuffer < StringBuilder