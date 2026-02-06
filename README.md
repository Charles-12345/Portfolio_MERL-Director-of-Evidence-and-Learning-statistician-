# Portfolio_MERL-Director-of-Evidence-and-Learning-statistician-

# Tiko Evidence & Learning Portfolio  
**Director of Evidence and Learning | MERL Systems | Cost-Effectiveness | Digital Health Data**

## Overview

This repository presents an end-to-end **Evidence, Measurement, Evaluation, and Learning (EMEL)** system designed for adolescent girls and young women (AGYW) programmes addressing **unintended pregnancy, HIV, and sexual and gender-based violence (SGBV)**.

The portfolio mirrors the operational and strategic evidence needs of **Tiko’s integrated service delivery model**, demonstrating how digital data systems, rigorous analytics, and structured learning processes can be embedded into programme delivery, government collaboration, and donor accountability.

The repository showcases:
- Harmonized MEL framework aligned to Theory of Change and donor standards  
- Digital data collection using KoboToolbox (XLSForms)  
- Secure data pipelines using Python, SQL, and API integrations  
- Excel-based quality assurance workflows for field and partner use  
- Power BI dashboards for decision-making and performance management  
- Cost-effectiveness and ROI analysis for integrated service models  
- Learning products, research protocols, and government-style data triangulation  

All datasets are **synthetically generated** and privacy-safe.

---

## Portfolio Architecture

**Data Flow:**  
KoboToolbox → API Extraction → Data Quality & Transformation → SQL Data Model → Analytics → Dashboards → Learning Outputs

AGYW Intake & Referral
↓
Service Verification (Clinics)
↓
Client Feedback & Quality Assessments
↓
Python ETL + Validation
↓
SQL Analytical Views
↓
Power BI Dashboards & Learning Briefs


---

## Repository Structure (Executive Summary)

