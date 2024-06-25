## JRC technical meeting

Agenda:
1. SWR Architecture Overview (Tomas)
2. Technical Components (Tomas)
3. Development Process (Nick)
4. Open Discussion:
   - Integration of SWR with EUSO
   - Non functional requirements 
   - Communication and technical meetings frequency SoilWise - JRC 
   - Expectations and next steps

<br />

**Current components of SWR to be integrated :**

Metadata authoring – Hale-studio/connect (data export/download and transformation) – Monitoring – Harvesters – PyCSW – Map Server – Interlinker – PostgreSQL – Triple Store – Large language models 

Deploy: Docker containers (+ Python code) + Kuberneters cluster

Connection to other (EUSO) applications/infrastructure via API’s

<br />
<br />

**Questions to JRC for implementation/migration:**

**1. General Information**

- What are the primary goals, objectives and limitations of your IT infrastructure? 
- What are the key business functions supported by your IT systems?

**2. Hardware**
- What types of servers are currently in use (physical, virtual, cloud, hybrid / public, private)?

**3. Software**
- What operating systems ((Windows, macOS, Linux) ) are used across servers and workstations? 
- What are the primary applications and software platforms in use? 
- What development tools and environments are used by your teams?

**4. Data Management**
- What databases and data storage solutions are in use? 
- How is data backed up?
- What is your data governance policy?

**5. Cloud Services**
- What cloud platforms and services are utilized (e.g., AWS, Azure, Google Cloud)? 
- How is cloud infrastructure managed and monitored? 
- What is your approach to cloud security and compliance? 
- Do you use any hybrid or multi-cloud strategies?

**6. Development and Deployment**
- What CI/CD tools and practices are in place? 
- How do you manage version control and repositories (e.g., Git)? 
- What is your testing and quality assurance process?

**7. Vendor and Third-Party Services**
- Which third-party services and vendors are critical to your operations?
- What third-party (or self-developed) integrations/services related to the SWR 10 components are already in place?
  - Metadata authoring:
  - Hale-studio/connect (data export/download and transformation):
  - Monitoring:
  - Harvesters:
  - PyCSW:
  - Map Server:
  - Interlinker:
  - PostgreSQL:
  - Triple Store:
  - Large language models:

**8. Performance and Scalability**
- What are your key performance metrics and SLAs? 
- How do you ensure scalability of your infrastructure?
