# LSCSC Electronic Engineering Calculators
# LSCSC 电子工程工具集

[English Version](#english-version)
[中文版本](#chinese-version)

Website: [https://www.lscsc.com](https://www.lscsc.com)

---

## English Version

### Introduction
LSCSC Electronic Engineering Calculators is a comprehensive web-based calculator suite designed for electronic engineers, hobbyists, and students. It provides accurate calculations and analysis Calculators for various electronic components and circuits.

### Key Features
1. Component Calculators
   - Resistor Calculators
     * Color Code Calculator (4/5/6 bands)
     * SMD Code Converter
     * Series/Parallel Calculator
     * Power Rating Calculator
   
   - Capacitor Calculators
     * Value Converter (pF, nF, µF)
     * SMD Code Calculator
     * Charging/Discharging Calculator
     * Time Constant Calculator
   
   - Inductor Calculators
     * Air Core Calculator
     * Iron Core Calculator
     * Inductance Calculator

2. Thermal Analysis Calculators
   - Heat Transfer Calculator
   - Thermal Resistance Calculator
   - Cooling System Designer
   - Enclosure Temperature Calculator

3. Semiconductor Calculators
   - LED Calculator
   - Transistor Calculator
   - MOSFET Calculator
   - Thermal Analysis

### Core Formulas

1. Resistor Calculations
   - Series: Rtotal = R1 + R2 + R3 + ...
   - Parallel: 1/Rtotal = 1/R1 + 1/R2 + 1/R3 + ...
   - Power: P = I²R = V²/R = VI
2. Capacitor Calculations
   - Series: 1/Ctotal = 1/C1 + 1/C2 + 1/C3 + ...
   - Parallel: Ctotal = C1 + C2 + C3 + ...
   - Time Constant: τ = RC
   - Charging: V = V0(1 - e^(-t/RC))
   - Discharging: V = V0(e^(-t/RC))

1. Thermal Calculations
   - Heat Transfer: Q = k × A × (T1 - T2) / L
   - Thermal Resistance: θtotal = θjc + θcs + θsa
   - Temperature Rise: ΔT = P × θtotal

### Usage
1. Select the appropriate calculator from the navigation menu
2. Input the required parameters
3. Get instant results with detailed explanations
4. Reference the included formulas and theory sections

### Technical Details
- Built with Next.js 14
- Responsive design with Tailwind CSS
- Real-time calculations
- Mobile-friendly interface
- Professional engineering accuracy
- Regular updates with latest standards

---

## Chinese Version

### 简介
LSCSC 电子工程工具集是一个综合性的在线计算器套件，专为电子工程师、爱好者和学生设计。它提供各种电子元件和电路的精确计算和分析工具。

网址：[https://www.lscsc.com](https://www.lscsc.com)

### 主要功能
1. 元件计算器
   - 电阻工具
     * 色码计算器（4/5/6 环）
     * SMD 代码转换器
     * 串并联计算器
     * 功率计算器
   
   - 电容工具
     * 值转换器（pF、nF、µF）
     * SMD 代码计算器
     * 充放电计算器
     * 时间常数计算器
   
   - 电感工具
     * 空心线圈计算器
     * 铁芯计算器
     * 电感值计算器

2. 热分析工具
   - 热传导计算器
   - 热阻计算器
   - 散热系统设计器
   - 机箱温度计算器

3. 半导体工具
   - LED 计算器
   - 晶体管计算器
   - MOSFET 计算器
   - 热分析

### 核心计算公式

1. 电阻计算
   - 串联：Rtotal = R1 + R2 + R3 + ...
   - 并联：1/Rtotal = 1/R1 + 1/R2 + 1/R3 + ...
   - 功率：P = I²R = V²/R = VI


2. 电容计算
   - 串联：1/Ctotal = 1/C1 + 1/C2 + 1/C3 + ...
   - 并联：Ctotal = C1 + C2 + C3 + ...
   - 时间常数：τ = RC
   - 充电：V = V0(1 - e^(-t/RC))
   - 放电：V = V0(e^(-t/RC))

3. 热计算
   - 热传导：Q = k × A × (T1 - T2) / L
   - 热阻：θtotal = θjc + θcs + θsa
   - 温升：ΔT = P × θtotal


### 使用方法
1. 从导航菜单选择适当的计算器
2. 输入所需参数
3. 获取即时结果和详细解释
4. 参考包含的公式和理论部分

### 技术细节
- 使用 Next.js 14 构建
- 采用 Tailwind CSS 的响应式设计
- 实时计算
- 移动端友好界面
- 工程级计算精度
- 定期更新最新标准
