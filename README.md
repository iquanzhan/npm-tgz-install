# npm依赖离线打包工具

1. 安装本项目依赖

   ```shell
   npm install	
   ```

2. 在源代码中执行`npm install`安装后生成的`package-lock.json`覆盖至根目录

3. 命令行执行`node npm-install.js`

## 注意

1. tgz包将下载至`download`文件夹中。

2. 为防止重复下载，可将已下载的tgz包放入`download/downloaded`文件夹中。下次将略过已下载文件