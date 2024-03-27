# System-Performance

#technologies used

POWER BI DESTOP
IDE- VISUAL STUDIO CODE,
MICROSOFT SQL SERVER MANAGEMENT STUDIO,
PYTHON (PROGRAMMING LANGUAGE).

#Abstract:

 we propose a comprehensive approach utilizing Python, SQL Server, and Power BI for real-time monitoring, data storage, and visualization of system performance metrics.

Python is employed for its versatility in data collection, processing, and analysis. Through Python libraries such as psutil and pyodbc, we gather real-time performance data from various system resources including CPU usage, memory utilization, disk I/O, and network activity. This data is then processed and stored in a SQL Server database, ensuring scalability, reliability, and efficient data management.

SQL Server serves as the central repository for storing the collected performance metrics. Its robust architecture facilitates real-time data ingestion and provides mechanisms for data retrieval and manipulation. Leveraging SQL queries and stored procedures, we perform analysis on historical performance data as well as generate insights on current system behavior.

Power BI is utilized for intuitive and interactive visualization of the performance metrics stored in the SQL Server database. With its rich set of visualization tools and capabilities, Power BI enables users to create dynamic dashboards and reports that offer real-time insights into system performance. Through features such as live data connectivity, users can monitor system metrics as they evolve over time, facilitating timely decision-making and proactive management.

This integrated approach offers a powerful solution for real-time system performance analysis, providing stakeholders with the necessary tools to monitor, analyze, and optimize system performance effectively. By combining the strengths of Python, SQL Server, and Power BI, organizations can gain actionable insights into their systems, leading to improved performance, enhanced reliability, and better resource utilization.

steps followed:


To display the system performance information in real-time,

used python th get the system performance data from the system.

used sql server to store that data in a database
columns created in table in the database are

memory_usage,
memory used,
cpu usage,
disk usage,
time,
cpu interupts,
bytes sent,
bytes recevied,
cpu calls.

used POWER BI to display the system performance 
