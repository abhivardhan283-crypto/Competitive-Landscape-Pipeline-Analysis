# Competitive-Landscape-Pipeline-Analysis

## 📊 **Project Overview**
A comprehensive competitive intelligence analysis of the Lung Cancer therapeutic market, built entirely in Jupyter Notebook with a consulting-style approach. This project demonstrates how to conduct professional pharmaceutical competitive intelligence using Python, SQL, and data visualization.

---

## 🎯 **Business Objective**
To analyze the competitive landscape of Lung Cancer therapies across approved drugs and pipeline candidates to identify:
- Market concentration and key players
- Pipeline intensity and development trends
- Strategic opportunities and competitive threats
- Actionable recommendations for market entry and portfolio strategy

---

## 🛠️ **Technical Stack**
| Component | Technology Used |
|-----------|-----------------|
| **Database** | SQLite (in-memory) |
| **Data Analysis** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Reporting** | Markdown cells, Excel export |
| **Environment** | Jupyter Notebook |

---

## 📁 **Project Structure**

### **1. Data Modeling (SQL-in-Jupyter)**
```sql
-- 4 Core Tables Created:
1. approved_drugs - 15 approved drugs with market performance
2. pipeline_drugs - 10 late-stage pipeline candidates  
3. company_profiles - 10 company competitive positions
4. therapy_class_analysis - 5 therapy class competitive dynamics
```

### **2. Key Analyses Performed**

#### **Market Concentration Analysis**
- Herfindahl-Hirschman Index (HHI) calculation
- Top 3/5 company market share analysis
- Competitive positioning classification

#### **Pipeline Intelligence**
- Phase III vs Phase II pipeline assessment
- Success probability analysis
- Competitive threat timeline

#### **Therapy Class Landscape**
- Current vs future competition mapping
- Growth trajectory (CAGR 2024-2030)
- White space opportunity scoring

#### **Patent Cliff Analysis**
- Immediate vs medium-term patent risks
- Revenue at risk quantification
- Strategic implications

---

## 📊 **Visualization Dashboard**

### **Main Executive Dashboard (9 Charts)**
1. **Market Share by Company** - Horizontal bar chart
2. **Pipeline Distribution by Stage** - Pie chart
3. **Therapy Class Competition** - Side-by-side bars
4. **Patent Cliff Timeline** - Bar chart
5. **Pipeline Strength by Position** - Dual-axis chart
6. **Opportunity Matrix** - Scatter plot (White Space vs Growth)
7. **Competitive Threat Timeline** - Line chart
8. **Market Evolution Heatmap** - Patent expiry impact
9. **Strategic Recommendations Matrix** - Color-coded table

### **Additional Insights Dashboard (4 Charts)**
10. **Company Innovation vs Market Share** - Bubble chart
11. **Therapy Class Growth Trajectory** - Color-coded bar chart
12. **Risk-Reward Profile** - Success rate vs potential sales
13. **Market Share Evolution Projection** - Stacked area chart

---

## 🚀 **Key Insights Generated**

### **Market Structure**
- **Market Concentration**: HHI 1421 (Unconcentrated)
- **Top 3 Control**: 51.7% of current market
- **Big Pharma Dominance**: Merck, AstraZeneca, Roche leading

### **Competitive Dynamics**
- **Pipeline Value**: $15.4B in projected sales
- **Phase III Dominance**: 80% of pipeline value in late-stage
- **Emerging Threats**: Daiichi Sankyo challenging with ADC platform

### **Strategic Opportunities**
- **White Space**: ADC therapies (Opportunity Score: 9/10)
- **High Growth**: Targeted therapies (12.5% CAGR)
- **Innovation Gap**: Limited competition in novel modalities

### **Risk Assessment**
- **Patent Cliff**: $3.2B at immediate risk (2024-2026)
- **2028 Inflection**: 52.3% of market expiring
- **Pipeline Attrition**: 55-70% average success rates


## 📈 **Key Metrics Summary**

| Metric | Value | Strategic Implication |
|--------|-------|----------------------|
| **Market Concentration (HHI)** | 1421 | Moderately competitive market |
| **Top 3 Market Share** | 51.7% | Big Pharma dominance |
| **Total Pipeline Value** | $15.4B | Significant future competition |
| **Phase III Pipeline Share** | 80% | Near-term launch threats |
| **Primary White Space** | ADC (9/10) | High investment opportunity |
| **Immediate Patent Risk** | $3.2B | Revenue protection needed |
| **Market CAGR Range** | 6.8-25.0% | Attractive growth across modalities |
