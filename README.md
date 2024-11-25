# Exam - IMSE
## Lecture 1: Data Engineering

---

### **Slide 4: CERN’s Challenge - Datagrid**
**Summary**:  
- **Purpose**: Large Hadron Collider (LHC) tests particle physics theories, including discovering the Higgs Boson.  
- **Features**: A 27 km ring, cooled to -271.3°C, with detectors like ATLAS, CMS, LHCb, and ALICE.  
- **Collaboration**: A global effort to process and analyze data.

**Explanation**: The LHC generates vast amounts of data, necessitating advanced computing systems.

**MCQs**:  
1. **What is the primary purpose of the Large Hadron Collider (LHC)?**  
   - A) Discover new planets  
   - B) Test particle physics theories  
   - C) Build neural networks  
   - D) Analyze economic trends  
   **Answer**: **B**

2. **Which of the following are LHC detectors? (Multiple correct)**  
   - A) ATLAS  
   - B) CMS  
   - C) LHCb  
   - D) TensorFlow  
   **Answer**: **A, B, C**

---

### **Slide 6: Worldwide LHC Computing Grid (WLCG)**
**Summary**:  
- **Features**: 1.4 million computer cores, 2 exabytes of storage, and >260 GB/s transfer rates.  
- **Decentralized System**: Handles 2 million tasks/day for LHC data analysis.  

**Explanation**: The WLCG ensures global collaboration and efficient processing for LHC experiments.

**MCQs**:  
1. **How much storage does the WLCG provide?**  
   - A) 2 terabytes  
   - B) 2 exabytes  
   - C) 170 petabytes  
   - D) 260 gigabytes  
   **Answer**: **B**

2. **What is the WLCG responsible for?**  
   - A) Storing financial records  
   - B) Processing LHC data  
   - C) Managing social media platforms  
   - D) Building predictive models  
   **Answer**: **B**

---

### **Slide 7: WLCG - Tiered Structure**
**Summary**:  
- **Tiers**:  
  - **Tier 0**: CERN (central repository).  
  - **Tier 1**: 13 global centers for major data storage.  
  - **Tier 2**: 150+ regional centers.  
- **Collaboration**: Involves 170 computing centers across 42 countries.

**Explanation**: The tiered structure facilitates decentralized yet coordinated global data management.

**MCQs**:  
1. **What is the role of Tier 1 in WLCG?**  
   - A) Central data repository  
   - B) Major data storage and distribution  
   - C) Local user data analysis  
   - D) Streaming data in real-time  
   **Answer**: **B**

2. **How many Tier 2 centers are part of the WLCG?**  
   - A) 13  
   - B) 42  
   - C) Over 150  
   - D) 170  
   **Answer**: **C**

---

### **Slide 8: WLCG Challenges**
**Summary**:  
- Key challenges:  
  - Data integration and scalability.  
  - Real-time processing.  
  - Machine learning and advanced analytics integration.  
  - Cost and resource management.

**Explanation**: Addressing these challenges is essential for maintaining WLCG’s functionality and efficiency.

**MCQs**:  
1. **Which of the following are challenges faced by WLCG? (Multiple correct)**  
   - A) Scalability  
   - B) Real-time processing  
   - C) Data security  
   - D) Manual data entry  
   **Answer**: **A, B, C**

2. **What is a major focus area for WLCG’s improvement?**  
   - A) Physical infrastructure  
   - B) Data lifecycle management  
   - C) Social media integration  
   - D) Predictive modeling  
   **Answer**: **B**

---

### **Slide 11: What is Data Engineering?**
**Summary**:  
- **ETL Process**:  
  - **Extract**: Collect and clean raw data.  
  - **Transform**: Enrich and aggregate data.  
  - **Load**: Securely store data.  
- **Purpose**: Efficient storage and retrieval.

**Explanation**: Data engineering ensures data is clean, usable, and accessible for analysis.

**MCQs**:  
1. **What is the first step of the ETL process?**  
   - A) Transform  
   - B) Extract  
   - C) Load  
   - D) Analyze  
   **Answer**: **B**

2. **What is the goal of the Transform stage in ETL?**  
   - A) Secure data  
   - B) Aggregate and enrich data  
   - C) Analyze trends  
   - D) Build visualizations  
   **Answer**: **B**

---

### **Slide 19: Data Lifecycle**
**Summary**:  
- **Stages**:  
  - **Creation**: Collecting data.  
  - **Storage**: Saving securely.  
  - **Processing**: Preparing data for use.  
  - **Utilization**: Sharing and applying insights.  
  - **Archiving**: Disposing of data responsibly.

