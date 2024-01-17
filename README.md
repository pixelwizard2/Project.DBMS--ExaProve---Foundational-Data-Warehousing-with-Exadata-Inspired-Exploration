# Project.DBMS--ExaProve---Building-a-Data-Warehouse-for-Emulating-Exadata-DB-Project
Exadata DB 모방을 위한 데이터 웨어하우스 구축 프로젝트(MySQL 활용)
 
<p align="right">
  <a href="https://blog.naver.com/pixelwizard/223321757202">
    <img src="https://img.shields.io/badge/한국어%20번역본-03C75A?style=flat-square&logo=Naver&logoColor=white" alt="네이버 블로그">
  </a> </p>  
  
![타이타닉 1](https://github.com/pixelwizard2/Project.DBMS--ExaProve---DB-Voyage-of-the-Titanic--Database-Operation-and-Optimization/assets/138272416/6c6b10a1-c5a3-46af-b4c1-8365340464d0)

 
**※ Development Period : 2023.01.12 ~ 2023.01.14 (24h) (In Progress) <진행 중>**
<br> <br> <br>

## 1. Project Overview (프로젝트 개요)

This project utilizes a housing dataset to explore the role of a database administrator and practice key functions and optimization strategies of Database Management Systems (DBMS). By emulating the advanced features required in high-end database systems like Exadata DB within a MySQL environment, this mini project aims to enhance the management and optimization skills for complex database systems. The primary focus is on gaining an in-depth technical understanding of database performance monitoring, tuning, security management, backup, and recovery.

Project Objective
The goal of this project is to master simple data CRUD operations and develop a deep technical understanding and problem-solving skills. The project is designed to demonstrate the ability to derive business insights based on data analysis and apply solutions in a real work environment.

Technical Background and Utilized Techniques
The project is built on the following technical background:

Basic Skills (Completed)
Schema Creation and Data Verification
Database Performance Monitoring & Query Performance Evaluation and Tuning
Data Security and Encryption Techniques
Data Integrity Maintenance and Recovery Strategy
Large Data Processing (+Data Warehouse Construction)
Advanced Skills (Planned)
(1) High Availability (HA) Setup

Objective: To ensure continuous availability and data integrity of the database.
Reason for Selection: Preventing data loss during failures and ensuring uninterrupted service is critical in all large-scale database systems. This mirrors the high availability features of Exadata.
(2) Disaster Recovery (DR) Plan

Objective: To develop swift and effective data recovery methods for data loss scenarios.
Reason for Selection: The ability to protect and recover data in any disaster situation is a core aspect of Exadata DB management.
(3) Security Enhancement Project

Objective: To strengthen database security and minimize security vulnerabilities.
Reason for Selection: Database security is crucial in advanced systems like Exadata. We will practice enhancing security levels through user rights management, encryption, and SQL injection prevention techniques.
(4) Automation and Monitoring

Objective: To automatically monitor database status and detect potential issues in advance.
Reason for Selection: Implementing a system similar to Exadata's 'Smart Metrics' for continuous monitoring of database performance and health.
Project Implementation
The project was carried out in the following stages:

(1) Schema Creation and Data Verification
(1.1) Schema Creation
(1.2) Basic Statistical Data Verification
(1.3) Identifying Data that Meets Specific Conditions
(1.4) Sorting Data
(2) Database Performance Monitoring & Query Performance Evaluation and Tuning
(2-1) Executing Queries to Verify MySQL Data Directory Path
(2-2) Activating Slow Query Log
(2-3) Generating Slow Query Logs and Real-Time Performance Monitoring
(2-4) Analyzing Index Efficiency for LSTAT Column (No Performance Improvement)
(2-5) Attempting to Improve Search Performance by Adding an Index to LSTAT
Column (No Time Improvement)

(2-6) Improved Performance Confirmed by Tuning Index for LSTAT Range Query
(3) Data Security and Encryption Techniques
(3-1) Enhancing Data Security with Advanced AES Encryption
(4) Data Integrity Maintenance and Recovery Strategy
(4.1) Database Recovery Strategy and Error Resolution During Code Execution, Handling Duplicate Records Using INSERT IGNORE and ON DUPLICATE KEY UPDATE
(5) Large Data Processing (+Data Warehouse Construction)
(5-1) SQL Work for Table Creation, Data Loading, and Range Partitioning in Database
(5-2) Querying Partition Information for Data Warehouse Construction
(5-3) Data Warehouse Construction Process, Querying Partitions of 'housing_new' Table
(5-4) Initial Data Loading and Creation of Dimension and Fact Tables
(5-5) Querying the First 10 Records of the Housing Table in the New_schema Schema
(5-6) Executing and Utilizing Data Warehouse Queries
Expected Results and Learning Points
The completed project is expected to yield the following results:

Experience in writing and optimizing queries for complex datasets
Enhanced ability to respond to real-world work environment incidents and performance tuning
A deeper understanding of database security enhancement
Development of practical cases for maintaining data integrity and recovery strategies
Implementation of predictive models for data-based decision-making support
Project Expansion Plans
After the completion of the project, the following expansions are planned:

Developing a decision support system based on data analysis results and insights
Acquiring skills in data movement and transformation between databases through DB migration scenarios
Strengthening database security expertise through additional security feature implementation and practice
Conclusion and Expected Effects
This project aims to deepen the expertise of a database administrator and improve skills in managing and optimizing complex database systems. It will demonstrate advanced technical capabilities and problem-solving skills required in a data-centric business environment.
