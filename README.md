# Tiko Evidence & Learning Portfolio

**Integrated Monitoring, Evaluation, Research & Learning (MERL) System for Adolescent Sexual & Reproductive Health**

[![Evidence-Based](https://img.shields.io/badge/approach-evidence--based-blue)](https://github.com)
[![Digital Health](https://img.shields.io/badge/sector-digital%20health-green)](https://github.com)
[![MERL Systems](https://img.shields.io/badge/focus-MERL%20systems-orange)](https://github.com)

---

## 🎯 Overview

This portfolio demonstrates an **end-to-end Evidence, Measurement, Evaluation, and Learning (EMEL) system** designed for adolescent girls and young women (AGYW) programmes addressing:

- Unintended pregnancy prevention
- HIV prevention and care
- Sexual and gender-based violence (SGBV) response

The system mirrors operational and strategic evidence needs for integrated service delivery models, showcasing how digital data systems, rigorous analytics, and structured learning processes can be embedded into programme delivery, government collaboration, and donor accountability.

### Key Highlights

- ✅ Harmonized MEL framework aligned to Theory of Change and donor standards
- ✅ Digital data collection using KoboToolbox (XLSForms)
- ✅ Secure data pipelines using Python, SQL, and API integrations
- ✅ Excel-based quality assurance workflows for field teams
- ✅ Power BI dashboards for decision-making and performance management
- ✅ Cost-effectiveness and ROI analysis
- ✅ Learning products and research protocols
- ✅ Government-style data triangulation and DHIS2 alignment

> **Note:** All datasets are synthetically generated and privacy-safe.

---

## 🏗️ System Architecture

### Data Flow Pipeline

```
KoboToolbox Forms
       ↓
API Extraction (Python)
       ↓
Data Quality & Transformation
       ↓
SQL Data Model
       ↓
Analytics & Indicators
       ↓
Power BI Dashboards → Learning Outputs
```

### Service Journey Flow

```
AGYW Intake & Referral
       ↓
Service Verification (Clinics)
       ↓
Client Feedback & Quality Assessments
       ↓
Data Integration & Analysis
       ↓
Evidence → Decisions → Learning
```

---

## 📂 Repository Structure

```
tiko-evidence-portfolio/
│
├── 1_mel_framework/
│   ├── theory_of_change.md
│   ├── mel_plan.md
│   ├── indicator_reference_sheet.xlsx
│   └── reporting_calendar.xlsx
│
├── 2_data_collection_kobo/
│   ├── agyw_intake_form.xlsx
│   ├── referral_verification_form.xlsx
│   ├── client_feedback_survey.xlsx
│   ├── clinic_quality_assessment.xlsx
│   └── safeguarding_incident_form.xlsx
│
├── 3_simulated_data/
│   ├── agyw_enrollments.csv
│   ├── service_verifications.csv
│   ├── client_feedback.csv
│   └── data_dictionary.md
│
├── 4_sql_data_model/
│   ├── schema_design.sql
│   ├── analytical_views.sql
│   └── data_quality_checks.sql
│
├── 5_python_analytics/
│   ├── api_extraction.py
│   ├── data_transformation.py
│   ├── indicator_computation.py
│   └── cost_effectiveness_analysis.py
│
├── 6_excel_workflows/
│   ├── data_cleaning_template.xlsx
│   ├── qa_summary_dashboard.xlsx
│   └── partner_performance_tracker.xlsx
│
├── 7_powerbi_dashboards/
│   ├── executive_dashboard.pbix
│   ├── partner_performance.pbix
│   └── data_quality_monitoring.pbix
│
├── 8_learning_products/
│   ├── evidence_briefs/
│   ├── research_protocols/
│   └── ethics_documentation/
│
└── 9_government_collaboration/
    ├── dhis2_indicator_mapping.xlsx
    ├── joint_review_pack.pptx
    └── data_quality_improvement_plan.md
```

---

## 💡 Core Competencies Demonstrated

### Strategic MEL Leadership
- Theory of Change development and operationalization
- Harmonized indicator frameworks aligned to donor and government standards
- Integration of evidence into programme strategy and adaptation

### Advanced Analytics & Research
- Quantitative and qualitative analysis
- Cost-effectiveness and ROI modeling
- Outcome evaluation and attribution analysis
- Ethical research design with safeguarding protocols

### Digital Health Systems
- KoboToolbox form design and deployment
- API-based data extraction and automation
- SQL database design and optimization
- Power BI dashboard development

### Government & Partner Collaboration
- DHIS2 system alignment and indicator mapping
- Joint data review processes
- Data quality improvement frameworks
- Evidence translation for policy influence

---

## 🔍 Theory of Change

### The Triple Threat

AGYW in Sub-Saharan Africa face intersecting challenges:
- Structural barriers to youth-friendly SRH services
- Fragmented service delivery and referral systems
- Stigma, cost, and limited trust in health systems
- Weak feedback loops for quality improvement

### Our Approach

**If** AGYW receive trusted referrals, verified services, and positive care experiences,  
**And if** partners are incentivized and supported through evidence,  
**Then** health outcomes improve and systems become more responsive and resilient.

### Impact Goals

- Reduced unintended pregnancy
- Reduced HIV incidence
- Reduced exposure to and impact of SGBV
- Improved health autonomy and resilience

---

## 📊 Sample Indicators

### Outcome Indicators

**OUT_01: Verified FP Service Uptake Rate**
- **Definition:** Percentage of enrolled AGYW who completed and verified a family planning service
- **Calculation:** (AGYW with verified FP service ÷ AGYW enrolled and referred for FP) × 100
- **Disaggregation:** Age group, district, clinic
- **Use:** Programme performance, donor reporting

### Experience Indicators

**EXP_02: Stigma-Free Care Score**
- **Definition:** Average score measuring perceived stigma-free treatment during service delivery
- **Scale:** 1–5 (higher is better)
- **Source:** Client Feedback Survey
- **Use:** Quality improvement, partner support

### Cost-Effectiveness Indicators

**CEA_01: Cost per Verified Integrated Service**
- **Definition:** Average programme cost per AGYW receiving at least one verified service
- **Calculation:** Total programme cost ÷ Number of AGYW with ≥1 verified service
- **Use:** ROI analysis, value-for-money assessments

---

## 🛡️ Ethics, Safeguarding & Data Protection

This portfolio adheres to the highest standards of research ethics and data protection:

- ✅ All data are **synthetically generated** and de-identified
- ✅ Forms include consent logic and safeguarding triggers
- ✅ Minimal data capture for sensitive topics (SGBV)
- ✅ Aggregation rules protect individual privacy
- ✅ Design aligns with **Do No Harm** principles
- ✅ Mock IRB and ethics documentation included for demonstration

### Safeguarding Features
- Real-time incident flagging
- Secure referral pathways
- Role-based data access controls
- Confidentiality protocols embedded in workflows

---

## 🎓 Learning & Adaptation

### Learning Cycle

```
Programme Delivery
       ↓
Data Collection
       ↓
Analysis & Insights
       ↓
Learning Briefs
       ↓
Adaptation & Decision-Making
       ↓
(Return to Programme Delivery)
```

### Learning Products

- Monthly programme reviews
- Quarterly evidence briefs
- Annual evidence synthesis
- Joint data review meetings with Ministries of Health
- Research papers and case studies

---

## 👥 Intended Audience

This portfolio is designed for:

- **Senior Leadership & Boards:** Strategic decision-making and governance
- **Ministries of Health:** Government collaboration and system strengthening
- **Donors & Technical Partners:** Accountability and evidence of impact
- **MEL Specialists:** Methodological approaches and best practices
- **Digital Health Practitioners:** Technical implementation and innovation

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- SQL database (PostgreSQL/MySQL)
- Power BI Desktop
- Excel with Power Query
- KoboToolbox account (for form deployment)

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/tiko-evidence-portfolio.git
   cd tiko-evidence-portfolio
   ```

2. **Install Python dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up the database**
   ```bash
   psql -U your_user -d your_database -f 4_sql_data_model/schema_design.sql
   ```

4. **Load sample data**
   ```bash
   python 5_python_analytics/data_transformation.py
   ```

5. **Open Power BI dashboards**
   - Navigate to `7_powerbi_dashboards/`
   - Open `.pbix` files in Power BI Desktop

---

## 📈 Use Cases

### For Programme Managers
- Real-time performance monitoring
- Partner accountability tracking
- Service quality improvement

### For MEL Teams
- Indicator computation automation
- Data quality assurance workflows
- Learning brief generation

### For Researchers
- Outcome evaluation frameworks
- Cost-effectiveness analysis
- Mixed-methods integration

### For Government Partners
- DHIS2 data alignment
- Joint review preparation
- System strengthening insights

---

## 🤝 Contributing

This is a demonstration portfolio showcasing professional MERL capabilities. While not currently accepting external contributions, feedback and questions are welcome.

---

## 📄 License

This portfolio is for demonstration purposes. All data are synthetic and do not represent real individuals or organizations.

---

## 📬 Contact

**Portfolio Owner:** [Charles Daniel Apollo]  
**Role:** Director of Evidence and Learning  
**Expertise:** MERL Systems | Cost-Effectiveness | Digital Health Data  

[![LinkedIn]https://www.linkedin.com/in/charles-daniel-apollo-1551b2b3/
[![Email](https://img.shields.io/badge/Email-Contact-red)](mailto:charlesdanieldoka@gmail.com)

---

## 🌟 Acknowledgments

This portfolio demonstrates not just analytical capability, but the **leadership, systems thinking, and evidence culture** required to operate at continental scale.

It reflects the integration of:
- Strategic vision and operational rigor
- Technical excellence and ethical practice
- Evidence generation and learning culture
- Digital innovation and human-centered design

---

*Building evidence systems that transform health outcomes for adolescent girls and young women across Sub-Saharan Africa.*
