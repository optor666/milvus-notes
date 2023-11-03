1. 主页：https://milvus.io/

# Tutorials
## [Codelabs](https://codelabs.milvus.io/)
### [Vector Database 101 - Introduction to Unstructured Data](https://codelabs.milvus.io/vector-database-101-introduction-to-unstructured-data/index#0)
#### 数据分类
1. 结构化数据：使用传统关系型数据库存储的数据，每条数据包含相同数量、相同类型的字段，灵活性低，一致性、结构性强；主要形式是文本。
2. 半结构化数据：使用 NoSQL 数据库（例如：MongoDB、Redis）存储的数据，每条数据包含的字段数量、字段类型都可以不一样，灵活性高，一致性、结构性低；主要形式是文本。
3. 非结构化数据：主要形式是图片、视频。两张包含相似事务的图片，其二进制表示可能差异很大，需要使用机器学习算法将其向量化存入向量数据库中。

### [Vector Database 101 - What is a Vector Database?](https://codelabs.milvus.io/vector-database-101-what-is-a-vector-database/index#0)
#### 什么是向量数据库
1. 一个合格的向量数据库需要满足如下特性：
    - 可扩展性和可调行（软件参数或行为可以按需微调或优化）
    - 支持多租户和数据隔离
    - 配套的 API 和 SDK
    - 直观的用户界面/管理控制台
2. 向量数据库 vs 向量检索库：向量检索库主要功能就是检索，而向量数据库却是集向量检索、向量存储、服务云原生化、支持多租户和数据隔离等优势于一身的完整解决方案。
3. 向量数据库 vs 传统数据库+向量检索插件：传统数据库本来是为了解决结构化数据、半结构化数据的存储、检索而设计的，而向量数据库是专门从头为非结构化数据存储、检索设计的，其优越性不是插件能比得了的。

## [Bootcamp](https://milvus.io/bootcamp)
