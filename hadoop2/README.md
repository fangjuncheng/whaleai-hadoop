# whaleai-hadoop  
## WhaleAI 专注人工智能/大数据
## 提供简化hadoop安装部署方式,自动化安装，安装过程中一路```yes```即可　

## ```. whaleai-hadoop2.sh -i　```

### This script installs Hadoop 2 with basic data, log, and pid directories.
已经支持的版本　hadoop-2.7.3 hadoop-2.8.0
USAGE:  ```. whaleai-hadoop2.sh [options]```


OPTIONS:

   - -i, --install　        伪分布式安装部署hadoop3

   - -r, --remove           卸载hadoop3

   - -h, --help             Show this message.

## EXAMPLES:
  - 如何安装？hadoop2 install:
>
>		 . whaleai-hadoop2.sh -i　
>
>		 Or . install-hadoop2.sh --install
>
  - 如何卸载？hadoop2 remove:
>
>		 . whaleai-hadoop2.sh -r
>
>		 Or . install-hadoop2.sh --remove
