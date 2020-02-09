# MixFile_iOS
# 此工具适用于Object-C开发的iOS的项目,功能简介:
```
1.文件及目录选择,目录支持递归,文件会过滤掉.h、.m文件以外的文件
2.Import打乱 
3.@property属性打乱
4.OC方法声明及方法实现打乱
5.注释代码删除
6.Compile Sources打乱,需要选中打乱的'.xcodeproj'文件
7.文件名修改,同时会修改项目目录下的import引用名称
8.修改类名
```
## 说明
```
1.代码打乱时,如果没有设置删除注释,则注释会和声明的属性或者方法绑定在一起
2.修改文件名,如果修改了ViewController,并且在storyboard中有使用,需要手动去storyboard中修改
3.有使用不当的地方,敬请提出!!!
```

## 界面
![MixFile_UI.jpg](https://github.com/GeLeis/MixFile_iOS/blob/master/mix_file.jpg)

### Author:869313996@qq.com
