# ZWYSigner
修复 ECSigner 开源版的 bug

感谢大佬的 [https://github.com/even-cheng/ECSigner](https://github.com/even-cheng/ECSigner) 工具, 虽然有一些 bug 在, 现在修复了一下, 在这个仓库使用

主要修复:
1. 支持了系统快捷键操作, cmd+q cmd+v
2. api 返回信息对应的模型参数缺失, 导致无法继续执行 Promise, 补充了参数
3. 拖拽文件的逻辑调整
