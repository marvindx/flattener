# flattener
truffle-flattener 的精简版
* 直接将flat之后的文件 放在`full/`文件夹下
* 支持文件flat之后文件重命名
* 去除多余的license注释
## 前提：
* 项目根目录创建`full/`文件夹
* clone 本仓库代码之后，执行`yarn link flat`
* `chmod +x flattener.js`
## 用法：
```shell
$ flat contracts/Box.sol
output path:  /Users/marvin/contracts/upgradeContract/full/Box.sol
```
```shell
$ flat contracts/Box.sol BoxV2.sol
output path:  /Users/marvin/contracts/upgradeContract/full/BoxV2.sol
```
