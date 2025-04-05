# **Cytoid 角色修改教程**

## **1. 软件准备**
- 一个Unity Bundle修改器：[UABEAvalonia](https://github.com/nesrak1/UABEA)
- 图片处理工具：[Photoshop](https://pan.baidu.com/s/1NzZCXnoSt59dKmCGG4hXNQ?pwd=fnhy)
- 解压软件：[7-zip](https://7-zip.org)
- APK 签名工具：[MT管理器](https://mt2.cn)

## **2. 处理 APK**
1. 下载Cytoid安装包，右键菜单选中`7-zip`提取，将其解压至一个你能找到的路径
2. 按照路径`解压路径\assets\Android\Bundles`找到文件`character_sayaka`
![Bundle路径](pics/bundle_path.png)

## **3. 导出资源**
1. 进入`UABEAvalonia`，使用组合键`Ctrl + O`打开文件`character_sayaka`, 接着选择`Memory`(解压至内存)
2. 点击`Info`（不要选择后缀为`.resS`的文件）进入详情，接着点击`Types`进行整理，拖到下面选中类型为`Texture2D`的文件
![整理和选择](pics/uabea_type.png)
3. 点击右侧的`Plugins`，选择`Batch export textures`，接着选择`PNG`格式导出
![导出图片](pics/uabea_export.png)

## **4. 处理图片**
自行使用`Photoshop`修改图片，注意分辨率应为`2048x2048`，且角色位置需与原图完全一致，否则会出现问题

## **5. 写回 Bundle**