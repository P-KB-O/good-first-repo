### 基本概念

实体 (entity)：语义类别上的对象或对象集合，每种实体具有相应类别，如人物、组织、地点、时间等。

实体描述(entity mention)：文档中关于实体的描述，一个或多个 实体描述构成一个实体 。

事件描述 (event mention)：文 中具 体描述 事件 的句 子或片段 。

事件论元角色(event argument)：在事件中担当某类角色的实体、数值或时间，主要包括事件参与者以及与事件相关的属性 (如时 间属性 ) 。


### 任务

事件抽取（event extractions）包含两种模式: pipeline mode(分为trigger identification和argument identification)和 joint mode 

事件关系抽取(event relation extractions) 

事件表示(event representation)是一种表示学习，类似word embedding，它的子任务也是十分的多，大致都是通过对事件进行嵌入学习，获得和word2vec类似的能力(例如：中国+北京=美国+?)，推断子事件（进入餐馆->点餐->付钱->?）等。
