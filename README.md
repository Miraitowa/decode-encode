今年暑假做的一个作品，感觉自己还是一个渣渣(QAQ),毕竟我是那么的弱呀

主要的功能进行演示一下：

1）Unicode编码：其中有两种编码方式，我们以最简单的为例：Unicode与中文之间的转化。
 
![](https://i.imgur.com/NfKm766.png)

图 1　　作品测试图１
经过Unicode编码就会得到：
 
![](https://i.imgur.com/bo58rwu.png)

图 2　　作品测试图２
2）Unicode编码到ASCII之间的转换：

![](https://i.imgur.com/iB9ljlJ.png)

图 3　　作品测试图３
转换之后得到的结果：

![](https://i.imgur.com/QtXHvg8.png)
 
图 4　　作品测试图4
3)URL加解密，使用比较简单的进行演示：

![](https://i.imgur.com/SOJr7XL.png)
 
图 5　　作品测试图5
进行解密就会得到：

![](https://i.imgur.com/AeGyZgm.png)
 
图 6　　作品测试图6

4):base64加解密演示：
 
![](https://i.imgur.com/eb6CunY.png)

图 7　　作品测试图7
 
解密之后就会得到：
 
![](https://i.imgur.com/ylJ3V0R.png)

图 8　　作品测试图8

在这个加解密里面还有两个比较有特色的加解密的演示：
其中第一个HTML和js之间的加解密，进行演示：
 
![](https://i.imgur.com/d1nyZDs.png)

图 9　　作品测试图9
 
解密之后就会得到：
 
![](https://i.imgur.com/kM7IKRO.png)

图 10　　作品测试图10

### 2 XSS  ###

关于XSS的攻击原理以及防御方式不再过多的叙述，毕竟上文有内容：本作品主要是提供一些常见的XSS攻击AttackAPI LIB数据
 
![](https://i.imgur.com/CnKWvHt.png)

图 11　　作品测试图11

### 3 CSRF  ###

关于csrf（跨站请求伪造）攻击主要分为两种一个是以get方式，一种以post方式进行伪造：
 
![](https://i.imgur.com/YPqfAU9.png)

图12　　作品测试图12

#### 1)GET ####

![](https://i.imgur.com/OzaUqmL.png)
 
图 13　　作品测试图13

#### 2)POST方式： ####
 
![](https://i.imgur.com/dczlgoh.png)

图 14　　作品测试图14

此时就以一种最常见的攻击类型PHP类型为例：

![](https://i.imgur.com/DEsqxAk.png)
 
图 15　　作品测试图15

整体来说做的并不好，希望各位大佬能够修改一下，丰富里面的内容！