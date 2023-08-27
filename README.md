# Real Estate Management System

Welcome to the Real Estate Management System! 
This project showcases a comprehensive system designed to streamline property listing, tenant management, and agent tracking in the real estate industry. 
The system was successfully developed and implemented using a combination of HTML, CSS, JavaScript, MySQL database, and APIs for property data retrieval.

### Features
* Efficiently manage property listings, tenants, and agents in the real estate business.
* User-friendly interface for easy navigation and data entry.
* Seamless integration with external APIs to fetch property data for accurate and up-to-date information.
* Secure and robust MySQL database to store and retrieve property, tenant, and agent records.
* Responsive design, making it accessible and functional on various devices.
  
### Installation
* Make sure you have a web server and MySQL database server installed on your system.
* Clone this repository to your local machine or download the ZIP file and extract it into your web server's root directory.
* Set up the MySQL database by importing the provided SQL schema and data files:
  * mysql -u your_username -p your_database < database/schema.sql
  * mysql -u your_username -p your_database < database/data.sql
*Modify the database connection configuration in the config.php file to match your MySQL settings:
  * define('DB_SERVER', 'localhost');
  * define('DB_USERNAME', 'your_username');
  * define('DB_PASSWORD', 'your_password');
  * define('DB_DATABASE', 'your_database');
* Launch the Real Estate Management System by accessing its URL through a web browser:
  * http://localhost/real-estate-management/

### How to Use
* Access the system using the installation steps above.
* The dashboard will provide options to manage properties, tenants, and agents. Navigate through the sections to add, edit, or delete records as needed.
* To fetch property data from external APIs, click on the "Fetch Property Data" button and follow the prompts.
  This will ensure that property information remains accurate and up-to-date.

#### Enjoy the convenience of streamlined real estate management!

### Credits
* The Real Estate Management System project was developed by Harsh Gupta & Team. For any inquiries or feedback, please contact hsg99100@email.com.

#### Acknowledgments to the creators of HTML, CSS, JavaScript, MySQL, and the external APIs used in this project for their invaluable contributions.
