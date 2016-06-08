Git is a version control system.
Git is free software.

git add readme.txt
git commit -m "balabalabala"

Git is a distributed version control system.
Git is free software.

Git is a distributed version control system.
Git is free software distributed under the GPL.

现在总结一下：

HEAD指向的版本就是当前版本，因此，Git允许我们在版本的历史之间穿梭，使用命令git reset --hard commit_id。

穿梭前，用git log可以查看提交历史，以便确定要回退到哪个版本。

要重返未来，用git reflog查看命令历史，以便确定要回到未来的哪个版本。

Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.

管理修改
http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/001374829472990293f16b45df14f35b94b3e8a026220c5000