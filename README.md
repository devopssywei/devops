# devops
DevOps演示项目

1.登录

2.创建仓库

3.用gitbash创建证书
	ssh-keygen.exe -t rsa
4.cd ~进入家目录

5.ls

6.cd .ssh

7.ls列出目录下的文件  id_rsa（私钥）  id_rsa.pub（公钥）

8.把公钥id_rsa.pub内容放置到github上。
cat id_rsa.pub将内容粘贴到如下位置：
他开github点击用户图像---settings--SSH and GPG keys--New SSH

9.克隆仓库代码

	git clone git@github.com:devopssywei/devops.git
	
10.进入本地仓库目录修改README.md文件

11.将修改加入INDEX

	git add README.md
	
12.提交修改

	git commit -m "第一次修改" README.md
	
13.同步到github

	git push
	
	

