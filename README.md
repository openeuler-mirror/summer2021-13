# Summer2021-No.13 openEuler版本演进中的License冲突检测

#### Description
https://gitee.com/openeuler-competition/summer-2021/issues/I3E2PG


#### Software Architecture
1. Pycharm

#### 方案

1.	构建开源许可证条款分析矩阵，条款包括但不限于链接、子证书授予、商用、分发、修改、专利授权、私用、使用商标、承担责任、提供担保、公开源码、防止协议与版权信息、使用网络分发、使用相同协议、声明变更等。
2.	定义冲突的概念以及产生冲突的条件，挖掘不同许可证之间兼容性判断的一般性规则，同时对选定开源许可证文本内容进行细致分析，构建开源许可证相容性矩阵，给出不同许可证之间的冲突情况以及相容性关系。
3.	开发开源许可证冲突查询工具，以Web应用形式实现，通过对项目使用的许可证以及项目要引入的许可证选择，可视化标识是否会产生冲突和相容性情况，并给出数据来源和准确性的标注。

#### 项目产出

1. 开源许可证条款分析矩阵：该成果主要通过Excel图表形式呈现，该图表搜集了60种世界范围内流行的开源许可证，对每个许可证的SPDX标识符、类别、FSF认证情况、OSI认证情况、13项条款的声明情况进行了详细标识。
1. 许可证相容性分析矩阵：该成果主要通过Excel图表形式呈现，基于对冲突和相容性的定义和理解，借助许可证相与否的判断规则，对33种Copyleft类型的开源许可证的相容性相关问题进行了细致分析和解读，构建形成流行开源许可证相容性分析图表，用于便捷查询不同许可证之间的冲突和相容情况。
1. 《开源许可证相关知识与相容性解读》白皮书撰写：归纳了开源许可证领域内的各类相关知识，主要对不同开源许可证之间的冲突问题进行了细致阐述，总结出判断开源许可证相容与否的一般性规则和各类例外情况。
1. 开源许可证冲突查询工具：以Web应用的方式实现不同开源许可证之间冲突查询以及兼容与否的情况。


#### Contribution

1.  Fork the repository
2.  Create Feat_xxx branch
3.  Commit your code
4.  Create Pull Request


#### Gitee Feature

1.  You can use Readme\_XXX.md to support different languages, such as Readme\_en.md, Readme\_zh.md
2.  Gitee blog [blog.gitee.com](https://blog.gitee.com)
3.  Explore open source project [https://gitee.com/explore](https://gitee.com/explore)
4.  The most valuable open source project [GVP](https://gitee.com/gvp)
5.  The manual of Gitee [https://gitee.com/help](https://gitee.com/help)
6.  The most popular members  [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
