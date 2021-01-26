<h1 align="center">VegaOps</h1> 
<p align="center">基于API的高效调度编排工具</p>

<p align="center">
<img src="https://img.shields.io/badge/Version-1.0-orange" title="Version" />
<img src="https://img.shields.io/badge/City-Wuhan-red" title="武汉" />
<img src="https://img.shields.io/badge/Build-passing-green" title="Build" />
</p>

<p align="center">
<a href="./README.en.md">English</a> |
<a href="./README.zh-cn.md">中文</a>
</p>


## Sponsors



### introduction

VegaOps是基于API的高效调度编排工具。



### characteristic
1. 灵活的编排采集能力：
  - 对标OpenStack heat、terraform等，通过解析资源模版，可快速批量构建云资源；
  - 可通过资源模版，获取多云资源，提供格式化输出数据到用户CMDB；
  - 可通过metric模版，获取多云监控指标，并提供格式化输出数据到用户监控平台；
2. 灵活的Provider拓展能力：
  - 无需编码，通过编写provider提供的各资源的json解析文件，实现Provider拓展；
  - 灵活生效，无需重新进行复杂的打包流程，provider的解析json保存即生效；

### Preparation



### How to use



#### Provider list
* [阿里云](https://github.com/vegaops/vegaops-aliyun-provider)
* [腾讯云](https://github.com/vegaops/vegaops-tencentcloud-provider)
* [AWS](https://github.com/vegaops/vegaops-aws-provider)
* [天翼云](https://github.com/vegaops/vegaops-ctyun-provider)

#### Example list
* [云资源编排](https://github.com/vegaops/vegaops-examples-cloudorch)
* [多云资源采集](https://github.com/vegaops/vegaops-examples-cloudresource)
* [多云监控采集](https://github.com/vegaops/vegaops-aws-cloudmetric)



### Contribution

Thank you to all the people who already contributed to VegaOps!



### License
[Mozilla](./LICENSE)

Copyright (c) 2013-present, OneProCloud(WUHAN) Co.,Ltd

