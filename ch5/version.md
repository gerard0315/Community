# 项目版本和附件

### 生成项目版本
在K-Lab上创建的数据分析项目如果需要公开发布或分享给他人，必须要至少成一个项目版本：在Notebook页面点击**生成版本**按钮，该操作将基于当前notebook的内容生成一个新的版本。

![image description](/image/运行时-生成版本.png)

### 添加附件
对于一些和Notebook相关或Notebook所依赖的工程文件、数据文件，可以作为Notebook的附件，在生成版本时一起保存。生成一个项目版本时最多能选择**5个文件**，总大小不超过**10M**。添加附件文件的步骤如下：

* 在**work目录**下创建一个**新的文件夹**；
* 将需要添加为附件的文件都存入该文件夹内；
* 在点击**生成版本**按钮后，会跳出会话框如下，在会话框内勾选所需的文件即可。
* 需要注意的是，勾选的文件需要在**同一文件夹内**哦。

![image description](/image/add-attachment.png)

**特别需要注意的是，将文件直接存入work目录下是无法保存为附件的哦，一定要存入**work目录下某一个文件夹**内才可以。**

* 如果想查看**某一版本的项目**相关的依赖文件，在项目详情里点击**附件**即可查看：

![image description](/image/content-attachment.png)

### Fork包含附件的项目

在Fork了一个包含附件的项目后，附件中的文件会**自动导入你的work目录**下。如果附件名与自己工作区里的文件夹重名，可以修改文件夹名称或直接覆盖原文件。

![image description](/image/renamefile.png)


导入成功后可以在文件树的work目录下直接查看附件：

![image description](/image/view-new-file.png)