**Explanation**: The lifecycle ensures systematic and secure data management.

**MCQs**:  
1. **What is the final stage of the data lifecycle?**  
   - A) Data creation  
   - B) Data storage  
   - C) Data archiving  
   - D) Data retrieval  
   **Answer**: **C**

2. **Which stage involves sharing data insights?**  
   - A) Data creation  
   - B) Data processing  
   - C) Data utilization  
   - D) Data archiving  
   **Answer**: **C**

---

### **Slide 25: New Requirements for Data Management**
**Summary**:  
- **Trends**:  
  - Increase in unstructured data (e.g., sensor data, social media).  
  - Use of complex types (arrays, maps).  
  - Machine learning uses complex representations (e.g., embeddings).

**Explanation**: Data management must evolve to handle complexity and variety.

**MCQs**:  
1. **Which type of data is increasing in use? (Multiple correct)**  
   - A) Structured  
   - B) Semi-structured  
   - C) Unstructured  
   - D) Financial data  
   **Answer**: **B, C**

2. **What is a common machine learning data representation?**  
   - A) Arrays  
   - B) Embeddings  
   - C) Maps  
   - D) Relational tables  
   **Answer**: **B**

---

---

### **Slide 30: Object-Relational Mapping (ORM)**
**Summary**:  
- **Definition**: A technique to map object-oriented programming (OOP) models to relational databases.  
- **Functionality**: Automates translation of objects into relational tables, simplifying CRUD operations.  
- **Popular Frameworks**: Hibernate (Java), Django ORM (Python), Entity Framework (.NET).

**Explanation**: ORM bridges the gap between OOP and relational databases, enhancing developer productivity.

**MCQs**:  
1. **What is the primary purpose of ORM?**  
   - A) Build predictive models  
   - B) Bridge OOP and relational databases  
   - C) Simplify data visualization  
   - D) Optimize query performance  
   **Answer**: **B**

2. **Which frameworks are examples of ORM? (Multiple correct)**  
   - A) Hibernate  
   - B) Django ORM  
   - C) TensorFlow  
   - D) Entity Framework  
   **Answer**: **A, B, D**

---

### **Slide 32: ORM Example with Python**
**Summary**:  
- **Pure Python**: Manually connects to SQLite, executes SQL, and commits changes.  
- **Django ORM**: Simplifies database interaction by defining models and performing CRUD operations using object-oriented syntax.

**Explanation**: ORM reduces the complexity of database operations compared to manual SQL handling.

**MCQs**:  
1. **What does Django ORM replace in traditional Python database access?**  
   - A) Use of SQL queries  
   - B) Use of object-oriented programming  
   - C) CRUD operations  
   - D) Data visualization  
   **Answer**: **A**

2. **What are key benefits of ORM-based access? (Multiple correct)**  
   - A) Simplified CRUD operations  
   - B) Object-oriented model representation  
   - C) Direct use of SQL queries  
   - D) Enhanced code readability  
   **Answer**: **A, B, D**

---

### **Slide 34: Object-Relational DBMS vs. Object-Oriented DBMS**
**Summary**:  
- **ORDBMS**: Combines relational and object-oriented features, extends SQL.  
- **OODBMS**: Fully object-oriented, supports encapsulation, inheritance, and polymorphism.

**Explanation**: ORDBMS merges relational models with object-oriented features, while OODBMS relies entirely on object principles.

**MCQs**:  
1. **Which features distinguish ORDBMS from traditional relational databases?**  
   - A) Support for inheritance  
   - B) Encapsulation  
   - C) Polymorphism  
   - D) Nested tables  
   **Answer**: **A, D**

2. **What is a characteristic of OODBMS?**  
   - A) Uses SQL exclusively  
   - B) Stores objects as they are used in programming  
   - C) Lacks support for inheritance  
   - D) Combines relational and object-oriented features  
   **Answer**: **B**

---

### **Slide 37: ORDBMS**
**Summary**:  
- **Definition**: Extends traditional relational models with object-oriented features.  
- **Key Features**: Supports objects, classes, inheritance, and methods.  
- **Advantages**: Combines object-oriented and relational strengths, improving database flexibility.

**Explanation**: ORDBMS adapts to modern data needs by integrating object-oriented capabilities into relational systems.

**MCQs**:  
1. **What are the key features of ORDBMS? (Multiple correct)**  
   - A) Classes and inheritance  
   - B) SQL-only support  
   - C) Polymorphism  
   - D) Encapsulation  
   **Answer**: **A, C, D**

