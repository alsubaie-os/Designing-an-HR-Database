# Data Architecture Foundations

## Project a Human Resources Database Design

In this project, I was able to use SQL to design, build and populate a database for the Human Resources Department of Tech ABC Corp, a fictional video game company.

The goal of this project is to be able to digest a memo provided by the Tech ABC Corp Head of HR, with the business context of the company and requisition of a brand new HR database system, and come up with a solution proposal. It is essential to meet all the technical and business requirements of the project by providing two assets:

1. <a href="https://github.com/alsubaie-os/Udacity-Data-Architect-Nanodegree-Repo/blob/0c9d2a1ab17d39216c97a99bca5d75f17feb0139/Project_1%20Designing%20an%20HR%20Database/HR%20Database%20Solution%20Report.pdf" title="Solution Report">Solution Report</a>
2. <a href="https://github.com/alsubaie-os/Udacity-Data-Architect-Nanodegree-Repo/tree/0c9d2a1ab17d39216c97a99bca5d75f17feb0139/Project_1%20Designing%20an%20HR%20Database/SQL">SQL implementation</a>

## Business Scenario

Tech ABC Corp saw explosive growth with a sudden appearance onto the gaming scene with its new AI-powered video game console. As a result, they have gone from a small 10 person operation to 200 employees and 5 locations in under a year. HR is having trouble keeping up with the growth since they are still maintaining employee information in a spreadsheet. While that worked for ten employees, it has become increasingly cumbersome to manage as the company expands.

## Support Material

### 1. Dataset

An Excel workbook consisting of 206 records not normalized. The data lists the names of employees, job title, department, manager's name, hire date, start date, end date, work location and salary.

### 2. IT Department Best Practices

The IT Best Practices and policies for database that should be followed. It contains security constraints, backup policies and mandatory routines that should be followed, storage rules (such as in memory and in disk) and data ingestion caracteristics.

# Solution

## 1. Data Architecture Foundations

In this step I had to answer to technical and business open questions. The questions are related to

- Current architecture
- New architecture
- Data governance
- Data ownership
- Data access and security concerns
- Estimated size and growth of data
- Database objects
- Data ingestion
- Scalability
- Flexibility
- Storage & retention
- Backup

Solution can be found on `Step 1` of <a href="https://github.com/alsubaie-os/Udacity-Data-Architect-Nanodegree-Repo/blob/0c9d2a1ab17d39216c97a99bca5d75f17feb0139/Project_1%20Designing%20an%20HR%20Database/HR%20Database%20Solution%20Report.pdf" title="Solution Report">Solution Report</a>.

## 2. Relational Database Design

Create Entity Relationship Diagrams - Conceptual, Logic and Physical using <a href="https://www.lucidchart.com/pages">Lucidchart</a>. The Physical ERD must have <a href="https://en.wikipedia.org/wiki/Entity%E2%80%93relationship_model#Crow's_foot_notation">Crow's foot notation</a> indicating the relationship between entities as well as the design must follow the <a href="https://en.wikipedia.org/wiki/Third_normal_form">3NF (third normal form)</a>.

- <a href="https://github.com/alsubaie-os/Udacity-Data-Architect-Nanodegree-Repo/blob/0c9d2a1ab17d39216c97a99bca5d75f17feb0139/Project_1%20Designing%20an%20HR%20Database/ERD/Conceptual.png" title="Conceptual ERD">Conceptual ERD</a>
<img src="ERD/Conceptual.png" alt="Conceptual ERD" width="1000">

- <a href="https://github.com/alsubaie-os/Udacity-Data-Architect-Nanodegree-Repo/blob/0c9d2a1ab17d39216c97a99bca5d75f17feb0139/Project_1%20Designing%20an%20HR%20Database/ERD/Logical.png" title="Logical ERD">Logical ERD</a>
<img src="ERD/Logical.png" alt="Logical ERD" width="1000">

- <a href="https://github.com/alsubaie-os/Udacity-Data-Architect-Nanodegree-Repo/blob/0c9d2a1ab17d39216c97a99bca5d75f17feb0139/Project_1%20Designing%20an%20HR%20Database/ERD/Physical.png" title="Physical ERD">Physical ERD</a>
<img src="ERD/Physical.png" alt="Physical ERD" width="1000">

Solution can be found on `Step 2` of <a href="https://github.com/alsubaie-os/Udacity-Data-Architect-Nanodegree-Repo/blob/0c9d2a1ab17d39216c97a99bca5d75f17feb0139/Project_1%20Designing%20an%20HR%20Database/HR%20Database%20Solution%20Report.pdf" title="Solution Report">Solution Report</a>.

## 3. Create a Physical Database

- <a href="https://github.com/alsubaie-os/Udacity-Data-Architect-Nanodegree-Repo/blob/0c9d2a1ab17d39216c97a99bca5d75f17feb0139/Project_1%20Designing%20an%20HR%20Database/SQL/DDL.sql">DDL</a>
- <a href="https://github.com/alsubaie-os/Udacity-Data-Architect-Nanodegree-Repo/blob/0c9d2a1ab17d39216c97a99bca5d75f17feb0139/Project_1%20Designing%20an%20HR%20Database/SQL/DML.sql">DML</a>
- <a href="https://github.com/alsubaie-os/Udacity-Data-Architect-Nanodegree-Repo/blob/0c9d2a1ab17d39216c97a99bca5d75f17feb0139/Project_1%20Designing%20an%20HR%20Database/SQL/CRUD.sql">CRUD</a>

Solution can be found on `Step 3` of <a href="https://github.com/alsubaie-os/Udacity-Data-Architect-Nanodegree-Repo/blob/0c9d2a1ab17d39216c97a99bca5d75f17feb0139/Project_1%20Designing%20an%20HR%20Database/HR%20Database%20Solution%20Report.pdf" title="Solution Report">Solution Report</a>.

## 4. Above and Beyond (optional)

- <a href="https://github.com/alsubaie-os/Udacity-Data-Architect-Nanodegree-Repo/blob/0c9d2a1ab17d39216c97a99bca5d75f17feb0139/Project_1%20Designing%20an%20HR%20Database/SQL/Standout%20Suggestion.sql">Standout Suggestions</a>

Solution can be found on `Step 4` of <a href="https://github.com/alsubaie-os/Udacity-Data-Architect-Nanodegree-Repo/blob/0c9d2a1ab17d39216c97a99bca5d75f17feb0139/Project_1%20Designing%20an%20HR%20Database/HR%20Database%20Solution%20Report.pdf" title="Solution Report">Solution Report</a>.
