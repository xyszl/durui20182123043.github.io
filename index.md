### 用例名称
creating new file
### 用例说明
仓库管理员在仓库中创建一个新的文件，首先命名文件，然后编辑文件，提交新文件时可以建立新的档案，同时添加扩展说明，也可以进行预习 。
### 参与者	
仓库管理员
### 元素	
creating a new file 、Edit new file 、commit new file 、preview、
create new file、add extend description
### 关系
元素Edit new file，commit new file对于creating a new file是包含关系；
元素preview是元素creating a new file的扩展；
元素creating a new file和add extend description是commit new file的扩展。
### 建模思路	
仓库管理员在仓库中creating new file，提交新文件时可以建立新的档案，同时Add extended description。此外，可以进行preview，初次在仓库创建文件时，预习文件部分为空。


### 用例名称	
uploading an existing file、Query file
### 用例说明
仓库管理员下载现有的文件开始使用，将文件添加到存储库中或者选择管理员自己的文件将其添加到存储库中。提交文件变更的时候可以通过上传添加文件，同时添加可选的扩展说明。仓库管理员通过命令行推送现有存储库。
### 参与者	
仓库管理员
### 元素	
uploding an existing file、Query file、choose your files、commit change、Add files via upload、Add extended description
### 关系	
元素choose your files对于元素uploding an existing file是包含关系；
元素commit change是uploding an existing file的扩展；
元素Add files via upload 和Add extended description对于元素commit change是包含关系。
### 建模思路	
仓库管理员可以uploading an existing file，将文件拖到指定位置以将其添加到存储库中或者选择管理员自己的文件将其添加到存储库中。提交文件变更的时候可以通过上传添加文件，同时添加可选的扩展说明。同时可以push an existing repository from the command line，即Query file。
