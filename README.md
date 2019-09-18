# txle | [中文](README_ZH.md) [![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html) [![Gitter](https://img.shields.io/static/v1?label=chat&message=on&nbsp;gitter&color=brightgreen)](https://gitter.im/actiontech-txle/Lobby)

txle is a distributed transaction solution and can guarantee the final consistency of the business data.
## Feature
* Multiple ways to guarantee the final consistency of the business data.
* High performance. QPS is 5000 or so and TPS is 50000 or so.
* Low invasion. It can work by setting 2 annotations.
* Support quick start by Docker.
* Support service downgrading. No effect to main business in case of irresistible factors.
* Support for exception snapshot processing.
* Support both timeout and retry.

## History
txle is based on [ServiceComb Pack](https://github.com/apache/servicecomb-pack). First of all, thanks to the contributors from ServiceComb Pack.

For us, focusing on MySQL is a better choice. So we cancelled the support for other databases, deeply improved/optimized its behavior on compatibility, complex query and distributed transaction. And of course, fixed lots of bugs.
## Architecture

![txle architecture](docs/txle-architecture.png)

## Quick start

[中文文档](https://actiontech.github.io/txle-docs-cn/1.QuickStart/1.0_deployment.html)

## Official website

For more information, please visit the [Official website](https://opensource.actionsky.com/).

## Documentation

For more information, please visit the [Official website](https://opensource.actionsky.com/).

## Contribution

Contributions are welcomed and greatly appreciated. See [CONTRIBUTION.md](https://github.com/actiontech/txle/blob/master/docs/CONTRIBUTION.md) for details on submitting patches and the contribution workflow.

## Community

* [![Gitter](https://img.shields.io/static/v1?label=chat&message=on&nbsp;gitter&color=brightgreen)](https://gitter.im/actiontech-txle/Lobby)
* QQ group: 696990638
* wechat subscription QR code
  
  ![dble](./docs/QR_code.png)

## Contact us

txle has enterprise support plans, you may contact our sales team:

- Global Sales: 400-820-6580
- North China: 86-13718877200, Mr.Wang
- South China: 86-18503063188, Mr.Cao
- East China: 86-18930110869, Mr.Liang
- South-West China: 86-13540040119, Mr.Hong