# 重庆高校 2026 软科排名与新生人数数据

已生成：`data/chongqing_university_2026_soft_ranking_enrollment.csv`

## 字段说明

- `soft_ranking_2026`：2026 软科榜单名次；主榜、民办高校榜、民办财经类榜的名次分别保留在 `soft_ranking_type` 中，不能直接横向比较。
- `new_student_count_2026`：优先填入公开可查的 2026 年在渝招生计划数；这不是最终实际报到新生数。没有可靠公开校级数据的学校留空，避免把估算值伪装成事实。
- `new_student_count_type`：说明该数值是招生计划还是实际新生人数。
- `data_status`：标记数据是否使用了招生计划作为代理值。

## 数据限制

截至数据抓取时，公开来源未提供所有高校统一口径的“2026 级实际新生人数”。因此 CSV 对多数学校留空，并对已公开的部分学校填入“2026 年在渝招生计划”作为代理值。实际录取、报到人数应以重庆市教育考试院及各高校招生就业处最终公布的数据替换。

## 来源

- 软科 2026 中国大学排名：https://www.shanghairanking.cn/rankings/bcur/2026
- 重庆市教育考试院：http://www.cqksy.cn/
- 重庆 2026 招生计划汇总（用于部分代理值）：https://www.gk100.com/read_19989758.htm
- 重庆市人民政府：79 所在渝高校 2026 年招生章程：https://www.cq.gov.cn/zwgk/zfxxgkzl/fdzdgknr/zdmsxx/jy/jy_ssqk/202606/t20260624_15774320.html

CSV 使用 UTF-8 编码，建议用支持 UTF-8 的工具打开。
