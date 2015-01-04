普通软件推荐：[OS X 平台上有哪些值得推荐的常用软件？ - 知乎](http://www.zhihu.com/question/19550256)
优质软件推荐：[我用Mac的这一年](http://www.jianshu.com/p/cfc0d49f2e8f)
下面补充些上面没提到的软件。

## [Mac App Store - Degrees](https://itunes.apple.com/us/app/degrees/id430173763)
在菜单栏显示当前气温。
## [TotalFinder brings colored labels back to your Finder and more!](http://totalfinder.binaryage.com/)
finder增强。
## [Mac App Store - Snap](https://itunes.apple.com/eN/app/snap/id418073146)
设置程序快捷键，方便切换。
## [Timing - Automatic time tracking for your Mac - Home](http://timingapp.com/)
记录每天在每个程序（文件、网站）上花了多少时间。
## [Anxiety - Lightweight To-do Management](http://www.anxietyapp.com/)
基于Reminders的极简todo list应用。
## [Mac App Store - FoldingText](https://itunes.apple.com/us/app/foldingtext/id540003654)
基于markdown的时间管理，教程:[Customizing FoldingText - Tuts+ Computer Skills Tutorial](http://computers.tutsplus.com/tutorials/customizing-foldingtext--cms-21674)
## [Literature and Latte - Scapple for Mac OS X and Windows](https://www.literatureandlatte.com/scapple.php)
不会自动调整位置的思维导图。
## [Simplenote](http://simplenote.com/)
足够简单的笔记软件。
## [Karabiner](https://pqrs.org/osx/karabiner/)
更改键位。由于官方教程很不友好，这里简单讲解下，改键的方法是打开[一个xml格式的文件](https://pqrs.org/osx/karabiner/document.html.en#privatexml)，然后根据[这里介绍的格式进行更改](https://pqrs.org/osx/karabiner/xml.html.en)，里面真正的关键其实就两个，举例来说
`<autogen>__KeyToKey__ KeyCode::Q, KeyCode::Y</autogen>`
表示把q键改为y键；
`<autogen>__KeyToKey__ KeyCode::W,ModifierFlag:: CONTROL_R, KeyCode::CURSOR_UP</autogen>`
把（右） ctrl＋w改为上键；
`<autogen>__KeyToKey__ KeyCode::Q, ModifierFlag::CONTROL_R, KeyCode::CURSOR_LEFT, ModifierFlag::COMMAND_L</autogen>`
把（右） ctrl＋q改为cmd＋左键；
`<autogen>__KeyOverlaidModifier__ KeyCode:: SPACE, KeyCode:: COMMAND_L, KeyCode:: ESCAPE </autogen>`
把空格键改为一直按着时是cmd键，按一次时是esc键；
以上就是我用到的所有配置“格式”。
