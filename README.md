# DDD Microservice Sample

- 用户接口层：面向前端用户提供服务和数据适配。聚集了接口和数据适配相关的功能。
- 应用层：实现服务组合和编排，主要适应业务流程快速变化的需求。聚集了应用服务和事件订阅相关的功能。
- 领域层：实现领域模型的核心业务逻辑。包括领域模型的集合、聚合根、实体、值对象、领域服务和事件等领域对象，通过各领域对象的协同和组合形成领域模型的核心业务能力。
- 基础层：贯穿所有层，为各层提供基础资源服务。