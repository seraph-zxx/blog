###js小知识点之indexOf和filter
#####indexOf
indexOf() 方法可返回某个指定的字符串值在字符串中首次出现的位置。一般有两种情况：  

1.  返回 -1 表示未匹配到
2.  返回 其他整数表示匹配字符串下标起始位置  

example：  
[html] view plaincopyprint?
```javascript
var result = 0,
    str = "zxxwslq"
    str1 = "zxx",
    str2 = "wtf";    
result = str.indexOf(str1);
console.log(result);  //0
result = str.indexOf(str2);
console.log(result);  //-1
```
