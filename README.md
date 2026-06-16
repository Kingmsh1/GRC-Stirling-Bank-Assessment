# Cybersecurity GRC Risk Assessment Project - Fictional Commercial Bank

## Author
Maahir Shah

## Overview

This project simulates a cybersecurity Governance, Risk & Compliance assessment for a fictional commercial bank - Stirling Bank.

The aim was to identify, analyse, document and present key cybersecurity risks across the bank. This included risks in the bank's cloud infrastructure, legacy systems, internal Active Directory network and AI systems.

The project aligns risks with the following industry GRC frameworks:

- NIST Cybersecurity Framework (NIST CSF)
- ISO/IEC 27001 (referred to as ISO 27001 throughout the project)
- NIST AI Risk Management Framework (NIST AI RMF)
- GDPR

## Objectives

This project aimed to identify realistic cybersecurity risks in a financial services environment. It aims to map risks to recognised GRC frameworks and assess the impact of each risk on the bank. Practical mitigation strategies were proposed for each risk to demonstrate understanding of GRC frameworks and how companies can adhere to them.

Risk audit data was collected and compiled into an interactive, executive dashboard in Excel. The dashboard presents the data collected, giving a detailed overview of risk and provides interactivity to allow users to filter data and make comparisons.

Design considerations, such as visual appeal, colour scheme and fonts, were taken into account during design to ensure accessibility, readability and simplicity.

## Scenario

This assessment is based on a fictional high-street bank offering financial services, such as mobile banking and loans.

The bank operates a hybrid infrastructure environment including the following infrastructure:

- AWS cloud services for data storage and mobile application hosting
- Legacy core banking systems with limited patching ability
- Active Directory for internal identity and resource access management
- AI chatbot assistants for employees and customers, helping with support and queries

This setup introduces a host of both legacy and modern security risks that may occur in a real-world banking scenario.

## Key Risks Identified

This assessment uncovered a total of 13 crucial findings. This included:

- Unencrypted sensitive log data stored in AWS cloud storage
- AI chatbot prompt injection vulnerabilities
- Weak credential policy
- Excessive privileges granted to staff

## Methodology

These findings were identified through structured analysis of the bank's architecture. This included:

- Reviewing IAM practices
- Assessing legacy system constraints and risks
- Assessing AI vulnerabilities and threat modelling
- Mapping findings to relevant GRC frameworks, offering remediation according to framework guidelines

## Deliverables

- Professional GRC Risk Assessment Report (PDF)
- Risk Audit Data & Executive Dashboard (Excel spreadsheet)
