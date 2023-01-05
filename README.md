jsDelivr CDN



## 上传资源
复制需要上传的资源到本地git仓库（注：jsDelivr不支持加载超过20M的资源）

```git
git status                    //查看状态
git add .                     //添加所有文件到暂存区
git commit -m '第一次提交'      //把文件提交到仓库
git push                      //推送至远程仓库
```

## 发布仓库
点击release发布
![image](https://user-images.githubusercontent.com/76586211/210697394-5b74fe31-196e-4c16-ab15-93b20dc39e8d.png)

自定义发布版本号
![image](https://user-images.githubusercontent.com/76586211/210698938-263e3acd-6c3d-4eec-a023-75b1ab8bc8c8.png)


## 通过jsDelivr引用资源
使用方法：https://cdn.jsdelivr.net/gh/你的用户名/你的仓库名@发布的版本号/文件路径
例如：
```
https://cdn.jsdelivr.net/gh/Melanie618/CDN@v1.1/images/logo.jpg
https://cdn.jsdelivr.net/gh/Melanie618/CDN@v1.1/cursor/arrow.cur
```
