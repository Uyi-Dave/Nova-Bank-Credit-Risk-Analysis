# Nova Bank Credit Risk Analysis  

**Onyx Data Challenge - September 2025**  

---

## Project Background  

As a Credit Risk Analyst at Nova Bank, I have conducted a comprehensive analysis of our loan portfolio spanning the USA, UK, and Canada to address critical strategic questions around lending optimization and risk management. This analysis directly responds to Nova Bank's challenge of balancing fair, accessible lending while protecting against unnecessary financial exposure.  

### Stakeholder Delivery:  
- **Risk Management Committee**: Strategic insights on portfolio risk distribution and concentration  
- **Lending Operations Team**: Actionable recommendations for policy adjustments and approval criteria  
- **Executive Leadership**: High-level portfolio performance metrics and business impact analysis  
- **Product Development Team**: Data-driven guidance for loan product optimization  

### Project Goals:  
- **Risk Optimization**: Identify optimal risk-return balance to maximize profitability while maintaining prudent lending standards  
- **Segment Identification**: Develop clear borrower segmentation to enable targeted lending strategies  
- **Early Warning System**: Establish predictive indicators for proactive risk management  
- **Geographic Strategy**: Guide market expansion and resource allocation across USA, UK, and Canada  
- **Policy Enhancement**: Provide evidence-based recommendations for lending criteria refinement  

### Data Structure Overview  
The analysis leverages a comprehensive dataset of **32,581 loans** with multi-dimensional risk factors:  
- **Geographic Coverage**: USA, UK, Canada with city and state-level granularity  
- **Borrower Demographics**: Age, marital status, employment type, education level, home ownership  
- **Financial Metrics**: Annual income, debt-to-income ratios, loan-to-income ratios, credit utilization  
- **Credit History**: Credit history length, prior defaults, number of open accounts, delinquency records  
- **Loan Characteristics**: Purpose, amount, grade (A-G), term length, interest rates  
- **Outcome Variable**: Binary default indicator with **21.82% overall default rate**  

---

## Executive Summary  

**Portfolio Health Check**: Nova Bank maintains a well-balanced risk profile with critical optimization opportunities identified.  

### Key Performance Indicators:  
- **Total Loan Portfolio**: 32,581 loans  
- **Overall Default Rate**: 21.82% (industry benchmark: 18-25%)  
- **Mean Loan Amount**: $9.59K with optimal loan-to-income ratio of 0.17  
- **Mean Annual Income**: $66.07K across all borrowers  
- **Geographic Distribution**: Consistent risk across all three markets (21.73%-21.86%)  

### Strategic Findings:  
1. **Risk Segmentation Success**: Our current model effectively identifies risk, with 21.82% classified as risky and 78.18% as safe - an optimal distribution for balanced growth.  
2. **Grade G Crisis**: Loan Grade G shows catastrophic 98.44% default rate, indicating immediate need for policy revision or product discontinuation.  
3. **Debt-to-Income Danger Zone**: Borrowers with DTI >0.8 show 93.33% default rate, representing clear underwriting failure.  
4. **Employment Risk Hierarchy**: Unemployed borrowers present 22.67% default rate while self-employed show surprisingly similar risk (22.49%) to full-time employees (21.63%).  
5. **Geographic Stability**: Remarkably consistent default rates across countries suggest effective risk management processes are transferable globally.  

**Immediate Action Required**: Grade G lending policies and high DTI approvals need urgent review to prevent further losses.  

---

## Insights Deep-Dive  

### Borrower Risk Analysis  

**Age and Life Stage Impact**:  
Our analysis reveals a compelling U-shaped risk curve by age group:  
- **Highest Risk**: Ages 61-70 (29.82% default rate) - likely due to fixed income constraints and health-related financial stress  
- **Moderate Risk**: Ages 20-30 (22.21%) - typical of early career income volatility  
- **Sweet Spot**: Ages 41-50 (20.40%) - peak earning years with established financial stability  

**Housing Status as Risk Predictor**:  
Home ownership strongly correlates with repayment reliability:  
- **Renters**: 31.57% default rate (highest risk segment)  
- **Mortgage Holders**: 12.57% default rate (most reliable segment)  
- **Homeowners**: 7.47% default rate (premium borrower segment)  

*Strategic Insight*: Renters represent our highest-volume, highest-risk segment requiring enhanced screening or risk-adjusted pricing.  

**Employment Stability Analysis**:  
Contrary to conventional wisdom, employment type shows minimal risk differentiation:  
- **Unemployed**: 22.67% (expected high risk)  
- **Self-employed**: 22.49% (surprisingly similar to employed)  
- **Part-time**: 21.63% (comparable to full-time)  
- **Full-time**: 21.57% (baseline risk)  

*Strategic Insight*: Employment type alone is insufficient for risk assessment; income stability and debt service capacity are more predictive.  

---

### Loan Characteristics and Repayment  

**Loan Grade Performance Analysis**:  
Our loan grading system shows clear risk stratification with one critical outlier:  
- **Grade A**: 9.96% default rate (premium segment)  
- **Grade B**: 16.28% default rate (good performance)  
- **Grade C-F**: Progressive increase from 20.73% to 70.54%  
- **Grade G**: 98.44% default rate (systematic failure)  

