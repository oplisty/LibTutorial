# PANDAS

本教程专注于 pandas 在数据处理中的各种常用操作，**覆盖从数据读取到清洗、变换、分析、导出的完整流程**。

## 数据处理（`pandas`）

**路径为 `pandas/pandas.ipynb`**

- `pd.DataFrame` / `pd.Series` — 数据容器
- `pd.read_csv()` / `.to_csv()` — 数据读写
- `.head()` `.info()` `.describe()` — 数据概览
- `.loc[]` `.iloc[]` `df[条件]` `.query()` — 索引与筛选
- `.isnull()` `.fillna()` `.dropna()` — 缺失值处理
- `.groupby()` `.agg()` `.value_counts()` — 分组聚合
- `df['新列'] =` `.apply()` — 新增列与变换
- `.sort_values()` — 排序
- `pd.concat()` `pd.merge()` — 数据合并
