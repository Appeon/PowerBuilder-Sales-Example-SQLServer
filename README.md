# PowerBuilder-Sales-Example-SQLServer

The Sales App demonstrates PowerServer supporting key PowerBuilder constructs and programming styles commonly used in many existing client/server applications. It is developed with Appeon PowerBuilder and deployed to the Cloud with Appeon [PowerServer 2022 R3](https://www.appeon.com/products/powerserver). 

### Sample Project Structure

The project is structured as follows.

```
|—— PowerBuilder-Sales-Example-SQLServer Repository 
                |—— Native_PB                                                              
                |—— Restful_PB
```

### Setting Up the Project

Download this PowerBuilder demo application, and then:

1. Open the PowerBuilder project in PowerBuilder 2022 R3.

2. If you have restored PBDemoDB2022 on your Microsoft SQL Server, you can just skip step#3 and step#4 below to run the PowerBuilder project directly. Otherwise, please follow the steps below to configure your SQL Server Database. 

3. Download the database backup file <b> pbdemodb_for_sqlserver.zip</b> from[PowerBuilder-Project-Example-Database](https://github.com/Appeon/PowerBuilder-Project-Example-Database). 

4. Create an empty database on Microsoft SQL Server with the name PBDemoDB2022. Then restore it using the downloaded database backup file. 

5. Run the PowerBuilder project.
