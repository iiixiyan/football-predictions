# 足球预测数据仓库

## 目录结构
- `beidan/` — 北京单场让球SPF预测（含模型因子评分、主选次选、置信度）
- `jingzu/` — 竞足比分预测（含模型比分 + 玄学双比分）
- `reports/` — 复盘报告

## 预测方法论
### 北单：HDM模型
`HDI = FormGap×0.25 + GoalDiffRate×0.20 + HomeAwayGap×0.20 + H2H×0.20 + MomentumCrv×0.15`

### 竞足：10套自创模型
IPI/FFM/PPM/HPM/TMM/CPM/LPM/GPM/RPM/UPM 按比赛类型匹配

## 数据源
- ESPN API（主流联赛战绩/O/U）
- Sofascore API（罗马尼亚/波兰/瑞士/挪威等小众联赛）
- 500彩票网（赔率参考）
