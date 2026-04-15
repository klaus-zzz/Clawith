将当前所有变更提交到 git 并推送到远程仓库。

1. 运行 git status 查看变更
2. 运行 git diff 查看具体改动
3. 运行 git log --oneline -3 查看最近提交风格
4. 将所有变更的文件 git add（注意不要添加 .env 或含密钥的文件）
5. 根据变更内容生成合适的 commit message，遵循项目已有的提交风格
6. git commit
7. git push origin main

如果用户提供了 $ARGUMENTS，将其作为 commit message 使用。
