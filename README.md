![image](https://github.com/Vetoyi/CN_Patch.Being_A_DIK/blob/main/%E5%B0%81%E9%9D%A2.png)

***

# :o:前言
**<details><summary>:lock:原专栏前言(2022.04.20 - 2022.07.04)</summary>**
> 为什么要把补丁放到B站呢？原因倒是简单，因为我在游戏的评测和指南先后都被社区版务封了，除了无语我也不知道说什么，可能他们不喜欢看到有人修改游戏文件还是什么的吧。恰好我最近又改了下补丁，还是本着希望更多人能在正版上用到汉化而不必憋屈的入正玩盗版，故在此分享我东偷西缝的这份补丁，而我也希望能在一个平台上至少把补丁发出来而不是只能憋在手里，至于大家能不能看到这篇专栏也看缘分了。然后本补丁是免费下载，本身大部分汉化成果也不来自于我，不必感谢我，希望各位能玩的开心吧，尽量别给我私信，有问题可以评论反馈，但不要无脑评论就是，我主要还是摆烂，如果你不满意现有汉化，那我只能说我基本是长期不会更新的。
<br><br>另外还是说一下，该补丁旨在针对Steam版本进行汉化，以达到我视频或专栏中所提及的效果。这也意味着如果你不想在Steam版上使用本补丁，而是将其用在其他地方，请别来问我补丁为什么会不适配、有bug等问题，我也不会回复解决，这本身就是Steam专用补丁，如果你执意如此请自己想办法解决。而对于Steam版的问题，各位在反馈时最好能指出是EP几，能具体到是否自由模式、报错页&报错前后的台词就更好了，这对我纠错补丁会有很大帮助。
<br><br>然后，各位请别再问我攻略、存档、盗版等各方面无关内容了，我就单纯分享汉化，记录补丁反馈问题，那些问题你问我我也没法解决，希望各位理解，我不是万能哆啦A梦什么都有的。</details>

**<details><summary>:lock:原指南前言(2022.03.25 - 2022.03.25)</summary>**
> 在我发布Ver0.07的补丁更新后，我的评测就被和谐了，所以我索性摆了，今天碰巧想起就干脆再发布篇指南看看吧，一切只是为方便更多和我一样的玩家，具体详见指南。</details>

**<details><summary>:lock:原评测前言(2022.02.01 - 2022.02.18)</summary>**
> 各位新年好，本来这篇评测2022.01.21左右就该发了，但我一摸再摸，最近感觉似乎摸鱼已经没有尽头，遂还是赶紧发出来。说起来本以为新年回来就会直接快乐大表哥一整月，没想到反而是刚回来隔天就买了首发特惠的Season2，也没想过自己会出于想玩的缘故于是来折腾这游戏的汉化，一下居然就摸到了新年，确实该歇歇了！</details>

**<details><summary>:lock:历史游玩评测(2020.11.26 - 2022.02.18，初次游玩于2020.08)</summary>**
> 总实际游玩时长约40h，超棒
<br><br>欧美黄油天花板，视觉小说内含大量高质量图绘&动态CG，场景&人物可互动性很高，剧情超棒代入感十足，能够调动玩家情绪且对故事后续充满好奇，充足对话选项引发多剧情分支，真·因黄油而来却好似在谈恋爱，快进快退功能也使得全画廊收集&另类剧情体验更加方便，BGM优美无人物配音但丝毫不影响代入感与游戏体验。</details>

***

# :o:补丁介绍
本补丁汉化范围为[Season1本体(EP1-4)](https://store.steampowered.com/app/1126320) + [Season2DLC(EP5-8)](https://store.steampowered.com/app/1215820)总8章：<br>EP1-6汉化文件取自火鸟字幕组0.6.1版，所有文件代码已逐一校对至0.8.2版并顺便改一些我碰巧看见的错误；<br>EP7-8部分机翻汉化文件取自ACG0.8.1，其余由我自行翻译(主要为新手机、各种自由模式小游戏等)。
<br><br><br>
**:white_check_mark:解锁Steam成就**
- 理论全可解，但没打全成就故不确定，如有发现解不了的请留言告知我。

**:white_check_mark:存档兼容(原版&汉化版)**
- 存档节点或不一致，进度会倒退一些或保持原样，少数情况下可能报错(不确定)，盗版不通用。

**:white_check_mark:官方指南DLC可用**
- 经验证，本补丁与[Season1指南DLC](https://store.steampowered.com/app/1223490)、[Season2指南DLC](https://store.steampowered.com/app/1631620)均适配且无bug，但指南DLC本身存在一些游玩相关问题，如果你购买并安装指南DLC后在游玩时遇到问题，请认真看[目录“补丁快速Q&A”](https://github.com/Vetoyi/CN_Patch.Being_A_DIK#o补丁快速qa)，里面有一些指南相关问题的解决方案。

**:white_check_mark:目前已知bug(如有额外发现请反馈)**
- 暂无

***

# :o:汉化剩余进度简述
1. EP7-8叫鸡App帖子内容我翻译至EP8开头(摸了)，勉强能看。
2. EP7-8短信回复全部翻译完毕(一半机翻，一半我自己翻)。
3. EP7-8新手机功能除以下几项外全部翻译完毕：
   - EP7-8人物行为记录(机翻用的不是游戏主剧情原文件，弄的话代码修改量又太大了故摆烂)；
   - 统计App中的当前性格显示(已放弃，见[目录“目前无法汉化内容”](https://github.com/Vetoyi/CN_Patch.Being_A_DIK#o目前无法汉化内容)；
   - 2D艺术商店各角色的人名(不能翻，见[目录“目前无法汉化内容”](https://github.com/Vetoyi/CN_Patch.Being_A_DIK#o目前无法汉化内容))。
4. EP7-8机翻文件涵盖对象：
   - **主剧情对话、自由模式对话、性别研究课、与玫瑰夫人对话、部分短信回复**；
   - 以上文件均取自ACG18机翻汉化，漏翻、人名不一致等问题很多，我只能说能玩但别期待是什么精翻，不存在的，而且未来我也不会尝试自翻主剧情，只能等更高质量文本出现再说，其余的那些以后可能会慢慢更新解决，主要我现在不太想再整了。
5. 图片汉化方面EP1-6沿用火鸟素材，少数由我补翻；EP7-8由我翻译完毕，仅剩余以下内容：
   - 收集奖励中图片鉴赏相关功能按钮(脱衣服等)；
   - 我认为没必要：ep8提伯尔特报纸(太多)、ep8主角吉他弹奏纪念图、结局Season3预告图、结局作者推特指路图。
<br>
如有发现除我提及以外我缺漏的，请留言告知我。

***

# :o:目前无法汉化内容
**<details><summary>:one:(不能翻)EP6开始的雅各布2D艺术商店，各角色2D艺术解锁界面的人名</summary>**
- 此处同时涉及人名显示&2D艺术商店的人物封面图调用，改完虽然能变中文，但图片会调用失败，导致2D艺术商店界面显示异常，而我也不想改图片的调用名，故作罢。</details>

**<details><summary>:two:(已放弃)EP7开始的新手机，统计App中的当前性格显示</summary>**
- 考虑到游戏后续Season更新，决定放弃此处的修改。
- 此处必须连同游戏所有源文件性格相关代码一起修改，否则游戏中的性格特定讲话风格、性格特定对话选项等会无法正常识别并作用，导致出现如：你是混蛋性格但讲话口气没有变化，你是怂逼但没法选怂逼特定对话选项。
- 而如果全改了，虽然当前性格能成功变成中文，游戏也没有任何问题，但可能会导致使用该汉化的最终存档在过渡至Season3以后，无法正常检测当前性格(已经被汉化成中文，而新游戏的性格相关检测代码均为英文)，而我自然没法保证还会去跟进游戏的汉化，故放弃此更改，避免后续出错。</details>

**<details><summary>:three:(特殊)EP8最后一个自由模式，篮球游戏的高分排行榜记录里的各人名</summary>**
   - 这个地方的汉化比较特殊，简单说就是：如果你此前从未玩过EP8，直到使用本汉化才初次接触该篮球游戏，就可以汉化成功；如果你此前已玩过EP8且当时没有使用本补丁或者说当时这个地方是英文的，那么即便安装本补丁重玩也没法汉化这个地方。排行榜的翻译在你初次玩到EP8这个篮球游戏时就定性了，需要有新纪录产生才会更新取代旧记录，但npc不会来玩小游戏，因此他们排行榜中的分数和人名是固定不变的，真正会玩这些小游戏的只有你，也因此只有你的分数人名会随新纪录而变化。</details>

***

# :o:(必读:bangbang:)使用前注意事项
<br>**:warning:注：不看或导致未来补丁更新时，再游玩旧档无法体验新汉化甚至报错:bangbang:**<br>
<br>
1. 如果你无法确认自己Steam上的Being A DIK游戏本地文件夹中是否有其它汉化残留文件，请删除Being A DIK文件夹中的所有文件，重新下载游戏并安装本补丁(能确认则直接安装补丁即可)，否则易导致汉化失败、游戏报错。

2. 切勿直接载入其它来源的旧档，否则易导致汉化不全、报错等问题，要载也只能是以本汉化(CN_Ver0.08及往后版本)进行游玩的存档，或者原版游玩的英语存档(但会导致汉化不全)，建议以新游戏开始游玩，享受较全面的汉化体验。

3. 如果你没有购买安装[Being A DIK - Season2 DLC](https://store.steampowered.com/app/1215820)，请在安装完汉化补丁后，根据[目录“(必读)如何使用补丁”](https://github.com/Vetoyi/CN_Patch.Being_A_DIK#warning重要bangbang如果你没有购买安装season2请在安装完汉化补丁后根据以下步骤删除部分补丁文件否则游戏将会存在报错或者你也可以直接购买being-a-dik---season2-dlc并在安装完dlc后再次解压汉化补丁游戏即可正常游玩)删除部分补丁文件，否则游戏将会存在报错；或者你也可以直接购买[Being A DIK - Season2 DLC](https://store.steampowered.com/app/1215820)，并在安装完DLC后再重新安装一次补丁，游戏即可正常游玩。

4. 经测试已知游戏部分内容无法在安装补丁后即时转换为新汉化内容(如: 短信、历史对话、叫鸡、滑滑、人物历史行为等)，需要回退进度或重开本章(上一章的结尾报告处开始玩)。本补丁EP1-6汉化已全部完毕(还得感谢火鸟)，只剩EP7-8还存在未来更新可能，而**如果你是使用本补丁(CN_Ver0.08及往后版本)进行汉化，并重开新档游玩的玩家，你可以保留一些EP6结尾报告画面处的备份存档(别进EP7)，因为补丁未来更新EP7-8内容时，部分汉化需要重开该章才能生效(判定为该章以前的存档)，故进行该存档备份很有必要，方便到时体验新版补丁，游玩成本上也只需重开EP7-8即可而不是整个游戏**；但如果没备份且仅剩EP7-8的存档，直接载入则无法体验部分新汉化内容，甚至出现报错；同时如果你不介意不完整的汉化也不想重新玩，那么也没关系，使用该补丁汉化的存档应该能正常过渡至Season3(其实暂不确定但理应没问题)，你可以在那继续你的故事。

***

# :o:补丁下载
**更新时间：2022.04.20
<br>补丁版本：0.08
<br>适配Steam版本：0.8.2
<br>解压码：BAD
<br>下载地址：[Github]()　[百度网盘(提取码：vas7)](https://pan.baidu.com/s/1TojgVaMS6r7hqA5k9tmVtQ)　[MediaFire](http://www.mediafire.com/file/ydcvly63ke40py8/%25282022.04.20%2529BAD.S1%25262_CN_Ver0.08%2528GameVer0.8.2%2529.rar/file)
<br>补丁安装：目录“(必读)如何使用补丁”
<br>汉化报错等问题：目录“补丁快速Q&A”**

***

# :o:(必读:bangbang:)如何使用补丁
**具体步骤：**

**<details><summary>1. 将下载好的补丁压缩包里的文件再次解压，并将其扩展名改为rar得到最终压缩包；</summary>**
> ![image](https://github.com/Vetoyi/CN_Patch.Being_A_DIK/blob/main/(%E5%BF%85%E8%AF%BB%E2%80%BC%EF%B8%8F)%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8%E8%A1%A5%E4%B8%81/1.jpg)
> ![image](https://github.com/Vetoyi/CN_Patch.Being_A_DIK/blob/main/(%E5%BF%85%E8%AF%BB%E2%80%BC%EF%B8%8F)%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8%E8%A1%A5%E4%B8%81/2.jpg)</details>

**<details><summary>2. 在steam库中找到该游戏→右键→属性→本地文件→浏览，弹出游戏文件夹(Being A DIK)；</summary>**
> ![image](https://github.com/Vetoyi/CN_Patch.Being_A_DIK/blob/main/(%E5%BF%85%E8%AF%BB%E2%80%BC%EF%B8%8F)%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8%E8%A1%A5%E4%B8%81/3.jpg)
> ![image](https://github.com/Vetoyi/CN_Patch.Being_A_DIK/blob/main/(%E5%BF%85%E8%AF%BB%E2%80%BC%EF%B8%8F)%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8%E8%A1%A5%E4%B8%81/4.jpg)</details>

**<details><summary>3. 将最终压缩包中的2个文件夹(game，renpy)，解压至**第2步**弹出的游戏文件夹(Being A DIK)，在跳出提示框后选择替换所有文件；</summary>**
> ![image](https://github.com/Vetoyi/CN_Patch.Being_A_DIK/blob/main/(%E5%BF%85%E8%AF%BB%E2%80%BC%EF%B8%8F)%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8%E8%A1%A5%E4%B8%81/5.jpg)
</details>

**<details><summary>4. 进入游戏(如上述步骤操作均正确，则进游戏已汉化成功)，在`“游戏设置”`中找到`“语言选项”`，单点启用`“简体中文”(启用=橙色，禁用=灰色)`，会需要几秒响应时间；如安装补丁后初开游戏，该选项就已启用的话，请禁用该选项并再重新启用一遍，否则可能导致EP7-8未成功汉化；如决定不再使用本补丁或有意还原原版，请在卸载本补丁之前禁用该`“简体中文”`选项，以免游戏后续出错(虽说似乎并不会)。</summary>**
> ![image](https://github.com/Vetoyi/CN_Patch.Being_A_DIK/blob/main/(%E5%BF%85%E8%AF%BB%E2%80%BC%EF%B8%8F)%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8%E8%A1%A5%E4%B8%81/6.jpg)
> ![image](https://github.com/Vetoyi/CN_Patch.Being_A_DIK/blob/main/(%E5%BF%85%E8%AF%BB%E2%80%BC%EF%B8%8F)%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8%E8%A1%A5%E4%B8%81/7.jpg)</details>

## :warning:【重要:bangbang:】如果你没有购买安装Season2，请在安装完汉化补丁后，根据以下步骤删除部分补丁文件，否则游戏将会存在报错；或者你也可以直接购买[Being A DIK - Season2 DLC](https://store.steampowered.com/app/1215820)，并在安装完DLC后再次解压汉化补丁，游戏即可正常游玩。

1. 根据**具体步骤**中的**第2步**进入弹出的游戏文件夹Being A DIK，双击进入里面的game文件夹；

**<details><summary>2. 删除game文件夹下名为season2的文件夹；</summary>**
> ![image](https://github.com/Vetoyi/CN_Patch.Being_A_DIK/blob/main/(%E5%BF%85%E8%AF%BB%E2%80%BC%EF%B8%8F)%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8%E8%A1%A5%E4%B8%81/8.jpg)</details>

**<details><summary>3. 进入game文件夹下名为images的文件夹，删除images文件夹下名为season2的文件夹；</summary>**
> ![image](https://github.com/Vetoyi/CN_Patch.Being_A_DIK/blob/main/(%E5%BF%85%E8%AF%BB%E2%80%BC%EF%B8%8F)%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8%E8%A1%A5%E4%B8%81/9.jpg)</details>

**<details><summary>4. 进入game文件夹下名为tl的文件夹，删除tl文件夹下除了common.rpyc之外的所有文件。</summary>**
> ![image](https://github.com/Vetoyi/CN_Patch.Being_A_DIK/blob/main/(%E5%BF%85%E8%AF%BB%E2%80%BC%EF%B8%8F)%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8%E8%A1%A5%E4%B8%81/10.jpg)</details>

***

# :o:补丁快速Q&A
**<details><summary>:red_circle:Q：为什么我解压完后进游戏却没汉化或只有部分汉化甚至报错、打不开游戏？</summary>**
> :green_circle:A：确认是否完成以下所有操作，如果全部都做到却还不行，再留言反馈：
> 1. 根据[目录“(必读)如何使用补丁”](https://github.com/Vetoyi/CN_Patch.Being_A_DIK#o必读bangbang如何使用补丁)正确解压最新汉化补丁，别把文件放错位置，否则你可能会报错连游戏都打不开；
> 
> 2. 如果你无法确认自己Steam上的Being A DIK游戏本地文件夹中是否有其它汉化残留文件，请删除Being A DIK文件夹中的所有文件，重新下载游戏并安装本补丁(能确认则直接安装补丁即可)；
>> ![image](https://github.com/Vetoyi/CN_Patch.Being_A_DIK/blob/main/%E8%A1%A5%E4%B8%81%E5%BF%AB%E9%80%9FQ%26A/01.jpg)
> 3. 以上两步骤均完成后，进游戏则应已有汉化，如为第一次使用本汉化补丁，切勿直接载入其它来源的旧档，否则易导致汉化不全、报错等问题，要载也只能是以本汉化(CN_Ver0.08及往后版本)进行游玩的存档，或者原版游玩的英语存档(但会导致汉化不全)，建议以新游戏开始游玩，享受较全面的汉化体验。</details>

**<details><summary>:red_circle:Q：为什么我购买并安装了指南DLC，进游戏后点开始游戏或载入存档，画面总是显示“感谢你购买……按下'g'以继续.”，但不管怎么按`“g”键`却都没有反应，画面一直不动，但是对话仍在进行？</summary>**
> :green_circle:A：目前测试结论为：与补丁无关，但是与系统输入法有关。请确保你有如下图所示英语键盘的切换选项(如果没有可以百度如何装)，切换并保持在英语键盘，再进游戏就可以正常按`“g”键`继续游戏；如果你不愿意装英语键盘，请试着把你的输入法状态调整为英语，再进游戏也许能正常按`“g”键`继续游戏，但如果不行请花时间研究一下英语键盘。
> <br><br>**:warning:注：本补丁并没有涉及官方指南DLC的内容汉化，别问为什么是英文。**
>> ![image](https://github.com/Vetoyi/CN_Patch.Being_A_DIK/blob/main/%E8%A1%A5%E4%B8%81%E5%BF%AB%E9%80%9FQ%26A/02.jpg)
>> ![image](https://github.com/Vetoyi/CN_Patch.Being_A_DIK/blob/main/%E8%A1%A5%E4%B8%81%E5%BF%AB%E9%80%9FQ%26A/03.jpg)</details>

**<details><summary>:red_circle:Q：为什么我购买并安装了指南DLC，进游戏后开始游戏或载入存档，画面总是显示“感谢你购买……按下'g'以继续.”，但按`“g”键`却跳出一个灰白色的功能调整页面？</summary>**
> :green_circle:A：确保你没有开启大写锁定及中文输入法，要是开了大写锁定再按`“g”键`就会进功能页(`“Shift+g”键`也会)，这里通常是用来调整画面渲染方式的，如果你的游戏画面时常卡顿滞留，就可以在这里进行调试；但如果你并不需要而只是误进，那么每次一进到该页面就请直接点击下方的`“返回游戏/Return”`退出该页面。
> 通常只需要关闭大写锁定就能避免该问题，但如果还是不行，请试着重复按几遍`“Shift”键`或`“Shift+Tab”键`，或者按一遍`“Shift+g”`键也可以，在这之后再按`“g”键`应该就正常了。
> <br><br>**:warning:注：本补丁并没有涉及官方指南DLC的内容汉化，别问为什么是英文。**
>> ![image](https://github.com/Vetoyi/CN_Patch.Being_A_DIK/blob/main/%E8%A1%A5%E4%B8%81%E5%BF%AB%E9%80%9FQ%26A/04.jpg)</details>

**<details><summary>:red_circle:Q：为什么我在游戏里按任何按键都没有反应？</summary>**
> :green_circle:A：你可能开启了中文输入法，请将其关闭并切换保持在英语键盘。</details>

**<details><summary>:red_circle:Q：为什么我汉化好了，但一到EP5就全程黑屏，左上角出现红色代码报错？</summary>**
> :green_circle:A：因为本体只包含了EP1-4，而EP5-8则在Season2中，如果你只购买了本体而没有购买Season2，游戏就会出错，因为找不到DLC文件。只需购买[Being A DIK - Season2 DLC](https://store.steampowered.com/app/1215820)并在安装完DLC后再次解压汉化补丁，就能解决该报错继续游玩Season2；如果你不想购买该DLC，请根据[目录“(必读)如何使用补丁”](https://github.com/Vetoyi/CN_Patch.Being_A_DIK#warning重要bangbang如果你没有购买安装season2请在安装完汉化补丁后根据以下步骤删除部分补丁文件否则游戏将会存在报错或者你也可以直接购买being-a-dik---season2-dlc并在安装完dlc后再次解压汉化补丁游戏即可正常游玩)删除对应补丁文件，放弃游玩Season2。</details>

**<details><summary>:red_circle:Q：为什么我的EP1-6都有汉化，但EP7-8却是英文？</summary>**
> :green_circle:A：进入游戏，在`“游戏设置”`中找到`“语言选项”`，单点启用`“简体中文”(启用=橙色，禁用=灰色)`，会需要几秒响应时间；如安装补丁后初开游戏，该选项就已启用的话，请禁用该选项并再重新启用一遍，否则可能导致EP7-8未成功汉化；如决定不再使用本补丁或有意还原原版，请在卸载本补丁之前禁用该`“简体中文”`选项，以免游戏后续出错(虽说似乎并不会)。
>> ![image](https://github.com/Vetoyi/CN_Patch.Being_A_DIK/blob/main/%E8%A1%A5%E4%B8%81%E5%BF%AB%E9%80%9FQ%26A/05.jpg)
>> ![image](https://github.com/Vetoyi/CN_Patch.Being_A_DIK/blob/main/%E8%A1%A5%E4%B8%81%E5%BF%AB%E9%80%9FQ%26A/06.jpg)</details>

**<details><summary>:red_circle:Q：下载好补丁压缩包后，里面那个文件要怎么打开？</summary>**
> :green_circle:A：百度“如何更改文件扩展名”，学会之后将下载好的补丁压缩包里的文件的扩展名改为rar，并对其再次解压得到最终压缩包；如果你连压缩包都打不开，请百度并下载个压缩包软件。</details>

**<details><summary>:red_circle:Q：为什么下载完的汉化包提示文件损坏、缺失？</summary>**
> :green_circle:A：说明你下载的过程或者电脑环境有问题，可能是杀毒软件等因素，需要你自行研究，我也无能为力。</details>

**<details><summary>:red_circle:Q：有没有盗版下载地址、完美存档、攻略、汉化指南？</summary>**
> :green_circle:A：没有别问，我只分享汉化补丁。</details>

**<details><summary>:red_circle:Q：能推荐点其它类似的游戏吗？</summary>**
> :green_circle:A：这个还是交给评论区的各位推荐吧，大家的黄油阅历肯定比我要丰富。</details>

**<details><summary>:red_circle:Q：补丁为什么很久都不更新？</summary>**
> :green_circle:A：摸鱼善哉，请勿催更，我不会保证有什么更新速度或者后续更新，甚至可能以后游戏出新版本导致补丁无法适配了我都不会更新，但既然现在能玩就抓紧好好享乐吧！</details>

***

# :o:补丁更新记录
**<details><summary>:beginner:【2022.04.20】CN_Ver0.08(GameVer0.8.2)</summary>**
- 已修复bug：EP7赛琪拳击游戏无法触发正确动画过程
- 已修复bug：EP8宿舍派对自由模式无法结束
- 已修复bug：EP8期中考试复习报错
- 解决部分汉化问题</details>

**<details><summary>:beginner:【2022.02.18】CN_Ver0.07(GameVer0.8.2)</summary>**
- 已修复bug：EP1初进玛雅宿舍后无法上床睡觉</details>

**<details><summary>:beginner:【2022.02.11】CN_Ver0.06(GameVer0.8.2)</summary>**
- 添加简体中文设置选项，解决部分人群汉化不全问题
- 补翻3处漏翻的任务指示</details>

**<details><summary>:beginner:【2022.02.01】CN_Ver0.05(GameVer0.8.2)</summary>**
- 首次发布补丁</details>

***
