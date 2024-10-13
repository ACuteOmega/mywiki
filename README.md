# mywiki
Mywiki is start.

公式是：
\[ Q = K_v \times \sqrt{\frac{ΔP}{ρ}} \]

对于压差 \(ΔP = 1\) bar 和水的密度 \(ρ = 1000\) kg/m³：

1. 先计算通径为17.5mm的最大流量系数 \(K_{vs}\)：
\[ K_{vs} \approx \frac{\pi \cdot (d/2)^2}{4} \times 0.85 \]
\[ K_{vs} \approx \frac{\pi \cdot (17.5/2)^2}{4} \times 0.85 \approx 1.96 \]

2. 然后计算流量：
\[ Q = K_v \times \sqrt{\frac{1}{1000}} \]

在 Excel 中，你可以这样表达：

- \( K_{vs} \) 在 A1 单元格（即 1.96）
- \( ΔP \) 在 B1 单元格（即 1）
- \( ρ \) 在 C1 单元格（即 1000）