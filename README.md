
## Git command

**创建库** 

```$ git init```

**提交**

```$ git add <file>```
> 可以添加多个文件到暂存区

```$ git commit -m "this is descript"```
> 将暂存区的修改都提交到仓库 -m 添加修改日志

**查看提交历史**

```$ git log```

**查看命令历史**

```$ git reflog```

**查看状态**

```$ git status```

**查看工作区和版本库里面指定版本的区别**

```$ git diff <version> -- <file>```

**版本回退**

```$ git reset --hard HEAD^```
> 回退到上个版本 
> 当前版本为 HEAD  上个版本 HEAD^  上上版本 HEAD^^

```$ git reset --hard <version>```
> 指定版本

****

```$ git checkout -- <file>```