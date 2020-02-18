# StockAnalysisSystemData
  
#### 介绍
StockAnalysisSystem的离线数据  
  
#### 安装教程
  
1.  下载或clone本项目到本地并解压
2.  获取并运行StockAnalysisSystem: https://gitee.com/SleepySoft/StockAnalysisSystem  
3.  如果软件从未被配置过，则会自动弹出配置窗口；如果不是，则从是界面上方菜单中选择：Config->系统配置  
4.  在配置窗口中点击Browse按钮正确配置MongoDB bin的路径（本人电脑中的路径是：C:\Program Files\MongoDB\Server\4.0\bin）  
5.  点击Import按钮，选择刚解压的文件夹，程序将会自动导入离线数据到本地的MongoDB数据库中  
  
#### 使用说明
  
1.  数据由mongodump导出，并使用mongorestore导入；用户也可以通过MongoDB的客户端软件自行导入
2.  数据库建议使用默认的端口，并且不设置密码，否则可能导入不成功
