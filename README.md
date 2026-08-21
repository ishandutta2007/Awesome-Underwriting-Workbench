# Awesome-Underwriting-Workbench

Markdown
# Top Underwriting Workbench Ecosystem


**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Insurance Underwriting Workbenches, Submission Management, Risk Assessment, Pricing, Rules, AI Underwriting & Decision Automation*  
**Last updated: August 2026**


This repository tracks notable **SaaS/Hosted Platforms** and **open-source projects** for **Insurance Underwriting Workbenches**. These platforms help insurers, MGAs, brokers, and reinsurers manage submissions, gather and enrich risk data, assess exposures, apply underwriting rules, calculate prices, automate decisions, manage referrals, generate quotes, and support the underwriting process from submission through bind.


**Examples** include Send Technology, Cytora, AKUR8, INSTANDA, EIS, Insurity, Guidewire, Duck Creek, Sapiens, and Majesco.


**Open-source emphasis**: The open-source ecosystem for underwriting workbenches is considerably more fragmented than the commercial market. Rather than many direct open-source equivalents of Guidewire or Cytora, the ecosystem is strongest across **open insurance platforms, policy administration systems, rating engines, rules engines, workflow engines, document intelligence, ML infrastructure, actuarial libraries, decision engines, and insurance-data tooling**.


The goal of this repository is therefore to include both **complete open-source insurance platforms** and the major open-source building blocks that can be assembled into a modern underwriting workbench.


Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or GitHub repositories.


## Table of Contents


- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Additional Strong Open-Source Options](#additional-strong-open-source-options)
- [Open-Source Underwriting Workbench Stack](#open-source-underwriting-workbench-stack)
- [Underwriting Workbench Building Blocks](#underwriting-workbench-building-blocks)
- [Important Underwriting Concepts](#important-underwriting-concepts)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)


## SaaS/Hosted Platforms


- **[Send Technology](https://send.technology/)**  
  Underwriting orchestration platform for commercial and specialty insurers, MGAs, and reinsurers. Supports submission management, risk workflows, data enrichment, rules, pricing, approvals, quote/rate lifecycle, and post-bind processes. Send was acquired by Duck Creek. 


- **[Cytora](https://www.cytora.com/)**  
  AI-powered underwriting platform focused on transforming insurance submissions into structured risk data, automating intake, triage, risk extraction, and underwriting workflows.


- **[AKUR8](https://akur8.com/)**  
  Insurance pricing and risk-modeling platform using transparent machine-learning techniques for actuarial pricing, rate modeling, and portfolio analysis.


- **[INSTANDA](https://instanda.com/)**  
  Cloud-native insurance platform supporting product configuration, underwriting, rating, policy administration, workflow, and distribution.


- **[EIS](https://www.eisgroup.com/)**  
  Cloud-native insurance core platform supporting product development, underwriting, policy administration, billing, claims, and digital insurance workflows.


- **[Insurity](https://www.insurity.com/)**  
  Insurance software platform offering underwriting, policy administration, billing, claims, data analytics, and insurance lifecycle capabilities across P&C and specialty insurance.


- **[Guidewire](https://www.guidewire.com/)**  
  Major P&C insurance software platform with PolicyCenter, BillingCenter, ClaimCenter, PricingCenter, and related underwriting, product, analytics, and insurance-core capabilities.


- **[Duck Creek](https://www.duckcreek.com/)**  
  Cloud-based P&C insurance platform covering policy, billing, claims, rating, product configuration, and underwriting workflows. Duck Creek now incorporates Send Technology's underwriting orchestration capabilities.


- **[Sapiens](https://sapiens.com/)**  
  Insurance software provider offering policy administration, underwriting, billing, claims, decision management, and insurance-core platforms across P&C, life, and retirement.


- **[Majesco](https://www.majesco.com/)**  
  Cloud insurance technology provider covering policy administration, billing, claims, underwriting, product management, digital experiences, and data-driven insurance operations.


### Additional Major Underwriting Platforms
Recommended Open-Source Combinations

Basic Underwriting Rules Engine

Open Policy Agent + PostgreSQL + React

Useful for implementing configurable underwriting eligibility, authority, referral, and acceptance rules.

Insurance Underwriting Platform

CoSure + OPA/Drools + PostgreSQL + React

Useful as a starting point for an open-source underwriting and policy-administration environment.

Document-Heavy Underwriting

Docling + Unstructured + PaddleOCR + OpenSearch + LLM

Useful for extracting structured risk information from submissions, schedules, PDFs, emails, and supporting documents.

AI Underwriting

Docling + OpenSearch + XGBoost/LightGBM + MLflow + OPA

Useful for combining document extraction, retrieval, ML risk scoring, model management, and deterministic underwriting rules.

Complex Commercial Underwriting

Kafka + Airbyte + OpenSearch + Feast + MLflow + OPA + Camunda

Useful for building an event-driven commercial underwriting workbench with external-data enrichment, ML features, rules, and workflow orchestration.

Actuarial Pricing

Python + chainladder-python + PyMC + XGBoost + LightGBM

Useful for developing actuarial, statistical, and machine-learning pricing models.

Full Open-Source Underwriting Stack

CoSure/Open Insurance Platform + React + PostgreSQL + Kafka + Docling + OpenSearch + OPA/Drools + Camunda/Temporal + MLflow + Feast + Python actuarial libraries

This combination can provide submission intake, document extraction, data enrichment, risk assessment, rules, workflow, pricing, ML modeling, referral management, quote generation, and policy administration.

Underwriting Workbench Building Blocks
Submission Management

Submission Intake

Submission Triage

Submission Classification

Submission Routing

Email Intake

API Intake

Broker Portal

Agent Portal

Submission Deduplication

Submission Completeness

Submission Prioritization

Renewal Intake

New Business Intake

Endorsement Intake

Referral Intake

Document Intelligence

OCR

Document Classification

Document Extraction

Table Extraction

Entity Extraction

Named Entity Recognition

Document Summarization

Policy Document Analysis

Loss Run Extraction

Statement Extraction

Schedule Extraction

Application Extraction

ACORD Form Extraction

PDF Processing

Email Processing

Document AI

Risk Assessment

Risk Scoring

Risk Classification

Risk Segmentation

Risk Appetite

Risk Selection

Hazard Identification

Exposure Analysis

Property Risk

Cyber Risk

Credit Risk

Fraud Risk

Geospatial Risk

Catastrophe Risk

Financial Risk

Business Risk

Operational Risk

Underwriting Rules

Eligibility Rules

Referral Rules

Appetite Rules

Authority Rules

Knockout Rules

Coverage Rules

Limit Rules

Deductible Rules

Pricing Rules

Rating Rules

Underwriting Guidelines

Rule Versioning

Rule Testing

Decision Tables

Business Rules

Rules as Code

Pricing & Rating

Insurance Rating

Rate Tables

Rating Algorithms

Pricing Models

Technical Pricing

Indicated Pricing

Risk-Adjusted Pricing

Experience Rating

Exposure Rating

Manual Rate Overrides

Rate Versioning

Rate Filing

Premium Calculation

Quote Calculation

Discounts

Loadings

Deductibles

Limits

Minimum Premiums

Underwriter Workflow

Underwriter Workbench

Risk 360

Task Management

Referral Management

Approval Workflows

Escalation

Authority Management

Peer Review

Collaboration

Case Management

Activity Management

Underwriter Notes

Audit Trail

Decision History

Workflow Automation

Straight-Through Processing

Decisioning

Automated Underwriting

Decision Engines

Rules Engines

AI Decisioning

Risk Scoring

Eligibility Decisioning

Referral Decisioning

Accept/Reject

Human-in-the-Loop

Manual Review

Explainable AI

Decision Explainability

Decision Auditability

Decision Versioning

Insurance Data

Customer Data

Risk Data

Exposure Data

Claims Data

Policy Data

Loss Runs

Financial Data

Geospatial Data

Property Data

Business Data

Industry Data

Credit Data

Cybersecurity Data

External Risk Data

Third-Party Data

Machine Learning

Insurance Machine Learning

Risk Modeling

Pricing ML

Classification

Regression

Gradient Boosting

Random Forest

Neural Networks

Bayesian Modeling

Survival Analysis

Time-Series Modeling

Anomaly Detection

Fraud Detection

Portfolio Segmentation

Model Explainability

Model Monitoring

Model Drift

Feature Stores

Generative AI

AI Underwriting Assistant

Underwriter Copilot

Submission Summarization

Risk Summarization

Document Q&A

Policy Q&A

Guideline Q&A

Underwriting Knowledge Retrieval

RAG

Agentic Underwriting

AI Risk Research

AI Submission Triage

AI Data Extraction

AI Decision Support

Human-in-the-Loop AI

Portfolio Management

Portfolio Analytics

Portfolio Monitoring

Portfolio Optimization

Risk Aggregation

Exposure Management

Concentration Risk

Accumulation Management

Capacity Management

Risk Appetite Monitoring

Profitability Analysis

Loss Ratio Analysis

Combined Ratio

Rate Adequacy

Portfolio Steering

Specialty Insurance

Commercial Insurance

Specialty Insurance

Marine Insurance

Aviation Insurance

Energy Insurance

Cyber Insurance

Professional Liability

Directors & Officers

Errors & Omissions

Property Insurance

Casualty Insurance

Financial Lines

Reinsurance

Delegated Authority

MGA Underwriting

Lloyd's Underwriting

Insurance Core Integration

Policy Administration

Billing

Claims

Reinsurance

CRM

Accounting

Document Management

Data Warehouse

Data Lake

API Gateway

Event Streaming

REST APIs

GraphQL

ACORD APIs

ACORD Standards

Underwriting Analytics

Technical Pricing

Rate Adequacy

Loss Ratio

Frequency

Severity

Burning Cost

Loss Cost

Exposure Modeling

Predictive Analytics

Risk Analytics

Portfolio Analytics

Scenario Analysis

Stress Testing

What-If Analysis

Model Performance

Governance & Compliance

Audit Trails

Decision Auditability

Model Governance

Model Risk Management

Explainable AI

Fairness

Bias Detection

Regulatory Compliance

Data Lineage

Decision Lineage

Rule Versioning

Model Versioning

Approval Controls

Authority Controls

Human Oversight

Open-Source Insurance Technology

Open-Source Underwriting

Open-Source Rating

Open-Source Insurance

Open-Source PAS

Open-Source Policy Administration

Open-Source Rules Engine

Open-Source Decision Engine

Open-Source Insurance Analytics

Open-Source Actuarial Software

Open-Source Insurance ML

Open-Source Document AI

Open-Source Underwriting AI

Open-Source Insurance Data

Self-Hosted Underwriting

Self-Hosted Insurance Platform

Self-Hosted Rating Engine

Self-Hosted Decision Engine

Important Underwriting Concepts

Underwriting Workbench

Insurance Underwriting

Automated Underwriting

Straight-Through Processing

Submission Management

Submission Triage

Risk Assessment

Risk Selection

Risk Scoring

Risk Appetite

Underwriting Guidelines

Underwriting Rules

Rules as Code

Decision Engine

Business Rules Engine

Rating Engine

Pricing Engine

Technical Pricing

Risk-Based Pricing

Actuarial Pricing

Machine Learning Pricing

Insurance Rating

Quote-to-Bind

Submission-to-Bind

Bind Workflow

Referral Management

Authority Management

Human-in-the-Loop

Underwriter Copilot

AI Underwriting

Agentic Underwriting

Document AI

OCR

Risk Data Enrichment

External Data Enrichment

Risk Intelligence

Property Intelligence

Geospatial Risk

Catastrophe Risk

Cyber Risk

Financial Risk

Credit Risk

Fraud Risk

Exposure Management

Portfolio Management

Portfolio Optimization

Risk Aggregation

Accumulation Management

Capacity Management

Loss Ratio

Combined Ratio

Loss Frequency

Loss Severity

Burning Cost

Loss Cost

Exposure Rating

Experience Rating

Predictive Analytics

Insurance Machine Learning

Insurance AI

Model Governance

Model Explainability

Model Monitoring

Feature Stores

Decision Auditability

Decision Lineage

Data Lineage

Risk Scoring Models

GLM

Generalized Linear Models

Gradient Boosting

XGBoost

LightGBM

Bayesian Modeling

Survival Analysis

Actuarial Modeling

Loss Reserving

Chain Ladder

Stochastic Reserving

RAG

LLM Underwriting

Underwriting Knowledge Base

Underwriting Copilot

Submission Summarization

Risk Summarization

Policy Q&A

Guideline Q&A

AI Risk Research

Commercial Insurance

Specialty Insurance

P&C Insurance

Life Insurance

Health Insurance

Reinsurance

MGA

Delegated Authority

Lloyd's

ACORD

Policy Administration

Insurance Core Systems

Open-Source Underwriting

Open-Source Rating Engine

Open-Source PAS

Open-Source Insurance Platform

Self-Hosted Underwriting Workbench

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow existing format).

Include: name, official link or GitHub repository, 1–2 sentence description, and whether it is SaaS/Hosted or open-source.

For open-source projects, identify the primary capability — underwriting, rating, policy administration, rules, workflow, document intelligence, ML, actuarial analytics, or insurance data.

Clearly distinguish open-source, source-available, open-core, managed SaaS, and proprietary products.

Verify the current license before adding an open-source entry.

Prefer actively maintained repositories with meaningful documentation and recent development.

Do not describe a generic rules engine, ML library, or workflow framework as a complete underwriting workbench unless it actually provides underwriting functionality.

For infrastructure projects, prioritize functionality such as submission processing, risk assessment, rules, pricing, decisioning, workflow, document intelligence, actuarial modeling, and policy administration.

Submit a PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

The commercial insurance technology market changes rapidly, particularly around AI underwriting, automated submission processing, pricing, risk intelligence, and underwriting orchestration.

The open-source ecosystem is substantially more fragmented than the commercial underwriting-workbench ecosystem.

Some projects listed here are complete insurance platforms, while others are rules engines, workflow engines, document-processing frameworks, ML libraries, actuarial libraries, data platforms, or infrastructure components.

CoSure, Open Insurance Platform, LatticePolicy, and Open Insure are closer to complete open-source insurance platforms, while OPA, Drools, Camunda, Temporal, MLflow, Feast, Docling, and chainladder-python are building blocks for constructing a custom underwriting environment.

A production underwriting workbench normally requires multiple layers: submission intake, document processing, data enrichment, risk intelligence, underwriting rules, rating, workflow, decisioning, human review, policy administration, auditability, security, and integration.

Insurance underwriting is highly regulated and domain-specific. Production deployments require appropriate actuarial, legal, compliance, cybersecurity, data-governance, and model-governance controls.

Always verify the current license, maintenance status, documentation, security posture, supported deployment model, and commercial-use restrictions before adopting an open-source project.

Machine-learning and generative-AI systems should generally be treated as decision-support components unless they have been appropriately validated, governed, and approved for the relevant underwriting use case.

Commercial platform features, acquisitions, integrations, pricing, AI capabilities, and deployment options can change over time. Verify current capabilities with the vendor before making procurement decisions.

Made for insurance underwriters, actuaries, MGAs, brokers, reinsurers, InsurTech founders, insurance architects, data scientists, and open-source developers.
Let's make insurance underwriting more open, intelligent, explainable, data-driven, automated, and efficient.
