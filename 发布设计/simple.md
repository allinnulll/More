### 不能算是正规的发布系统，只是按照自己的需求、能力和想法实现的一个简单的自动化

##### 主要涉及的地方

1. 代码仓库
2. 静态资源站点
3. web站点

##### 逻辑

1. 打包 
		
		1. 从代码仓库拉取代码到静态资源站点
		2. 生成版本号（即时间戳）命名的文件夹
		3. 输出版本号
2. 发布
		1. 修改输出HTML引用文件的版本号

##### 功能

1. web服务
2. 静态资源站点
3. 可视化发布站点