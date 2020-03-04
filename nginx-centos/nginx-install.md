### 简要说明
- 默认centos环境
- 需要把pcre和nginx的源码包放到nginx/files目录下，并把相应的版本填写到nginx/vars/main.yml中
- 需要把nginx.conf放到nginx/templates/nginx.conf.j2
- 可以在nginx/vars/main.yml中修改nginx的安装参数，如：安装目录，需要安装的模块等