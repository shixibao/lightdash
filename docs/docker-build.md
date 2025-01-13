# 自动构建

将代码合并到主分支 `main` 后，打 tag 触发 github 的自动构建脚本。

git actions 会编译代码并构建镜像，将代码推送到 dockerhub 或者 其他镜像源仓库。

参考 [git action workflow file](../.github/workflows/build-docker-with-i18n.yml) 文件。
