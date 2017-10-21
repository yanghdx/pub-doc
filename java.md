# Java知识点

### linux启动脚本
#!/bin/bash

java -server -Xms1G -Xmx1G -Dfile.encoding=utf-8 -Djava.io.tmpdir=/xxx/tmp -jar /xxx/xxx.jar > /dev/null