2. **What is a significant benefit of ORDBMS?**  
   - A) Requires no relational schema  
   - B) Provides backward compatibility with relational databases  
   - C) Replaces SQL with object queries  
   - D) Focuses on visualization tools  
   **Answer**: **B**

---

### **Slide 40: SQL:1999**
**Summary**:  
- **Extensions**:  
  - Recursive queries (WITH clause).  
  - User-defined types (UDTs) and functions (UDFs).  
  - Advanced query operators, triggers, and stored procedures.  
- **Supported By**: Oracle, IBM DB2, PostgreSQL.

**Explanation**: SQL:1999 introduced object-relational features, enhancing relational databases for complex data needs.

**MCQs**:  
1. **What did SQL:1999 introduce?**  
   - A) Polymorphic table functions  
   - B) Recursive queries  
   - C) Graph querying  
   - D) NoSQL support  
   **Answer**: **B**

2. **Which databases support SQL:1999? (Multiple correct)**  
   - A) Oracle  
   - B) IBM DB2  
   - C) MongoDB  
   - D) PostgreSQL  
   **Answer**: **A, B, D**

---

### **Slide 42: SQL:1999 - Selected Extensions for Complex Types**
**Summary**:  
- **Features**:  
  - User-defined types and functions.  
  - Inheritance and collections.  
  - Large Object Types (LOBs).  

**Explanation**: These extensions support object-oriented modeling and handling of complex data types.

**MCQs**:  
1. **Which features were introduced in SQL:1999? (Multiple correct)**  
   - A) Recursive queries  
   - B) User-defined types  
   - C) Polymorphism  
   - D) Graph querying  
   **Answer**: **A, B**

2. **What are Large Object Types (LOBs) used for?**  
   - A) Data visualization  
   - B) Managing large binary data  
   - C) Streaming real-time data  
   - D) Building relational tables  
   **Answer**: **B**

---

### **Slide 47: User-Defined Functions (UDFs)**
**Summary**:  
- **Definition**: Custom functions written in SQL or procedural languages.  
- **Use Case**: Enables advanced querying and encapsulation of logic.  
- **Example**: Query books by a specific author using a UDF.

**Explanation**: UDFs add flexibility to databases by allowing reusable logic within queries.

**MCQs**:  
1. **What is the primary purpose of UDFs?**  
   - A) Simplify schema design  
   - B) Encapsulate logic for reusable queries  
   - C) Manage ETL pipelines  
   - D) Automate CRUD operations  
   **Answer**: **B**

2. **What is an example of UDF functionality? (Multiple correct)**  
   - A) Custom filtering of data  
   - B) Advanced querying  
   - C) Automating database migrations  
   - D) Adding data to tables  
   **Answer**: **A, B**

---

### **Slide 49: Object-Oriented Database Management Systems (OODBMS)**
**Summary**:  
- **Characteristics**:  
  - Stores data as objects, matching programming paradigms.  
  - Supports inheritance, encapsulation, and polymorphism.  
- **Advantages**: Native integration with object-oriented languages.

**Explanation**: OODBMS aligns databases with object-oriented programming, simplifying development workflows.

**MCQs**:  
1. **What is a characteristic of OODBMS?**  
   - A) Stores data in tables exclusively  
   - B) Supports inheritance and encapsulation  
   - C) Uses only SQL for queries  
   - D) Lacks support for polymorphism  
   **Answer**: **B**

2. **What are the advantages of OODBMS? (Multiple correct)**  
   - A) Object-oriented language integration  
   - B) Simplifies complex data modeling  
   - C) Requires no programming knowledge  
   - D) Supports encapsulation and polymorphism  
   **Answer**: **A, B, D**

---

### Parallel and Distributed DBMS**
**Summary**:  
- **Parallel Databases**: Use multiple processors to speed up query execution.  
- **Distributed Databases**: Store data across multiple nodes for reliability and scalability.  
- **Key Features**: Replication, fragmentation, and query optimization.

**Explanation**: These systems enhance performance and reliability for large-scale data operations.

**MCQs**:  
1. **What is the primary advantage of parallel databases?**  
   - A) Single-node performance  
   - B) Faster query execution using multiple processors  
   - C) Simplified data modeling  
   - D) NoSQL support  
   **Answer**: **B**

2. **Which of the following are key features of distributed databases? (Multiple correct)**  
   - A) Data replication  
   - B) Fragmentation  
   - C) Query optimization  
   - D) Single-node storage  
   **Answer**: **A, B, C**

---


