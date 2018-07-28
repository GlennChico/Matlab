# Matlab教程
## 
### 常用功能
* a: b:c : 从a到b,步长为c
* linspace（a,b,c）：插值
* 功能函数
	* hold on,hold off：相对使用，功能：多图共存
	* tic,toc 计时函数
* 画图相关
	* xlabel,ylabel,title：坐标轴，标题
	* grid
		* griddata：  vq=graddata(x,y,v,xq,yq) ，v：样本关于x,y的值，v(x,y)
		* meshgrid： 生成网格采样点的函数
		* grid on :增加网格
	* figure :建立图形，可用参数（尺寸、位置等等）
	* plot(x1,y1,linespec1,x2,y2,linespec2): 参数x,y，线的种类
	* plot3/mesh/surf的区别
		* plot3 三维曲线图
		* mesh 三维网格图
		* surf 三维着色曲线图
* 矩阵相关
	* randn :是一种产生标准正态分布的随机数或矩阵的函数 
		* 参数：randn(n)，randn(m,n),randn(size(A))
	* zeros :功能是返回一个m×n×p×...的double类零矩阵
	* eye(m,n):创造一个mxn，对角元素为1的矩阵
	* ones(m,n):创造一个mxn，元素全为1的矩阵
	* sparse: 稀疏矩阵 参数sparse(i,j,k)，或者sparse(A),i=j=k，i,j是一组位置，k是相对应位置的值
	
* 代数
	* rank ： 求矩阵的秩，rank([A y])
	* inv ： 求逆    \ ： 矩阵左除运算


* 集合运算
	* union(a,b) 并集
	* intersect(a,b) 交集
	* setxor(a,b) 在a不在b上的
* 多项式
	* 表达方法，p=[1 -12 4 25 22] 表达为p=x^4-12x^3+4x^2+25x+22
	* 求根 r=root(p)
	* 卷积 c=conv(a,b) 卷积：是通过两个函数f和g生成第三个函数的一种数学算子
	* 

