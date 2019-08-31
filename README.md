使用AutoCAD Civil 3D进行工程测量内业处理时非常方便，但在进放出图阶段时，CASS部分功能依然是需要的。我们将通过AutoLisp进行扩展，将CASS部分功能移植到Civil 3D或更高版本的AutoCAD中。
使用AutoLisp是因其兼容性最好，而且较C++和VBA更简单。目前实现的功能有：

- 通过描述码集生成点状地物
- 生成方格网
- 删除区域外（或区域内）的地形点
- 非CASS中打开地形图导出地形点至数据文件：CASS-point-block-to-point-entity.lsp
- 非CASS中打开地形图将地形点转换成CAD实体点用于Civil 3D点对象的创建：CASS-export-point-to-dat-file.lsp

### 计划中

- 解析代码法绘图的数据文件中线形地物的绘图
