- App文件夹是应用的源代码和配置文件所在的地方
  - 它所含的文件：
  - Dockerfile：
  - 它并不是应用的一部分，它的内容是一条条Docker指令，用于将该应用构建到容器镜像中（对应用进行容器化）
  - app.js是应用的主文件，它是一个Node.js应用
  - bootstrap.css是一个样式表模板，决定应用的网页外观
  - package.json列出了应用的依赖
  - views是一个包含HTML的文件夹，用于填充应用的网页