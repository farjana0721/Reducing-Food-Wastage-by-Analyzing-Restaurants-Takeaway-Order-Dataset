# Data Management Project- "Reducing Food Wastage by Analyzing Restaurants Takeaway Orders Dataset"
This is my first Master's level project. The project was completed along with my partner Farjana Alam under the supervision of our Professor Vimala Nunavath. <br><br>
**The main motto of the project was analyzing data and visualize it so that output can be predicted.**

**Locations of important files and datasets:**

- Datasets can be found under the Datasets folder

- Jupyter Notebook runnable file is inside ipynb-Jupyter Notebook folder

- Power BI runnable file can be found inside pbix-Power BI folder.

**How to run the ipynb file:**

- Install Anaconda Navigator from here: https://sparkbyexamples.com/python/how-to-install-anaconda-on-windows

- Installation guide for Anaconda Navigator: https://docs.anaconda.com/anaconda/install/

- Install findspark, pyspark, and Java from this link:  https://sparkbyexamples.com/spark/apache-spark-installation-on-windows/
- Installation tutorial for spark: https://sparkbyexamples.com/spark/apache-spark-installation-on-windows/

- From Anaconda Navigator open Jupyter Notebook. After that open the directory where the ipynb file is saved. Now load the file in the Jupyter Notebook text editor. 
- Download MongoDB from here: https://www.mongodb.com/docs/manual/installation/

- Download Studio 3T from here: https://studio3t.com/download
- Connect Studio 3T with MongoDB using this guide: https://studio3t.com/knowledge-base/articles/connect-to-mongodb/ 
- Download PowerBI from this link: https://powerbi.microsoft.com/en-au/getting-started-with-power-bi/
- In section 3 of ipynb file, put the directory where restaurant-1-orders and restaurant-2-orders are saved.

![ss1](https://github.com/Moin-Shahriyar/Data-Management-Project-Reducing-Food-Wastage-by-Analyzing-Restaurants-Takeaway-Orders-Dataset-/blob/main/Screenshots/ss1.PNG)

- In section 12, put the directory where restaurant-1-ingredients and restaurant-2-ingredients datasets are saved.

![ss2](https://github.com/Moin-Shahriyar/Data-Management-Project-Reducing-Food-Wastage-by-Analyzing-Restaurants-Takeaway-Orders-Dataset-/blob/main/Screenshots/ss2.PNG)

- In sections 19 and 20, put your desired local directory where you want to save the restaurant-1-details and restaurant-2-details datasets.

![ss3](https://github.com/Moin-Shahriyar/Data-Management-Project-Reducing-Food-Wastage-by-Analyzing-Restaurants-Takeaway-Orders-Dataset-/blob/main/Screenshots/ss3.PNG)

- In section 21, put the directory where you saved restaurant-1-details and restaurant-2-details datasets.

![ss4](https://github.com/Moin-Shahriyar/Data-Management-Project-Reducing-Food-Wastage-by-Analyzing-Restaurants-Takeaway-Orders-Dataset-/blob/main/Screenshots/ss4.PNG)

- **Tips:** You can skip by commenting out sections 17-20 as it will take a lot of time for data entry. You can use the attached dataset named restaurant-1-details and restaurant-2-details for loading the restaurant orders with ingredients. However, you must change the directory according to your saved location.

**Load pbix file:** 
- To load the Power BI file, go to pbix-Power BI folder and open the pbix file.
Load pbix file from scratch: 
This is the procedure of how we connect our Power BI with MongoDB (Studio 3T). 
- To connect MongoDB with Power BI, we used the Simba ODBC driver which can be found here: 
https://www.magnitude.com/drivers/mongodb-odbc-jdbc?utm_source=google&utm_medium=search&utm_campaign=si-se-Drivers-RTU-2022&utm_content=121468984489&gclid=Cj0KCQjwmouZBhDSARIsALYcourDfv-jCtEEHgtGZ_mxVF_UTMvy6VtdL3MncMVR0Dsc-n7UOJBu6KYaAp0yEALw_wcB 

- You will receive an email for Simba ODBC license. Download the license and paste it under C:\Program Files\Simba MongoDB ODBC Driver\lib directory. The license file should look like this,

 **SimbaMongoDBODBCDriver.lic**

- After downloading and Installing Simba ODBC create a system DSN like the figure given below,

![ss5](https://github.com/Moin-Shahriyar/Data-Management-Project-Reducing-Food-Wastage-by-Analyzing-Restaurants-Takeaway-Orders-Dataset-/blob/main/Screenshots/ss5.PNG)

- Now open Power BI and select ODBC then click connect

![ss6](https://github.com/Moin-Shahriyar/Data-Management-Project-Reducing-Food-Wastage-by-Analyzing-Restaurants-Takeaway-Orders-Dataset-/blob/main/Screenshots/ss6.PNG)

- Select the DSN that you have created, in my case it is BigData

![ss7](https://github.com/Moin-Shahriyar/Data-Management-Project-Reducing-Food-Wastage-by-Analyzing-Restaurants-Takeaway-Orders-Dataset-/blob/main/Screenshots/ss7.PNG)

- Now you can find all the datasets in Power BI which were in MongoDB

![ss8](https://github.com/Moin-Shahriyar/Data-Management-Project-Reducing-Food-Wastage-by-Analyzing-Restaurants-Takeaway-Orders-Dataset-/blob/main/Screenshots/ss8.PNG)

