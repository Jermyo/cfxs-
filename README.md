# 出个小白教程吧，看大家很多都是新手，帮到你的话，推特点个关注吧，防止微信群丢失 https://twitter.com/JermySalvatore

## 一切风险自己分析哈，我也是整理的网上的信息。

### 1、首先介绍一下 $cfxs
cfx链铭文第一个币 $cfxs ，总量2100万张，gas低。没有预打，此铭文目的是对conflux espace做压力测试。
evm+utxo符文，无需索引，铭文进化版，可以称作符文，怎么叫是大家的共识，你也可以叫他符文！
这个摆脱了中心化索引器的必须性，利用了evm环境的特性。
无需索引器，utxo模型类似可拆分的erc1155 nft

### 交互方式1、交互方式2，都可以，看你适合哪个！！！！！！！！！

### 2、交互方式1
1、钱包添加chainlist.org/chain/1030网络（这里钱包尽量用小狐狸）（不会的具体看下面第6条）
2、给合约地址 0xc6e865c213c89ca42a622c5572d19f00d84d7a16 转0个cfx即可，相当于打一张铭文(一分钟可以打20张)
这个地址是项目合约地址：https://evm.confluxscan.net/address/0xc6e865c213c89ca42a622c5572d19f00d84d7a16?transactionType=executed
3、想要看自己链上是否成功，换成自己的地址看成功进度

### 3、交互方式2：如何通过在 Core 空间打 cfxs（链接里有详细教程，在线工具，批量工具，都有，就不罗列了）
https://forum.conflux.fun/t/core-cfxs/19700


### 4、添加$CFXS
直接在小狐狸里面
添加代币名称 CFXS
把合约地址写上 0xc6e865c213c89ca42a622c5572d19f00d84d7a16
代币名称CFXS长度写 0

### 5、批量工具（以下是 eSpace 的打法；core的打法看上面第3步骤！！！！！！）
工具来自网络，不保证安全，自我识别！！！！！！
使用工具一定要用新钱包！新钱包！新钱包！切记，批量工具都是扔私钥的，这个谁也不保准工具会不会泄露！交互完获得$cfxs到账后转出到安全钱包!

##### 工具一：node脚本
地址：https://github.com/sfter/evm-inscription-mint
打开github地址，按照readme里的步骤操作安装就行，人家已经说的很详细了，实在看不懂的就放弃吧。
<img width="929" alt="image" src="https://github.com/Jermyo/cfxs-/assets/23717512/b99d93a6-60bd-4507-a36a-1f874fb5b417">
![image](https://github.com/Jermyo/cfxs-/assets/23717512/042012e3-2d03-46f0-aa27-1acdf477cbda)

##### 工具二：OneKey钱包 (适合不会脚本的人)
下载OneKey钱包，官网：https://onekey.so/，这是在非小号上面看到的，这个钱包非常方便，可以建立几十个钱包，建立的时候不需要验证助记词，很方便，建立几十个钱包后，从其他地址让着几十个钱包里面打入CFX，然后利用钱包里面自带的工具，路劲，工具---批量发送器---多对一，好了到了这一步就不用我说了，把你建立的几十个钱包地址搞进去，数量选0，然后下面收件人，输入cfxs的合约 ：0xc6e865c213c89ca42a622c5572d19f00d84d7a16，然后点提交就可以。

##### 工具三：cointool.app (适合不会脚本的人，但是会扔私钥，注意安全)
使用工具一定要用新钱包！新钱包！新钱包！切记，批量工具都是扔私钥的，这个谁也不保准工具会不会泄露！交互完获得$cfxs到账后转出到安全钱包!
地址：https://cointool.app/batchCallAbi/cfx
延迟记得设置个 1 秒 （很重要）  其他配置看图  注意不要转给自己  
合约地址是：0xc6e865c213c89ca42a622c5572d19f00d84d7a16
gas自己把控，设置固定也行，就看快慢了。
<img width="946" alt="image" src="https://github.com/Jermyo/cfxs-/assets/23717512/4ed911f4-960b-416f-a4c9-bd9e63672565">
<img width="446" alt="image" src="https://github.com/Jermyo/cfxs-/assets/23717512/42587d4e-e3c4-4fec-8c39-6717d70b9257">


### 5、转$cfxs
我现在也提不了，有大神补充吗，大概是因为代币还未开放交易，无汇率，等官方社区。

### 6、交易所里提不了cfx
 https://twitter.com/cfx36u 会更新社区信息
现在都比较fomo，别着急，等等吧，2100w个呢，两天了才打了7%，着啥急，况且现在gas都很高。
有人说跨桥提取可以，现在是否还行，可以去试试。

以下为群友补充：
1、
<img width="416" alt="image" src="https://github.com/Jermyo/cfxs-/assets/23717512/8ef1f2ff-f89a-40e1-b0f7-0b9faef5dded">
2、
可以从币安买，提现bsc网，然后跨链到ConFlux
币安购买地址：https://www.binance.com/zh-CN/activity/referral-entry/CPA?ref=CPA_00J0WBX6YH
跨桥地址：https://portal.zglabs.org/

### 小白添加网络
1、PC端浏览器访问：chainlist.org/chain/1030 
   如果是手机端，打开小狐狸，在小狐狸的浏览器里访问这个地址，也会出现下图
2、出现如图，直接点添加就行了
<img width="1005" alt="image" src="https://github.com/Jermyo/cfxs-/assets/23717512/d73c8452-7a9d-40c8-aab6-a46f60963a09">

### 7、加群
防止微信群丢失，推特加个关注吧 
https://twitter.com/JermySalvatore

![image](https://github.com/Jermyo/cfxs-/assets/23717512/581766fc-47f3-4f46-80b1-1dc26605b397)

<img width="519" alt="image" src="https://github.com/Jermyo/cfxs-/assets/23717512/7028f662-504c-4582-aff3-fcf9767e3393">

