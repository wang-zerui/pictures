# pics

for picgo-core

config.json

```json
{
  "picBed": {
    "uploader": "githubPlus",
    "current": "githubPlus",
    "githubPlus": {
      "branch": "main", // 仓库分支
      "customUrl": "https://cdn.jsdelivr.net/gh/xinwuyun/pictures@main", // 使用加速后的github自定义url
      "origin": "github", // 存放的图片类型
      "repo": "xinwuyun/pictures", // 存放图片的仓库，注意替换为你自己的仓库
      "path": "", // 存放图片的仓库目录下的文件夹
      "token": "xxxxxxxxxxxxxxxxxxxxxxxxxx" // 访问github的仓库的token
    }
  },
  "picgoPlugins": {
    "picgo-plugin-github-plus": true // 启用github-plus插件
    ,
    "picgo-plugin-rename-file": true
  },
  "picgo-plugin-rename-file": {
    "format": "{y}/{m}/{d}/{hash}-{origin}-{rand:6}" //启用重命名插件
  },
  "picgo-plugin-github-plus": {
    "lastSync": "2022-03-09 08:59:47"
  }
}
```
