[English](#english) | [中文](#中文)

<a name="中文"></a>
# 贵出如粪土，贱取如珠玉

这个仓库包含了价值投资需要的基本工具。

主要解决如何在嘈杂的市场中建立过滤机制，进行明智的风险选择。

目前的过滤指标是ROIC与PB。计算工具是未来现金流折现。

## Quick Start
```bash
chmod +x dcf_valuation.sh ./dcf_valuation.sh
```

Enter the required inputs when prompted:
- Earnings Per Share (EPS)
- Book Value per share
- 1-Year US Treasury Yield (%)

It will output:
- EPS输入的每股收益: 5.25
- 每股净资产: 45.30
- 国债收益率: 4.5%
- 年金现值因子: 16.2889
- 折现后的DCF价值: 130.82

```python
rc.plot_roic_time_series("OXY", 4)
```
It will output four year rolling average roic

<a name="english"></a>
# JiaGuoSuiShang

This repo builds sharp swiss tools to do Charlie and Buffet style value investing.
