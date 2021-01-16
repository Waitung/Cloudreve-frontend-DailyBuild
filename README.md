# Cloudreve frontend Daily Build

Cloudreve 前端静态资源每日构建
- https://github.com/cloudreve/frontend
- 每天 04:00 GMT+8 检查对应仓库的 **commits**，一天内有新的则进行构建
- 构建后删除 **map** 后缀文件上传到本仓库的 **statics** 文件夹里，并打上日期 **tag**