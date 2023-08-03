一般会出现在测试环境中


CLB 回环可能导致的问题现象有：

不管是 iptables 还是 ipvs 模式，访问本集群内网 Ingress 出现 4 秒延时或不通。
ipvs 模式下，集群内访问本集群 LoadBanacer 类型的内网 Service 出现完全不通，或者时通时不通。
