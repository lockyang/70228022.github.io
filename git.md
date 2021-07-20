## 遇到过的Git错误
> Q: refusing to merge unrelated histories <br />
> A:   
> 情况1: 克隆了一个项目但丢失了.git目录，导致git不能获取本地历史记录  
> 情况2: 创建了一个新的存储库，向它添加了一些提交，现在您正试图从已经拥有自己一些提交的远程存储库中提取  
> 解决：git pull origin \<branch\> --allow-unrelated-histories