- **1_mel_framework/**  
  Harmonized MEL plan, Theory of Change, indicator registry, and reporting calendar.

- **2_data_collection_kobo/**  
  XLSForms covering intake, referrals, service verification, feedback, clinic quality, and safeguarding.

- **3_simulated_data/**  
  Realistic synthetic datasets structured to mirror digital health and referral ecosystems.

- **4_sql_data_model/**  
  Normalized schemas, analytical views, and data quality checks.

- **5_python_analytics/**  
  API extraction, transformation, indicator computation, cost-effectiveness, and outcome analysis.

- **6_excel_workflows/**  
  Power Query–based cleaning templates and QA summaries for operational teams.

- **7_powerbi_dashboards/**  
  Executive dashboards for outcomes, partner performance, user experience, and data quality.

- **8_learning_products/**  
  Evidence briefs, research protocols, ethics notes, and learning documentation.

- **9_government_collab_simulation/**  
  DHIS2-style indicator comparisons, joint review packs, and data quality improvement plans.

---

## Key Competencies Demonstrated

- Strategic MEL leadership and framework design  
- Advanced quantitative and qualitative analysis  
- Cost-effectiveness and ROI modelling  
- Digital health data systems and APIs  
- Government and DHIS2-style data alignment  
- Ethical research design and safeguarding-aware systems  
- Translation of evidence into decisions and learning  

---

## Ethics, Safeguarding, and Data Protection

- All data are synthetic and de-identified  
- Forms include consent logic, safeguarding triggers, and minimal data capture  
- Design aligns with principles of **Do No Harm**, ethical research, and client confidentiality  
- Repository includes mock IRB and ethics documentation for demonstration purposes  

---

## Intended Audience

This portfolio is designed for:
- Senior leadership and boards  
- Ministries of Health and national data teams  
- Donors and technical partners  
- MEL, research, and digital health specialists  

---

*This repository demonstrates not just analytical capability, but the leadership, systems thinking, and evidence culture required to operate at continental scale.*
2️⃣ theory_of_change.md
# Theory of Change  
**Integrated Digital Health Ecosystem for Adolescent Girls and Young Women**

## Impact (Long-Term)

Improved health, autonomy, and resilience of adolescent girls and young women through:
- Reduced unintended pregnancy  
- Reduced HIV incidence  
- Reduced exposure to and impact of sexual and gender-based violence  

---

## Problem Statement

AGYW in Sub-Saharan Africa face a **Triple Threat** driven by:
- Structural barriers to accessing youth-friendly SRH services  
- Fragmented service delivery and referral systems  
- Stigma, cost, and lack of trust in health systems  
- Weak feedback loops and limited use of evidence for improvement  

---

## Core Assumptions

- Integrated service delivery increases uptake and continuity of care  
- Incentives and peer accompaniment reduce stigma and access barriers  
- Real-time data and feedback improve service quality and accountability  
- Evidence embedded into decision-making strengthens system performance  

---

## Inputs

- Trained peer mobilisers and community-based organizations  
- Digital referral and verification platform  
- Network of public and private health facilities  
- Incentive mechanisms (e.g., Tiko Miles)  
- MEL systems, analytics, and learning capacity  

---

## Activities

1. AGYW enrollment and risk-informed intake  
2. Digital referrals for FP, HIV, and SGBV services  
3. Service delivery and verification at clinics  
4. Incentive redemption and partner compensation  
5. Client feedback and experience monitoring  
6. Data quality assurance and analytics  
7. Learning, adaptation, and government engagement  

---

## Outputs

- Verified service uptake records  
- Client feedback datasets  
- Clinic quality assessments  
- Partner performance metrics  
- Cost and efficiency metrics  

---

## Outcomes (Medium-Term)

- Increased uptake of FP and HIV services  
- Improved identification and referral for SGBV cases  
- Improved client experience and reduced stigma  
- Improved partner performance and accountability  
- Strengthened use of data in programme management  

---

## Pathway to Impact

If AGYW receive **trusted referrals**, **verified services**, and **positive care experiences**,  
and if partners are **incentivized and supported through evidence**,  
then health outcomes improve and systems become more responsive and resilient.
3️⃣ mel_plan.md (with full indicator logic)
# Monitoring, Evaluation, and Learning (MEL) Plan

## Purpose

This MEL Plan operationalizes the Theory of Change by defining:
- What is measured  
- How it is measured  
- How evidence is used for decisions, learning, and accountability  

The plan aligns with donor requirements, government systems, and ethical standards.

---

## MEL Objectives

1. Measure uptake and continuity of integrated FP, HIV, and SGBV services  
2. Assess quality, experience, and safety of service delivery  
3. Monitor partner performance and efficiency  
4. Generate evidence on cost-effectiveness and value for money  
5. Embed learning into programme adaptation and scale  

---

## Results Framework

| Level | Focus |
|------|------|
| Impact | Health and resilience outcomes |
| Outcomes | Service uptake, experience, quality |
| Outputs | Referrals, verifications, feedback |
| Processes | Data quality, timeliness, coverage |

---

## Indicator Types

- Output indicators  
- Outcome indicators  
- Experience & feedback indicators  
- Cost-effectiveness indicators  
- Data quality indicators  

---

## Data Sources

- KoboToolbox digital forms  
- SQL analytical database  
- Client feedback surveys  
- Clinic quality assessments  
- Cost and financial tracking datasets  

---

## Disaggregation Standards

All individual-level indicators are disaggregated by:
- Age group (10–14, 15–19, 20–24)  
- Geography (country, district)  
- Service type (FP, HIV, SGBV)  
- Partner type (CBO, clinic)  

---

## Learning & Use

- Monthly programme reviews  
- Quarterly learning briefs  
- Annual evidence synthesis  
- Joint data review meetings with Ministries of Health  

---

## Ethics & Data Protection

- Informed consent embedded in intake forms  
- Minimal data capture for sensitive topics  
- Aggregation rules for SGBV reporting  
- Secure access and role-based data use  
4️⃣ Indicator Reference Sheet (Layout + Sample Entries)
Use this structure in Excel or CSV (indicator_reference_sheet.xlsx).

Column Layout (Authoritative Registry)
Column Name	Description
Indicator_ID	Unique code (e.g. OUT_01)
Indicator_Name	Short descriptive title
Indicator_Type	Output / Outcome / Experience / Cost
Description	Full definition
Numerator	What is counted
Denominator	Reference population
Calculation_Method	Formula
Unit	%, count, ratio
Disaggregation	Age, geography, service
Data_Source	Kobo form / SQL view
Collection_Frequency	Monthly / Quarterly
Responsible_Team	MEL / Research
Data_Quality_Checks	Key validations
Use_for_Decision_Making	How indicator is used
Reporting_Level	Internal / Donor / Government
Ethical_Notes	Sensitivity considerations
Sample Populated Indicators
Indicator_ID	Indicator_Name	Type
OUT_01	Verified FP Service Uptake Rate	Outcome
Definition:
Percentage of enrolled AGYW who completed and verified a family planning service.

Numerator: Number of AGYW with verified FP service

Denominator: Number of AGYW enrolled and referred for FP

Calculation: (Numerator ÷ Denominator) × 100

Disaggregation: Age group, district, clinic

Source: Referral & Service Verification Form

Frequency: Monthly

Use: Programme performance, donor reporting

Indicator_ID	Indicator_Name	Type
EXP_02	Stigma-Free Care Score	Experience
Definition:
Average score measuring perceived stigma-free treatment during service delivery.

Numerator: Sum of stigma-free scores

Denominator: Number of feedback respondents

Unit: Mean score (1–5)

Source: Client Feedback Survey

Use: Quality improvement, partner support

Indicator_ID	Indicator_Name	Type
CEA_01	Cost per Verified Integrated Service	Cost
Definition:
Average programme cost per AGYW receiving at least one verified FP, HIV, or SGBV service.

Calculation: Total programme cost ÷ number of AGYW with ≥1 verified service

Source: Financial tracking + service verification data

Use: Cost-effectiveness analysis, ROI discussions
