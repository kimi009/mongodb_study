# mongodb_study
StudyMongodb  首先到mongodb官网下载msi包，安装完成后配置环境变量 以管理员的方式运行下面的命令
mongod --dbpath="D:\Program Files\MongoDB\Data\db"     ====》表示数据库存放路径
       --logpath="D:\Program Files\MongoDB\Data\log\MongoDB.log" =====》很明显是日志路径
       --logappend ===》日志追加
       --directoryperdb  ===》每个db都放到单独的目录
       --install
       --serviceName="mongodb"
