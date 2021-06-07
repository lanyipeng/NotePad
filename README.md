1.项目结构

![image](![img](https://raw.githubusercontent.com/lanyipeng/NotePad/master/%E6%88%AA%E5%9B%BE/image-20210607170336557.png)

布局和菜单文件

![image](![img](https://raw.githubusercontent.com/lanyipeng/NotePad/master/%E6%88%AA%E5%9B%BE/image-20210607170356386.png)

2.添加时间戳

2.1应该在NotePad主页面的每个笔记后面都添加时间显示，应该在`notelist_item.xml`布局文件中添加`TextView`

![image](![img](https://raw.githubusercontent.com/lanyipeng/NotePad/master/%E6%88%AA%E5%9B%BE/image-20210607170530223.png)

2.2NoteList类对应的`PROJECTION`中添加`COLUMN_NAME_MODIFICATION_DATE`

![image](![img](https://raw.githubusercontent.com/lanyipeng/NotePad/master/%E6%88%AA%E5%9B%BE/image-20210607170620616.png)

2.3修改适配器内容，在NoteList类增加dataColumns中装配到ListView的内容

![image](![img](https://raw.githubusercontent.com/lanyipeng/NotePad/master/%E6%88%AA%E5%9B%BE/image-20210607170650731.png)

2.4对时间进行格式化

![image](https://raw.githubusercontent.com/lanyipeng/NotePad/master/%E6%88%AA%E5%9B%BE/image-20210607170721237.png)

添加时间戳后运行效果

![image](![img](https://raw.githubusercontent.com/lanyipeng/NotePad/master/%E6%88%AA%E5%9B%BE/image-20210607170754859.png)

