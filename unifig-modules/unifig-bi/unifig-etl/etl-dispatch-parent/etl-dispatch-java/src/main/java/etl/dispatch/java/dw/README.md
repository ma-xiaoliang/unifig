汇总数据层（DW MODEL）：

即轻度汇总数据层，也是数据仓库核心层数据模型之一，该层实现两个目的：一是数据的整合处理，包括主题内的数据整合处理和跨主题整合处理；二是对数据做轻量汇总。目前该层按照混合模式设计（第三范式和维度建模混合），设计目标是为信息子层、应用数据层数据提供足够灵活方便和扩展性的基础数据，并保证从该层获取数据是性能最优，而不是从基础数据层经过复杂操作获取数据。