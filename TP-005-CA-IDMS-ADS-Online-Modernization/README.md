# TP-005 — CA-IDMS & ADS/Online Modernization

## From Network Navigation and Legacy Dialogs to Relational Cloud Architecture

CA-IDMS modernization is not simply a database conversion. Decades of business meaning can be embedded across network records, owner/member sets, pointers, application currency, ADS/Online dialogs, COBOL programs, batch processing, and navigational access paths.

This BeyondX technical paper presents an engineering approach for discovering that legacy knowledge and transforming it into modern relational and cloud architectures.

## Modernization Paths

TP-005 examines three legitimate modernization models:

1. **Phased Mainframe Modernization**  
   CA-IDMS → Db2 z/OS  
   ADS/Online → COBOL/CICS with embedded SQL  
   Cloud modernization follows later.

2. **Application-First Hybrid Modernization**  
   CA-IDMS → Db2 z/OS  
   ADS/Online and selected COBOL logic → Java/Spring  
   A later Db2 z/OS → Amazon Aurora PostgreSQL migration can then be performed with the Java application largely retained when database-specific dependencies have been properly isolated.

3. **Direct Cloud Modernization**  
   CA-IDMS → Amazon Aurora PostgreSQL  
   ADS/Online / COBOL → Java/Spring Boot  
   Batch workloads → Spring Batch and cloud services on AWS.

## Topics Covered

- CA-IDMS schemas, subschemas, areas, records and elements
- Owner/member sets and pointer-driven navigation
- DBKEY and CALC considerations
- Navigational DML transformation
- OCCURS and REDEFINES
- ADS/Online modernization
- CA-IDMS date/time storage, semantics and migration
- Db2 z/OS and Amazon Aurora PostgreSQL target architectures
- Java/Spring application modernization
- AI-assisted discovery and transformation using ChatGPT/OpenAI
- Validation and reconciliation
- Legacy-system decommissioning and knowledge preservation

## BeyondX Engineering Principles

> **The unit of migration is not the IDMS record. The true unit of modernization is the business relationship.**

> **Modernize the application once. Modernize the database in controlled stages.**

> **Use AI to understand the legacy estate before using AI to transform it.**

> **Modernization is successful only when the legacy system can be retired with confidence.**

## Publication

**BeyondX TP-005 — CA-IDMS & ADS/Online Modernization**  
*From Network Navigation and Legacy Dialogs to Relational Cloud Architecture*

The publication PDF is available in this directory.

---

**BeyondX LLC**  
*Technology with Purpose. Opportunity with Impact.*  
*Imagination to Implementation.*
