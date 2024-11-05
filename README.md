# 维护指南


使用mkdocs框架material主题，便于维护

## 修改

### 修改内容

修改对应的md文件即可
### 增添图片

wiki文件夹默认为根目录
在static中的jpg文件相对路径为
```
/static/*/*.jpg
```

1. 本地图片 **【建议】**
    放到static对应文件夹中，使用明显易懂的命名方式
    （在index.md中有使用例子）
2. 远程仓库
3. 其他方式

## 本地预览
### 安装

python3.*环境

```shell
pip install mkdocs
pip install mkdocs-material
```

### 预览

```shell
mkdocs serve
```