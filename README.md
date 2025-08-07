<h1>ETL Development: Advanced Database Techniques</h1>


<h2>Overview</h2>
Implemented advanced database techniques in Talend Open Studio to optimize ETL workflows and improve data management, including schema handling, bulk loading, Slowly Changing Dimensions (SCD), and ELT processes.
<br />


<h2>Key Highlights</h2>

- **Schema Handling:** Retrieved tables via Metadata, imported database views, wrote stored queries, and integrated them into the Job Designer.  

- **Bulk Loading:** Enabled high-performance bulk loading using `SET GLOBAL local_infile = 1` and automated text-to-database loads with `tDBOutputBulkExec`.  

- **Stored Procedures:** Created and executed stored procedures using the `tDBRow` component, including simple queries such as record counting.  

- **Slowly Changing Dimensions (SCD):** Implemented SCD techniques to track and manage historical changes in dimension table attributes using the `tDBSCD` component.  

- **Extract, Load & Transform (ELT):** Created a parent-child job relationship in Talend to implement ELT processes. The child job created a table in MySQL, which was then used in the parent job. Applied ELT transformations using `tELTMysqlInput` and `tELTMysqlMap`, including a self-join on the employees table (via a managers alias) and inserted the results into a target table.  

- **Transactions:** Created a parent-child table relationship from the same input, ensuring the child table ID referenced the parent table ID. Configured Talend advanced settings using the "Additional Columns" option and applied the SQL expression `SELECT LAST_INSERT_ID()` to maintain referential integrity.  

<h2>Skills </h2>

Talend Open Studio, SQL, Schema Handling, Bulk Loading, Stored Procedures, Slowly Changing Dimensions (SCD), ELT, Transactions, ETL Optimization.

<h2>Documentation:</h2>

<p align="center">
Schema Handling - Retrieved Tables via Metadata <br/>
<img src="https://github.com/user-attachments/assets/86796858-7e38-47fd-8352-7f69495da4e5" height="80%" width="80%" alt="Schema Handling"/>
<br />
<br />
Schema Handling - Writing Stored Queries  <br/>
<img src="https://github.com/user-attachments/assets/99486324-fadd-41c9-8c67-553bc2bfd28d" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Schema Handling - Job Designer Workflow <br/>
<img src="https://github.com/user-attachments/assets/7b07ae7b-cb44-4791-9ef5-194ff3a41403" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Bulk Loading - Job Designer Workflow  <br/>
<img src="https://github.com/user-attachments/assets/0ca76dde-e2ac-4729-a08d-e775bee9b3db" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Stored Queries - Jod Designer Workflow  <br/>
<img src="https://github.com/user-attachments/assets/1a6279cd-d768-4e47-9069-9e932ed799bf" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Stored Queries - SQL Query in Talend  <br/>
<img src="https://github.com/user-attachments/assets/0f6d7cc8-41df-49c4-8d2d-ef9c39b83852" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
SCD - Job Designer Workflow  <br/>
<img src="https://github.com/user-attachments/assets/518ee639-4ae5-4c63-bbf8-531acc9d9bfa" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
SCD - SCD Component Editor  <br/>
<img src="https://github.com/user-attachments/assets/cfbcabe0-a0bd-4d73-9638-ff75cf32a34b" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
SCD - History Table Result in MySQL Database  <br/>
<img src="https://github.com/user-attachments/assets/f0ac2e15-1090-4394-ada8-5ebe4755c745" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
ELT - Child Job Workflow  <br/>
<img src="https://github.com/user-attachments/assets/a25f9888-4e0d-4762-9596-e887c16ff754" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
ELT - Parent Job Workflow <br/>
<img src="https://github.com/user-attachments/assets/8ff8cb05-f847-4f03-91e4-f955ca995517" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
ELT - Mapping (Self Join) and SQL Query  <br/>
<img src="https://github.com/user-attachments/assets/ff107ef1-92c9-47cf-9759-a33bf65a0e25" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
ELT - Table Result in MySQL Database  <br/>
<img src="https://github.com/user-attachments/assets/0ef3f778-c7f6-4bfd-9260-9ceaebb1c95d" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
