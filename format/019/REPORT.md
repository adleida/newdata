tkit必须指定notice_file文件,
当exchange接收到错误的bid-response文件后,未返回notice,

解决方案
1.tkit制定config.yaml文件中notice_file为可选参数
2.exchange返回lose