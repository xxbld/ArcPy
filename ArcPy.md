# ArcPy NOTE

### ArcPy 模块
数据访问模块 (arcpy.da)、
制图模块 (arcpy.mapping)、
Spatial Analyst 扩展模块 模块 (arcpy.sa)、
Network Analyst 扩展模块 模块 (arcpy.na)。

###  命名为`XXX_mb`工具专用于模型构建器
```python
# Process: 迭代要素选择
# 此工具专用于模型构建器，而并不在编写 Python 脚本时使用。
arcpy.IterateFeatureSelection_mb(输入要素, 按字段分组, 跳过空值)
```