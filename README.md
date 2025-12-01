# 🏨 酒店预订数据分析项目

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-数据分析-orange)
![Plotly](https://img.shields.io/badge/Plotly-可视化-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

一个完整的数据分析项目，基于11.9万条酒店预订数据，运用数据分析和可视化技术，挖掘影响酒店业务的关键因素，为收益管理提供数据驱动的决策支持。

## 📊 项目演示


## 🎯 核心发现

1. **取消率分析**：识别整体取消率37.5%，量化业务风险
2. **季节性趋势**：发现10月为预订旺季，预订量比1月高出68%
3. **用户行为洞察**：揭示"提前预订时间越长，取消概率越高"的重要关联
4. **业务优化建议**：基于数据提出具体的收益管理策略

## 🛠️ 技术栈

- **数据处理**: Pandas, NumPy
- **数据可视化**: Plotly, Matplotlib
- **开发环境**: Jupyter Notebook
- **分析技术**: 探索性数据分析(EDA), 统计分析, 业务洞察

## 📁 项目结构

```
Hotel-Booking-Data-Analysis/
├── hotel_analysis.ipynb          # 完整分析代码
├── cleaned_hotel_data.csv        # 清洗后的数据
├── 00_项目总览.html              # 交互式报告总览
├── 01_预订取消分析.html          # 取消率分析图表
├── 02_月度预订趋势.html          # 季节性分析图表
├── 03_提前时间与取消率.html      # 用户行为分析图表
├── 04_客源国家分析.html          # 市场分析图表
└── README.md                     # 项目说明文档
```

## 🚀 快速开始

### 环境要求
```bash
Python 3.8+
pip install pandas plotly numpy jupyter
```

### 运行分析
```bash
# 克隆项目
git clone https://github.com/your-username/Hotel-Booking-Data-Analysis.git

# 进入目录
cd Hotel-Booking-Data-Analysis

# 安装依赖
pip install -r requirements.txt

# 运行分析
jupyter notebook hotel_analysis.ipynb
```

### 查看交互报告
直接使用浏览器打开 `00_项目总览.html` 文件查看完整分析报告。

## 📈 分析方法

### 数据清洗流程
1. 处理缺失值和异常值
2. 数据格式标准化
3. 特征工程和变量转换

### 分析维度
- **描述性分析**: 基础统计和分布分析
- **趋势分析**: 时间序列和季节性模式
- **关联分析**: 变量间关系挖掘
- **预测性分析**: 基于历史数据的模式识别

## 💡 业务价值

本项目演示了如何将原始数据转化为可执行的业务洞察：

- **收益管理**: 为酒店优化定价和预订策略提供数据支持
- **风险控制**: 识别高取消风险预订，改进运营流程
- **营销优化**: 为资源投放提供季节性和地域性指导
- **用户体验**: 基于用户行为数据优化服务流程

## 🤝 贡献指南

欢迎提出建议和改进！如果你有新的分析角度或可视化想法，请随时提交Issue或Pull Request。



**数据来源**: [Hotel Booking Demand Datasets](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand) | **最后更新**: 2024年1月