Introduction of Project

For every school important task for administration department is to manage student information in a procedure oriented manner with latest updates for every year which need to be available for easy access. This can be provided by a simple Students Management system to help administration so to efficiently manage student’s details.
To store data MySQL is used by connecting MySQL with Python using MySQL Connector. 
There is also a Login Panel where now admin can register themselves and can Login.
 
 
Admin can perform different types of work such as:

Adding New Student

Viewing Students

Searching Student

Updating Student

Deleting Student

 
Program is easy to use. Every time choices are given to user and the user can select one of them by entering the numbers.
 

Software and Hardware Used

Software to be used:

Python 3.8.5 installation
MySQL for storing information
MySQL Connector (Python)
OS - Windows 10 Pro 64 bit

Hardware to be used:

CPU: Intel Core or Xeon 3GHz (or Dual Core 2GHz) or equal.

Cores: Single (Dual/Quad Core is recommended)

RAM: 4 GB (6 GB recommended)

Graphic Accelerators: OpenGL 1.5 or higher.

Display Resolution: 1280×1024 is recommended, 1024×768 is minimum.



MySQL Table Structure

Admin Table:

+----------+--------------+------+-----+---------+-------+
| Field    | Type         | Null | Key | Default | Extra |
+----------+--------------+------+-----+---------+-------+
| id       | varchar(50)  | YES  |     | NULL    |       |
| password | varchar(100) | YES  |     | NULL    |       |
+----------+--------------+------+-----+---------+-------+
 


Student Information Table:

+------------+--------------+------+-----+---------+-------+
| Field      | Type         | Null | Key | Default | Extra |
+------------+--------------+------+-----+---------+-------+
| sch_no     | int          | NO   | PRI | NULL    |       |
| name       | varchar(100) | YES  |     | NULL    |       |
| class      | varchar(50)  | YES  |     | NULL    |       |
| fee_status | varchar(100) | YES  |     | NULL    |       |
| age        | int          | YES  |     | NULL    |       |
| email      | varchar(150) | YES  |     | NULL    |       |
| phone      | varchar(150) | YES  |     | NULL    |       |
+------------+--------------+------+-----+---------+-------+
 

