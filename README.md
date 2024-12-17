# repkg_easy

基于RePKG.exe的一个简易图形化操作工具，免安装，以方便将 Wallpaper engine 中的壁纸提取为图片（支持提取jpg、png）。
RePKG.exe 项目：https://github.com/notscuffed/repkg
## 使用

下载release中的exe文件，或者下载源码，使用rust打包（需rust环境），然后直接双击运行exe文件出现图形化界面。

1. 壁纸大目录：
    Wallpaper engine 壁纸文件存放父目录。如：...../content/431960/2859325728 ，2859325728 即壁纸文件存放目录，其父目录为 ...../content/431960。

2. 提取结果存放目录：
    提取出的图片想要保存的目录。

3. 以名称创建文件夹：
    提取出的文件使用壁纸名称（project.json文件中的‘title’值）创建文件夹保存。
    如：...../content/431960/2859325728 ，默认提取后保存为 ...../target/2859325728；如果勾选此选项，则保存为 ...../target/对应壁纸名称

4. 提取文件保存：
    1.以文件夹分类
        同上，每个壁纸提取出的图片（一个壁纸可能会提取出多个图片）保存在同一文件夹内，不同的壁纸提取出的图片保存在各自对应的文件夹里
    2.合并到文件夹
        壁纸提取出的图片全部保存至一个文件夹（AAA-pics）里，文件名称为：壁纸名称-原文件名。同名文件有覆盖风险。
    3.分类和合并
        同1、2，分类文件夹与汇总文件夹都会保留。
选择完成后，点击‘开始转换’即可，下放会显示此次操作提取到的图片文件数量。

## 联系方式

- 维护者：[vans]
- 邮箱：[3305392065@qq.com]