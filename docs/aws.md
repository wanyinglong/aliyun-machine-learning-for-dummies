Amazon Web Services (AWS) 上和 阿里云 GN5 规格比较接近的是 [P2](https://aws.amazon.com/ec2/instance-types/p2/) 实例。其使用的是 NVidia Tesla K80 显卡。

从下图不难看出， GN5 目前使用的 P100 显卡
![pic](img/deep_learning_benchmark_per-network_speedups_on_Tesla_P100_PCIe.png)


当然 AWS 作为云计算业界的标杆， 肯定也有其优势的地方。 例如， AWS EC2 实例在停机后就只收取磁盘费用， 而阿里云要在实例删除后才停止收费。 此外 AWS 还提供了 Amazon Machine Image (AMI)， 即专为机器学习定制的系统镜像， 简化了 NVidia 驱动和 CUDA 的安装。而且 AWS 的竞价实例模式(Spot Instances) 已经推出很久了， 其价格已经十分稳定， 基本没有大的波动。 而阿里云在今年双十一后， 较长一段时间都维持了高价。
