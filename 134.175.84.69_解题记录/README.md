http://134.175.84.69/ 解题记录

## 第一关、来啦老弟

答案：admin888

![Burp响应包](1.png)

## 第二关：芝麻开门

密码：wazhp

```javascript
function testKey(){

var a=document.getElementById("password");

if(a.value == "wazhp"){

t="71,111,71,111,71,111,58,92,99,97,114,99,97,114"

t=eval("String.fromCharCode("+t+")");

alert(t);

}

else{

alert("输入的内容不对！请重新输入");

}

}
```

![下一关的提示](2.png)


## 第三关：carcar

<http://134.175.84.69/carcar>


密码：/wohahahaha

![](3.png)


## 第四关：我想进群

<http://134.175.84.69/wohahahaha>


密码：/olddrive


第四关这题感觉出的不是很好，UA写法固定必须是 IE/6.5 ，而zh-hk必须放在Accept-Language的开头

![](4.png)


## 第五关：老司机

密码：youwin

![](5.png)

a74e85d6c1d4faef74abfede3bae2030
![](6.png)


## 第六关：你赢了！

![](7.png)

> wechat:Freed0m1024
