
1. 复制`php-worker/crontabs/default.example` 到`php-worker/crontabs/default`，将执行的脚本放入到文件中

2. 使用`docker-compose up -d` 创建并启动容器

3. 新加脚本后，使用`docker-compose build && up -d` 重新编译并启动容器