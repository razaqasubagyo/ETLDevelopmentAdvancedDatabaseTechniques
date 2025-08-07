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
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
