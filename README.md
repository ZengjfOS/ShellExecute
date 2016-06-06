# ShellExecute
这个简单的库用于在Android层执行Linux shell命令，并以字符串的形式返回输出结果，初衷是获取dmesg信息。

## 函数接口

* 函数用于执行Linux shell命令 

```Java
    public static String execute ( String command, String directory )  
            throws IOException {  
        ......
    }  
```

* 函数用于执行Linux shell命令，执行目录被指定为:"/"
```Java
    public static String execute (String command) throws IOException {  
        ......
    }  
```
    
* 函数用于判断dmesg中是否存在pattern字符串，执行目录被指定为:"/"
```Java
    public static boolean devExist(String pattern) throws IOException{
        ......
    }
```

## Author

[曾剑锋](http://www.cnblogs.com/zengjfgit/)