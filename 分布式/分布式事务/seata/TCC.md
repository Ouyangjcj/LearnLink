
TCC 模式其实就是自定义版的AT模式：
 一阶段 prepare 行为：调用 自定义 的 prepare 逻辑。
 二阶段 commit 行为：调用 自定义 的 commit 逻辑。
 二阶段 rollback 行为：调用 自定义 的 rollback 逻辑。

支持把 自定义 的分支事务纳入到全局事务的管理中
