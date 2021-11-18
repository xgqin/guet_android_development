# 桂林电子科技大学[Android应用开发]课程资料库

资料库作为Android应用开发课程教学资料的汇集，将持续进行更新.
当前目录结构:
```
.
|____README.md
|____book (实验指导书)
| |____Andorid应用开发[20190925].pdf
|____ppt (课程知识点ppt)
| |____2017
|   |____ch01.pdf
|   |____ch02.pdf
|   |____ch03.pdf
|   |____ch07.pdf
|   |____ch06.pdf
|   |____ch04.pdf
|   |____ch05.pdf
|____final_projects (综合设计要求及评分标准)
| |____Android应用开发综合设计验收评分细则.docx
| |____Android应用开发综合设计.docx
|____report_template (实验报告模板)
  |____《Android应用开发》实验报告——参考模板.docx
```

##迁移至AndroidX

实验指导书中使用Android Support库，如果你使用最新版Android Studio则需要将部分工件或包名进行替换，其方法在[迁移至AndroidX](https://developer.android.google.cn/jetpack/androidx/migrate)进行了详细的介绍。

例如：
在实验指导书中**第七个Android项目**中使用了Android Support库中的卡片控件 `android.support.v7.widget.CardView`，如果在AndroidX库下卡片控件对应的包名为`androidx.cardview.widget.CardView`，此外你还需要移除在build.gradle(:app)文件中对应的`implementation 'com.android.support:cardview-v7:27.1.0'`依赖语句。


##其他课程资源:

1. 实验指导书在线版 [https://xxgqin.gitbook.io/android/](https://xxgqin.gitbook.io/android/)
2. Android官方开发者中心(国内镜像) [https://developer.android.google.cn](https://developer.android.google.cn)
3. Git教程 [https://www.liaoxuefeng.com/wiki/896043488029600](https://www.liaoxuefeng.com/wiki/896043488029600)
