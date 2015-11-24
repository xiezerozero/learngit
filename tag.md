git tag //所有标签
git tag tagName //HEAD创建一个标签
git tag tagName commit_id   //使用指定的提交创建一个标签
git tag -a tagName -m 'message' commit_id   //指定标签信息

git tag -d tagName  //删除标签

git checkout tagName


git push origin tagName     //推送标签

git push origin --tags      //一次性推送全部尚未推送到远程的本地标签：

删除远程标签 1.git tag -d tagName //删除本地标签
            2. git push origin :refs/tags/tagName   //从远程删除。删除命令也是push
