### 04.Github配置说明

```bash
# 配置说明
> cd /Users/axu/code/axuProject
> pwd
/Users/axu/code/axuProject

> git clone https://github.com/axu4github/configuration.git
Cloning into 'configuration'...
remote: Counting objects: 11, done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 11 (delta 0), reused 8 (delta 0), pack-reused 0
Unpacking objects: 100% (11/11), done.

> cd /Users/axu/code/axuProject/configuration/04.Github
> ll
total 16
-rw-r--r--  1 axu  staff   14  4  3 23:02 README.md
-rw-r--r--  1 axu  staff  282  4  3 23:02 gitconfig

# 将配置拷贝到用户根目录
> cp gitconfig ~/.gitconfig
> ll ~/.gitconfig
-rw-r--r--  1 axu  staff  282  4  3 23:04 /Users/axu/.gitconfig

# 检查
> git st
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean
```

