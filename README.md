# unixbench 

如果你想使用UnixBench测试你的服务器性能，请使用SSH工具连接你的服务器后执行下面命令。脚本默认使用UnixBench5.1.3版本，因为大多VPS都没有显卡或者是集成显卡，不需要进行图像性能测试，所以作者注释了关于graphic的测试项。此脚本运行测试时间大约10-30分钟，跑分结束后得分越高性能越好。

wget --no-check-certificate https://github.com/rainsuns/unixbench/blob/master/unixbench.sh 

chmod +x unixbench.sh

./unixbench.sh
