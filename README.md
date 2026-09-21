# 重庆高校 2025 软科排名与新生人数数据

文件：`data/chongqing_university_2025_soft_ranking_enrollment.csv`

## 口径说明

- `soft_ranking_2025` 保存软科主榜名次；分类榜/民办榜的名次保存于 `soft_subject_rank_2025`，并由 `soft_ranking_type` 标明榜单类型。
- `enrollment_2025` 主要是公开的 **2025 年本科普通批招生计划**，不是严格意义上的 2025 级实际报到新生人数；未找到可靠校级数字的记录留空。
- 招生计划通常不包含提前批、艺术类、专科批，也可能与最终录取和报到人数存在差异。
- 不同软科榜单之间不能直接横向比较，例如公办主榜第 100 名和民办主榜第 100 名不是同一评价序列。

## 来源

- 软科 2025 中国大学排名：https://www.shanghairanking.cn/rankings/bcur/2025
- 重庆市教育考试院：https://www.cqksy.cn/
- 2025 重庆招生计划汇总：https://www.gk100.com/read_3272208.htm
- 2025 年重庆各大学招生计划：https://cq.bendibao.com/edu/2025623/154655.shtm
- 2025 重庆高考录取情况：https://www.toutiao.com/article/7586655884802114058/

如需回归分析，建议把 `enrollment_count_type` 作为筛选条件，只使用同一口径的数据；不要把空值填成 0。
