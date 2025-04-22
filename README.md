**GitHub Project Description:**  
The **Exam Seating Arrangement System** is a JSP/Servlet-based web app that automates exam logistics by assigning students to seats dynamically using room capacity and batch data. Built with **MySQL** for database management, it includes a preconfigured SQL script (`esas.sql`) to set up tables, student records, and room details. Admins (default login: `admin/test`) can customize database credentials via the `Connect.java` class and deploy the system using **NetBeans IDE** and **GlassFish Server**.  

Key features include automated seat allocation, real-time reporting, and a centralized admin dashboard for configuration. The lightweight JSP/Servlet architecture ensures quick deployment, while MySQL Workbench simplifies database adjustments.  

**Setup**:  
1. Import `esas.sql` into MySQL.  
2. Update MySQL credentials (default password: `apcl123456`) in `Connect.java`.  
3. Deploy via NetBeans/GlassFish.  

Ideal for schools and universities, the system reduces manual errors in exam planning. **Note**: Change default passwords and admin credentials for production security. Contributions to enhance features or security (e.g., encryption, access controls) are welcome!  
