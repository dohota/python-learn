# 项目
#1.manage是一个实体管理系统
#2.life是一个人生模拟器（复杂功能没实现）
#3.uach 是一个qt designer编译的页面文件
#4.chess是一个逻辑文件，用来调用两个游戏
#5.chess—play是五子棋游戏
五子棋的问题：1.有的时候五个棋子相连却不能判断出来
2.黑棋/白棋胜利的字体不能显示出来

#6.plane-flight是飞机大战游戏
飞机大战的问题：1.两个飞机碰撞时没有爆炸效果（其实这个爆炸效果也不重要）
2.显示game over的时候字跳的太快了
显示字的时候会被别的东西遮盖住（可以结合pyqt进行改进）

#7.总结：以上四个文件用pyqt调用了pygame的代码
不过有部分问题，未来说不定能通过多线程解决
1.一次只能打开一个游戏窗口.退出游戏即退出程序
2.飞机大战重新开始游戏会出现错误
3.如果多次按按钮，则会重新开始游戏

学习pygame和pyqt的目的不在于做出多么厉害的东西，而是在于学会基础操作
为未来打下基础。真正做游戏可以用unity（要学c#）
博客园--我的博客：https://www.cnblogs.com/karl-lighting/
普通游戏一般用单线程，性能不够了可能会用多线程

#8.tank-fight是坦克大战游戏
实现了各种的方块，实现了和敌方坦克战斗，音效和碰撞的逻辑
这个游戏没啥问题，但还需要优化一下：
1.增强代码的可拓展性，增加更多的音效和地图类型
2.完善敌方坦克的Ai
3.实现socket联机，开房间

#9 tank和battle是坦克大战10.0版本的两个文件
10.0版本初步实现了游戏界面
###3D游戏不一定需要unity，可以用js和后端来搞，同时需要blender3D建模

#10 怪物大战2.0：基本实现了坦克大战向怪物大战的过渡，同时增加了挡位机制（比较复杂）
其中有个inte.py是我弄的一个未完成的游戏解释器
#11.怪物大战2.5：不再设置挡位。怪物，子弹，地图有共同的父类。通过元类生成方块
接下来怪物大战会有很多种类的怪物，武器，道具，属性

##之后可能不怎么想学python了（怪物大战停止更新），更想去学c++，Java以及一些框架（python速度比较慢）
以后会和学长做项目，我自己也会做一个前端的项目（小游戏/网站用前端也差不多够了，TS也可以用于处理逻辑）
electron可以把浏览器代码变为客户端代码
#三个宝贝：vite，springboot，UE

##12.tkk.py是tkinter结合数据库的一个小项目
##vue3+webassembly(用c++编译而成)+springboot

##13.Magic game1.0一个不完善有bug的c++初级坦克大战，接下来的版本会让它更加完善

##14.用pygame做了一个简易的音乐播放器

#15.音乐播放1.0可以按空格键切换另一首歌，但别的功能还都没有

#16.音乐播放器正式版：功能都实现了，就是UI不太好。
接下来我会完善UI按钮，文本输入框，事件监听器，不同页面的跳转逻辑。
实现输入文件夹，查找相应歌曲，加入播放列表/把随机歌曲加入播放列表，然后开始播放
甚至之后通过MicrosoftSAPI通过歌曲的播放自动生成歌词
