# 0️⃣ xml配置文件 🤓

⚙ESLyric自定义界面接口解释参考⚙

🔗https://github.com/ESLyric/release/wiki/%E9%9D%A2%E6%9D%BF%E5%B8%83%E5%B1%80


        <panel layout="stack" name="自定义布局" orientation="horizonal">
          <element type="text" caption=""anchor="left" height="100%" width="3%"/>
            <element type="container" width="40%" anchor="vstretch" options="8" >
              <element type="albumart" width="78%" height="55%" anchor="left" follow-background="1" options="4"/>
              <element type="text" caption="" anchor="left" height="6%" width="78%"/>
              <element type="text" caption="%title%" font-size="30" text-color="rgba(255,255,255,1)" text-align="left"anchor="left" height="5%" width="78%" nowrap="1"/>
              <element type="text" caption="[%artist%]" font-size="25" text-color="rgba(255,255,255,0.5)" text-align="left" anchor="left" height="4%" width="78%" options="4"/>
            </element>
          <element type="text" caption=""anchor="left" height="100%" width="0%"/>
          <element type="container" anchor="vstretch"  width="49%" options="4" >
            <element type="lyric" text-align="left" anchor="stretch"/>
          </element>
        </panel>


可以复制进`.txt`，然后后缀改为`.xml`

# 1️⃣ 下载 🧐

要用新版的ESLyric💖  

作者GitHub项目，可以收藏看看有没有更新：

🔗https://github.com/ESLyric/release/releases

