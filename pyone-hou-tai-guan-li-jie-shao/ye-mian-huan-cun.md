# 更新列表

本功能主要是在通过其他方法上传了文件到onedrive后，更新文件列表。

### 选项介绍

1. **网盘选择**：默认全部网盘都进行操作。如果只更新其中一个网盘文件，则选择网盘
2. **更新规则**
   * **增量更新**：通过检测本地目录和远程目录的大小，只有在远程目录的大小发生变化的时候才进行更新文件列表操作，否则不更新！
   * **全量更新**：直接清除本地文件列表，并全盘更新文件列表！
3. 如果**远程文件夹结构没有发生变化**，推荐使用**增量更新**！如果**远程文件夹结构发生了变化**，推荐使用**全量更新**！

#### 



