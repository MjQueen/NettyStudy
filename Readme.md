- Netty + MUI仿微信实现聊天APP
  - 后端使用SpringBoot + mybatis + netty，前端使用MUI 和 H5+
  - IDE：后端IDEA2019.1.2，前端：HBuilderX
- 实体类和mybatis初始架构（即mapper包、pojo包、mapperxml包）使用mybatis-generator逆向工程生成(可直接使用imooc-muxin-mybatis项目生成，修改相应配置文件即可)
  - 注意：xml生成是追加式的，所以，如果需要重新生成，需将以前生成的xml删除
- 使用org.n3r.idworker包生成唯一主键（便于后期分布式拆表扩展）
- 代码写于 6.1 - 