![image](https://github.com/user-attachments/assets/83cc4dbd-87b8-4d91-b190-6e5d278cf1a1)

![image](https://github.com/user-attachments/assets/9bf47e9a-3fbc-4e38-9393-b9fc62f86027)


上面下不了的可以在这下

ESLyric插件🔩和布局文件📁：

🔗https://wwpt.lanzoul.com/b02ihth1de

🔑密码:7cx5
    
------------------------------------------------------------------------------------------

# 2️⃣ 安装 🥳

按照下图安装插件🔩重启软件🔄

![image](https://github.com/user-attachments/assets/0b41147a-ee0c-406f-b380-8d0dbd50ffdb)

安装完后没出现插件界面怎么办❓

找到视图开启`快速编辑模式`

![image](https://github.com/user-attachments/assets/bbd8b7ad-5ecd-4860-932e-9ad7085ddbd1)

右键替换选`ESLyric`

![image](https://github.com/user-attachments/assets/8fbecf24-14a2-4425-a4b8-f234597766f7)

有了就回去取消`快速编辑模式`

![image](https://github.com/user-attachments/assets/0a9083a2-a7f9-4d9e-b1f0-d264791d28c0)

------------------------------------------------------------------------------------------

# 3️⃣ 配置 😴


效果图

![image](https://github.com/user-attachments/assets/2dabbb1b-3842-4c0f-b46b-1716b95899b1)

彷的苹果界面📱，目前作者没有添加进度条还有播放按钮⏯，只能是这样

下面的可以按照个人喜好调，要是想实现上图效果可以跟着调👣

因为每个人的电脑屏幕大小不同🖥💻，数值也不同，可以自己把控，调的像一点就行。🔧

因为外面的界面和全屏的界面是独立的设置的所以先进`全屏模式`🔳

右键界面🖱

![image](https://github.com/user-attachments/assets/1dfecb88-ea89-4cbd-893b-867fde2baed0)

右键界面🖱

![image](https://github.com/user-attachments/assets/37808317-3ad7-47bd-afee-6d78ff4ba673)

![image](https://github.com/user-attachments/assets/f3a866a3-a022-4ec0-9c3c-01d7d6a0a2c7)

![image](https://github.com/user-attachments/assets/363827c5-974f-4c07-8f05-07f1a943ad6d)

![image](https://github.com/user-attachments/assets/00d4f32d-1e9d-4919-90ca-e15373076da6)

![image](https://github.com/user-attachments/assets/687fac90-d661-483e-b50e-95cb4720c170)

![image](https://github.com/user-attachments/assets/09693ac2-c83e-499f-a49f-729c3d9e5cd9)

`高亮歌词`太偏了，可以这里调

![image](https://github.com/user-attachments/assets/0fd13294-fa67-43b4-83dd-6e85af034ceb)

![image](https://github.com/user-attachments/assets/6b18e9d3-8962-4470-a886-90ed209c78f9)

可以试试`动态模糊`🔮

![image](https://github.com/user-attachments/assets/c72f7dcc-eb40-49d4-b8e6-3e26e4f8cfb5)


然后把布局文件拖到

    C:\Users\（每个人的用户名字不一样）\AppData\Roaming\foobar2000-v2\eslyric-data\layout

这个路径是安装版本的

![image](https://github.com/user-attachments/assets/0693183d-f641-4b24-ad25-f19ada4fbef2)

如果找不到，可以去安装文件夹找有没有 `profie` 这个文件夹📁，这个是便携版的，里面会有后面的

    eslyric-data\layout

![image](https://github.com/user-attachments/assets/d019c3c7-d820-4559-9fa6-1e856e879e42)

然后回全屏面板参数选`自定义布局`就行了

右键界面🖱

![image](https://github.com/user-attachments/assets/e64b63ea-c67d-403c-a633-97273f3b69d5)

右键界面🖱

![image](https://github.com/user-attachments/assets/9703c981-cb13-4e77-b693-9b6d7faf677c)


因为界面没有播放暂停⏯还有歌词全屏🔳的开关，所以我们添加播放▶暂停⏸，还有全屏模式🔳的`快捷键`

`快捷键`个人喜好调

![image](https://github.com/user-attachments/assets/087f2366-ac3d-4f4f-8717-3d2da4c9951a)

![image](https://github.com/user-attachments/assets/6d3b0392-1d3e-42d1-8041-db3b62d8f37b)

![image](https://github.com/user-attachments/assets/4afaab25-7a59-4d0c-85db-88acb186373f)


如果你们出现了左侧标题等行高字体显示一半，显示不全🚫

![image](https://github.com/user-attachments/assets/9fc7e46c-a947-402d-8a05-49bf4515944e)

可以试一试改一下行高`height=" "`，或者字号`font-size=" "`，高就改大一点，改一下就保存一下，会实时显示的❗

每个人的电脑屏幕还有字体设置大小不同就这样↕

用文本记事本打开刚刚放置的配置文件`.xml`，调整下图参数🔢

![image](https://github.com/user-attachments/assets/34da1afd-716d-4a30-8fc0-8c6fbd6df6ae)

------------------------------------------------------------------------------------------

# 4️⃣ 逐字歌词源 💬

下面是逐字歌词源

原地址：

🔗https://github.com/Robotxm/ESLyric-LyricsSource

![image](https://github.com/user-attachments/assets/712a7c06-ed8a-4ad1-9c87-731fa1b601d5)

上面下不了的可以在这下⬇

🔗https://wwpt.lanzoul.com/b02ihth1de https://wwpt.lanzoul.com/b02ihth1de

🔑密码:7cx5

下好解压📂

因为我们这个插件是新版，选`current`

![image](https://github.com/user-attachments/assets/2e7affcd-08ec-45d1-bf96-a6916f5547a6)

里面是`酷狗`，`网易云`，`QQ`逐字的源⛓

放这里

    C:\Users\（每个人的用户名字不一样）\AppData\Roaming\foobar2000-v2\eslyric-data\scripts

这个路径

如果找不到，可以去安装文件夹找有没有 `profie` 这个文件夹，里面会有后面的

    eslyric-data\scripts

![image](https://github.com/user-attachments/assets/7fd4ecc1-2047-4559-9222-7f11a8ddd409)



记得把`转换为标准格式`取消勾选🚫，没有就不用管

![image](https://github.com/user-attachments/assets/3136593d-4451-43a5-8234-14e456995adc)

还有把`EX`源勾上✅

![image](https://github.com/user-attachments/assets/6b1725d1-18df-461c-b783-f550c4229444)

只有`EX`源是逐字，酷狗有没有逐字看运气🗿

再打开`卡拉OK模式`下面的`增强歌词`

因为外面的界面和全屏的界面是独立的设置的所以两个都要选✅✅

![image](https://github.com/user-attachments/assets/1edfc16e-71fd-4143-a549-2407988dcfea)

![image](https://github.com/user-attachments/assets/d8cef639-a24e-43bf-be0f-311aa612e765)

当插件搜索到歌词后

可以把歌词保存到歌曲文件里面📎

右键歌词界面🖱

![image](https://github.com/user-attachments/assets/3d25fa3d-2d56-4fd8-9073-32a408058b59)


------------------------------------------------------------------------------------------

# 5️⃣ 歌词规则 🤩

歌词上面有原唱那些东西怎么去除❓🚮

就像下图一样
![image](https://github.com/user-attachments/assets/c54782e3-ebac-4c72-add9-046551cc2eba)

打开软件设置，选择通配符移除，里面的`*`代表若干字

如果你要去除像这样的  `演唱：林俊杰` ，然后有很多歌曲开头也有这个，你可以填  ` 演唱：*`🗿

![image](https://github.com/user-attachments/assets/7b8caf75-5654-44bf-a634-dce61aa19ba7)

------------------------------------------------------------------------------------------

# 6️⃣ 嵌入封面 😇

要给歌曲嵌入封面，要不黑压压的看的丑◼

![image](https://github.com/user-attachments/assets/df4ea3e5-778d-463f-90f1-b1ab8945601e)

[Windows] 音乐标签 v1.0.3.1—给本地音乐内置歌词和专辑封面！

🔗https://www.52pojie.cn/thread-1076546-1-1.html

![image](https://github.com/user-attachments/assets/4809c0ed-a5db-4279-bfad-9dfee15ea0b4)

------------------------------------------------------------------------------------------

# 7️⃣ 插件读取 🤨

这个插件搜索歌词是读取歌曲的`标签字段`📝

不是以文件名搜索的，不对的话可以右键最底下那栏点`属性`，把那两个改对

![image](https://github.com/user-attachments/assets/e41846ad-73cf-4b3e-8dce-bf540d77c688)

搜索歌词时歌手太多会影响结果，可以歌名不变，单独一个一个歌手加进去搜🔍

![image](https://github.com/user-attachments/assets/dcf5efad-429b-4f58-ba5b-7bf576de7997)

------------------------------------------------------------------------------------------

# 8️⃣ 无歌词设置 😎

如果歌曲没有歌词显示🚫

![image](https://github.com/user-attachments/assets/4363b780-39aa-4680-8982-a6d3233735d9)

可以这里自定义🔧

![image](https://github.com/user-attachments/assets/d274ad23-5715-44db-8f7b-bdd0d5cb0236)

------------------------------------------------------------------------------------------

# 9️⃣ 字体 🤠

这个是`ios`的字体🔟

🔗https://developer.apple.com/fonts/

这个是`spotify-mix`的字体（只支持英文🔡，想支持其他字体得靠软件将其他的字体库合成）

🔗https://en.bestfonts.pro/font/spotify-mix
