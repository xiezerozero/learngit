告诉Git，以后st就表⽰示status
git config --global alias.st status
// 以后git status 简写 git st
git st

其他:
git config --global alias.co checkout
git config --global alias.ci commit
git config --global alias.br branch

配置⼀一个git last，让其显⽰示最后⼀一次提交信息：
git config --global alias.last 'log -1'

git config --global alias.gl "git log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"