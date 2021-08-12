# Summer2021-No.13 openEuler版本演进中的License冲突检测

#### Description
https://gitee.com/openeuler-competition/summer-2021/issues/I3E2PG


#### Software Architecture
1. Pycharm

#### Plan

1. 构建开源许可证条款分析矩阵，条款包括但不限于链接、子证书授予、商用、分发、修改、专利授权、私用、使用商标、承担责任、提供担保、公开源码、防止协议与版权信息、使用网络分发、使用相同协议、声明变更等。
2. 定义冲突的概念以及产生冲突的条件，构建开源许可证冲突分析矩阵，给出不同许可证之间的兼容性关系。
3. 通过自动化方式实现2和3矩阵的扩充
4. 开发开源许可证冲突检测工具，以API、Web应用或在社区工具中添加此项功能的形式实现，能够生成开源许可证冲突检测报告，对冲突和兼容情况进行标识，给出数据来源的标注。

#### 项目完成情况

1.	借助资料和文档，熟悉了开源许可证的相关知识，明确了开源程序兼容性问题发生的场景,许可证组合的各类情况以及许可证涵盖的主要条款。
2.	总结和归纳开源许可证兼容性判定的一般性规则，选择了20余种Copyleft许可证进行详细分析，筛选出不符合该一般性规则的各种情况，初步构建完成开源许可证冲突与兼容性列表。
3.	基于构建的开源许可证冲突与兼容性列表以及开源许可证条款信息清单，搭建了一个Web程序，已实现对不同许可证冲突与兼容性的标识和提示。

#### 后续计划

1.	增加和完善License兼容性（冲突）列表，人工分析的许可证种类尽量囊括较为流行的开源License。
2.	对工具的代码、技术和功能进行完善。
3.	借助貂蝉网，对许可证的条款数据进行扩充，或考虑将兼容性检测的功能并入貂蝉网。


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
