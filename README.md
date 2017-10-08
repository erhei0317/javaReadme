###如何生成git的公钥和私钥
`ssh-keygen -t rsa -C "hnerhei@qq.com"`
之后会在当前用户的目录下生成
`id_rsa`
`id_rsa.pub`
将`id_rsa.pub`的内容复制，并拷贝到自己的github设置公钥的地方，保存。
git添加文档：
在本地git目录下，创建文件，比如说添加【git使用技巧】文件
`git add git使用技巧`
然后使用
`git commit -m "第一次提交"`
`git remote add orgin git@github.com:erhei0317/javaReadme.git`
然后推送
`git push -u orgin master`

