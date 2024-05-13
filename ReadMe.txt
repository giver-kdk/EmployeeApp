- Cloud Database Setup: 
  - SignUp to freeasphosting.com
  - Create a cloud database in it
  - Generate db generator script(normally generate script for Table) for 2016 version from the desired database in SSMS
- Create 2016 version backup file in .bak format:
  - Goto somee.com website and crate a new database of MySQL2016 version 
  - Run the generated DB creating script on the website
  - Create and download the backup file(.bat) from the website 
  - Upload .bat format database backup file to the freeasphosting.com
  - Import the dump (.bat file) for the cloud database 
  - Use the DB credentials for connection string in ASP.NET Core MVC App

- Reference these videos for overall setup:
  - https://www.youtube.com/watch?v=R75QbUD5XLI
  - https://www.youtube.com/watch?v=3CTPu9QJg_E

