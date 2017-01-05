###js小知识点之indexOf和filter
#####indexOf
indexOf() 方法可返回某个指定的字符串值在字符串中首次出现的位置。一般有两种情况：  

1.  返回 -1 表示未匹配到
2.  返回 其他整数表示匹配字符串下标起始位置  

example：  
    var result = 0,
        str1 = "zxx",
        str2 = "zxxwslq";    
    result = str2.indexOf(str1);
    console.log(reuslt);  //0
`printf()`
