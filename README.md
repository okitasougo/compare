# compare
关于dota 训练集

在SRGAN上的训练 参考代码：https://github.com/leftthomas/SRGAN
1.关于python：
如果你的python是3.8版本，请注意
   在test_image.py中start = time.clock() python3.8不支持了，请修改为start = time.perf_counter()
2.关于pytorch的安装：
   查看cuda ：版本打开CMD，输入nvcc --version
   根据对应版本去官网https://pytorch.org/get-started/previous-versions/寻找合适版本
