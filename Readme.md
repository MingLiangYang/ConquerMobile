# ConquerMobile

- 一款统计手机各个应用使用时间并添加限制功能的手机应用，甚至可以自行设置手机应用的使用时间
- 除了提供手机各个应用的时间的显示功能外，还提供了应用使用时间超时限制功能，例如：通知栏提醒，关机，重启，锁屏等惩罚方式
- 应用使用时间的统计调用了google官方提供的 android.app.usage 的 API，用于用户获取手机中各个应用的使用情况以及使用时间
- 获取时间时由于没有调用后台服务实行精确统计，所以在时间节点上可能显示不很精确
- 图表的绘制绘制图表调用的库来自于开源的 MPAndroidChart 图表项目，其项目位置：https://github.com/PhilJay/MPAndroidChart
