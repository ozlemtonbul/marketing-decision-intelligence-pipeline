## 📊 Live Interactive Dashboard
| | Link |
|--|--| Marketing Decision Intelligence · ETL Pipeline · What-If Simulation Dashboard | [View Dashboard →](https://ozlemtonbul.com/dashboards/marketing_dashboard.html) |

# Marketing Decision Intelligence Pipeline

## Executive Summary
This project is a marketing decision intelligence system designed to transform fragmented
marketing data into structured, data-driven business decisions.

Developed during a US-based analytics initiative, the system demonstrates how customer
behavior, campaign performance, and marketing data can be unified into a single decision
framework. Due to data privacy constraints, publicly available Kaggle datasets were used to
replicate real-world marketing scenarios while preserving the full analytical methodology and
system design.The pipeline goes beyond traditional analytics by combining data processing, segmentation,
and decision logic to generate actionable recommendations for marketing optimization.

## Business Problem
Marketing teams often operate with disconnected datasets across campaigns, customers,
and channels. While large volumes of data are available, decision-making remains manual,
reactive, and inefficient.

Key challenges included:
- Lack of a unified system connecting customer behavior and campaign performance
- Time-consuming manual reporting and analysis
- No structured prioritization of marketing efforts
- Limited ability to identify high-value customer segments
- Decisions driven by intuition rather than measurable impact

As a result, marketing resources were not optimally allocated, and high-impact opportunities
were frequently overlooked.

## Solution
I designed and implemented a structured marketing intelligence pipeline that converts raw
data into actionable decision outputs.

The system includes:
- Data processing and transformation of marketing datasets
- Feature engineering focused on business metrics such as conversion rate, customer
value, and engagement
- Customer segmentation based on behavioral and value-driven patterns
- Campaign performance evaluation across multiple dimensions
- A decision engine that prioritizes actions based on expected business impact

This transforms marketing analytics from descriptive reporting into a decision-support
system.

## System Architecture

### Data Layer
- Large-scale marketing datasets (Kaggle-based simulation)
- Customer and campaign interaction data

### Feature Engineering
- Conversion rate
- Customer lifetime value (CLV) proxies
- Engagement and response metrics

### Analysis Layer
- Customer segmentation
- Campaign and channel performance analysis

### Decision Engine
- Rule-based prioritization framework
- Identification of high-value segments and campaigns
- Structured recommendation outputs

## Results & Business Impact
The system demonstrates measurable improvements in marketing decision-making:
- Improved decision efficiency by transforming raw data into structured insights
- Reduced manual analysis workload through automated data processing
- Enabled prioritization of high-value customer segments and campaigns
- Increased visibility into marketing performance across multiple dimensions
- Established a scalable framework for data-driven marketing decisions

### Additional Impact
- Reduced manual analysis effort by over 40 hours per month
- Enabled prioritization of top-performing customer segments
- Improved decision-making speed through structured outputs

This approach shifts marketing operations from reactive reporting to proactive,
intelligence-driven decision-making.

## Dashboard & Insights
The pipeline is designed to feed a business intelligence dashboard that visualizes:
- Campaign performance overview
- Customer segmentation insights
- Conversion and revenue trends
- Channel-level performance comparison
- Priority segments and recommended actions

## Technical Stack
- Python
- Pandas, NumPy
- Data analysis and segmentation techniques
- Business rule-based decision systems
- Power BI

## How to Run

```bash
pip install -r requirements.txt
python src/marketing_decision_intelligence.py
```

## Author
Ozlem Tonbul