**Loan Purpose Risk Hierarchy**:  
Significant variations in default rates by loan purpose:  
1. Debt Consolidation: 28.59% (highest risk - indicates existing financial stress)  
2. Medical: 26.70% (emergency-driven, often unplanned)  
3. Home Improvement: 26.10% (discretionary spending risk)  
4. Personal: 19.89% (moderate risk)  
5. Education: 17.22% (investment in future earning capacity)  
6. Venture: 14.31% (lowest risk - business investment mindset)  

**Loan-to-Income Ratio Critical Thresholds**:  
Clear risk escalation pattern identified:  
- 0.00-0.10: 11.21% default rate (conservative lending)  
- 0.20-0.30: 22.09% default rate (balanced risk)  
- 0.70-0.80: 87.50% default rate (danger zone)  

*Strategic Insight*: LTI ratios above 0.5 should trigger enhanced due diligence or decline.  

---

### Credit History and Behavior  

**Prior Default Impact**:  
- No Prior Defaults: 18.39% current default rate  
- With Prior Defaults: 37.81% current default rate (2.06x higher risk)  

**Credit History Length Paradox**:  
Longer credit history correlates with higher default rates:  
- 0-10 years: 20.65% default rate  
- 25-30 years: 28.71% default rate  

*Hypothesis*: Longer credit histories may indicate older borrowers facing age-related financial pressures or accumulated financial obligations.  

**Credit Utilization Sweet Spot**:  
- 0.00-0.10: 21.84% default rate (potentially limited credit access)  
- 0.20-0.30: 21.11% default rate (optimal usage)  
- 0.90-1.00: 22.33% default rate (maxed out credit)  

**Open Accounts Risk Pattern**:  
- Moderate number of open accounts (7-8) shows highest risk at 24.13% default rate  
- Very low (1-2 accounts) and high (14-15 accounts) show better performance (~21%)  

---

### Geographic Risk Distribution  

**Consistent International Performance**:  
- USA: 21.86%  
- UK: 21.73%  
- Canada: 21.86%  

*Strategic Insight*: Our risk management framework translates effectively across different regulatory and economic environments.  

**City-Level Risk Variations**:  
- Vancouver: 24.19% (highest risk)  
- Dallas: 23.59%  
- Edinburgh: 23.46%  
- Los Angeles: 22.85%  
- Glasgow: 21.56% (lowest risk)  

*Note*: Limited variation suggests consistent urban economic conditions across our markets.  

---

### Segmentation – Safe vs Risky Groups  

**Portfolio Balance Achievement**:  
- Risky Segment: 21.82% (7,108 loans)  
- Safe Segment: 78.18% (25,473 loans)  

**Risk-Adjusted Pricing Validation**:  
- Safe Group: Higher income ($70.8K vs $49.1K), lower loan amounts ($9.2K vs $10.9K), better rates (6.1% vs 8.13%)  
- Risky Group: Lower income, higher loan amounts, risk-adjusted pricing implemented  

**Segmentation Effectiveness**:  
The 3.6:1 safe-to-risky ratio indicates disciplined risk management while maintaining growth opportunities in higher-yield segments.  

---

## Recommendations  

### Immediate Actions (0-30 days)  
1. **Grade G Emergency Response**  
   - Action: Immediately suspend all Grade G loan approvals  
   - Owner: Risk Management Committee  
   - Impact: Prevent significant additional losses from highest-risk segment  

2. **Debt-to-Income Policy Tightening**  
   - Action: Implement hard cap at 0.6 DTI ratio for all loan approvals  
   - Owner: Underwriting Team  
   - Impact: Reduce portfolio risk by eliminating extreme outliers  

---

### Short-term Optimizations (1-6 months)  
3. **Enhanced Renter Screening Protocol**  
   - Action: Implement additional verification requirements for renters including landlord references, rental payment history, and increased income documentation  
   - Owner: Lending Operations Team  
   - Impact: Improve largest risk segment performance  

4. **Loan Purpose Risk-Adjusted Pricing**  
   - Action: Implement purpose-based interest rate adjustments (+2% for debt consolidation, -1% for education/venture)  
   - Owner: Product Development Team  
   - Impact: Better align pricing with risk, improve portfolio profitability  

5. **Age-Targeted Products**  
   - Action: Develop specialized senior lending products with income verification, co-signer options, or reduced terms  
   - Owner: Product Development Team  
   - Impact: Serve underbanked seniors while managing risk  

---

### Strategic Initiatives (6-12 months)  
6. **Geographic Expansion Strategy**  
   - Action: Leverage successful risk management framework for expansion into additional English-speaking markets (Australia, Ireland)  
   - Owner: Business Development Team  
   - Impact: Geographic diversification with proven risk management  

7. **Credit Utilization-Based Pricing**  
   - Action: Implement credit utilization ratio as a pricing factor in risk assessment models  
   - Owner: Risk Analytics Team  
   - Impact: More nuanced risk pricing based on credit behavior patterns  

---

### Long-term Transformations (12+ months)  
8. **Predictive Early Warning System**  
   - Action: Develop machine learning model incorporating all identified risk factors for real-time risk scoring  
   - Owner: Data Science Team  
   - Impact: Proactive risk management and reduced default rates  

9. **Portfolio Rebalancing Strategy**  
   - Action: Gradually shift toward 25% risky / 75% safe ratio to optimize risk-adjusted returns  
   - Owner: Portfolio Management Team  
   - Impact: Enhanced profitability while maintaining risk discipline  

---

*Analysis completed by* **Uyi Godwin Omokaro, Credit Risk Analyst, Nova Bank**  
*Report Date*: 24th September, 2025  
*Onyx Data Challenge - September 2025*  

Onyx Data Challenge - September 2025

