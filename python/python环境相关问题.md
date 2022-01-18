### pip遇到的问题
1. 服务器: ubuntu20.04
2. python3.8
> 问题报错: AttributeError: module "importlib._bootstrap" has no attribute "SourceFileLoader"

解决方法:
```shell
# 参考: https://stackoverflow.com/questions/44761958/using-pip3-module-importlib-bootstrap-has-no-attribute-sourcefileloader
curl -sS https://bootstrap.pypa.io/get-pip.py | sudo python3
```
