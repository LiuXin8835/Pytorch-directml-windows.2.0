# Pytorch-directml-windows.2.0
提供编译好的兼容Directml适用于windows的PyTorch2.0 whl

## 版本说明

目前只提供适配Python 3.10和Python 3.11版本的whl包
感谢微软官方[Microsoft.DirectML#400](https://github.com/microsoft/DirectML/issues/400#issuecomment-1470074201)号issue提供的解决方案

## 文件说明

source 文件夹 - 编译用的源代码

torch-2.0.0a0+gitunknown-cp310-cp310-win_amd64.whl - 适用于Python 3.10的torch文件

torch-2.0.0a0+gitunknown-cp311-cp311-win_amd64.whl - 适用于Python 3.11的torch文件


## 特别说明

如果安装后运行时提供backend缺少文件，可以下载正常torch2.0 cpu的windows包，用7zip打开从里面进入`torch-2.0.0+cpu-cp310-cp310-win_amd64.whl\torch\lib\`路径把全部文件解压到对应安装目录的`torch\lib`路径即可，如果提示文件已存在不用覆盖，之后应该就可以正常使用
